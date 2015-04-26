---
layout: post
title: "ubuntu دا java مۇھىتى ھازىرلاش"
excerpt: "A nice post"
date: 2015-5-26 23:55
categories: linux
---
ئەسسەلامۇ ئەلەيكۇم
بىز ubuntu مەشغۇلات سېستىمىسىدا java مۇھىتى ھازىرلاشنى ئۈگىنىپ ئۆتەيلى،windows دا java مۇھىتى ھازىرلىغانغا قارىغاندا ubuntu دا java مۇھىتى ھازىرلاش پۈتۈنلەي ئوخشاش ئەمەس،شۇڭا بىز ubuntu دا java مۇھىتى ھازىرلاشنىڭ قەدەم باسقۇچىلرى بىلەن تونۇشۇپ چىقىمىز،بۇلاردىن كىيىن ubuntu دا ئەپ ئاچساقمۇ بولىدۇ دىگەن گەپ.
قەدەم باسقۇچلىرى تۆۋەندىكىچە
ئاۋال ubuntu دا terminlaنى ئاچىمىز ،ئاندىن بۇ قۇرلارنى تەرتىپ بويىچە كىرگۈزۈپ ئىجرا قىلساقلا 10 مىنۇت ئىچىدە پۈتۈن مەشغۇلات تامام بولىدۇ.
<pre>

sudo apt-get purge openjdk*

sudo add-apt-repository ppa:webupd8team/java

sudo apt-get update

sudo apt-get install oracle-java6-installer

sudo nano /etc/environment

JAVA_HOME=/usr/lib/jvm/java-6-oracle/

source /etc/environment
چوقۇم تەرتىپ بويىچە ئىجرا قىلىڭ!

</pre>
