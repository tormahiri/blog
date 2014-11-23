---
layout: post
title: "PYTHON دا ھۆججەت ئىزدەش"
date: 2014-11-15 16:27
categories: python
---
PYTHON دا ھۆججەت ئىزدەش
بۇ كىچىك پىروگىراممىنى چۈشۈرۈپ ئىجرا قىلسىڭىز ،كىڭەيتىلگەن نامى xml دىن باشلانغان ھۆججەتلەرنى سىزبەلگىلەپ بەرگەن مۇندەرىجە ئىچىدىن تىپىپ چىقىدۇ،ئاندىن نەتىجىنى بىردانە txt ھۆججىتى ئىچىگە قالدۇرىدۇ،ئەلۋەتتە تاپماقچى ۋە بولغان مۇندەرىجە ۋە ھۆججەتنىڭ كىڭەيتىلگەن نامىنى ئۆزىڭىز بەلگىلەپ بىرىىسز!
كود
<pre>
<code>
import os  
# izidmakqi bolgan mundaria mundarija = 'C:\java\.idea' # kigaytilgan namini xlmnig orniga .txt digandak alamxurug 
kigaytilganName = '.xml' natija = 'tapkini.log'  results = str()   
for dirpath, dirnames, files in os.walk(mundarija):  
for name in files:      
if name.lower().endswith(kigaytilganName):    
results += '%s\n' % os.path.join(dirpath, name) 
# log hojjitiga natijini yazidu with open(natija, 'w') as logfile:  
logfile.write(results)
</code>
</pre>
