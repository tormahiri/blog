---
layout: post
title: "CSS  ئاستى ئۈستىگە تيىلدىغان تىيلغۇچ ياساش"
date: 2014-11-15 16:37
categories: css
---
بۇ كود ناھايتى پاكىزە،html ئېلمىنتىندىن پەقەت بىرنىلا تەلەپ قىلىدۇ،ھىچقانداق javascript نىڭ ئېلمىنت ھەرىكەتلەندۈرۈش قىستۇرمىسى تەلەپ قىلمايدۇ بۇكودتىن پۈتۈپ چىقىدىغان ئۈنۈم كونۇپكىنى باسقاندىن كيىن ئىچىدىكى مەزمۇن ئۈستىگە تيىلدۇ،يەنە بارسقاندىن ئاستىغا تيىلىدۇ،ئەمىسە كودنى يىزىشنى باشلايلى،ئاخرىدا ئۈنۈمىنى كۆرىمىز
CSS كودىغا بۇنى يازىمىز
<pre>

<code>
.tiyilguqi { overflow-y: hidden; font-family:alkatip; direction:rtl; max-height: 500px;
/* tahminan magx-height egizliki */
background: orange; transition-property: all; transition-duration: .5s; 
transition-timing-function: cubic-bezier(0, 1, 0.5, 1); height: 200px; width: 200px; }
.tiyilguqi.qekin { max-height: 0; }
</code>
</pre>
HTML كودىغا بۇنى يازىمىز
<pre>
<code>
<div id="tiyilguqi">
    بىلىم ئالمىغان ياش تام تۈۋىدىكى تاش
</div>
<button onclick="document.getElementById('tiyilguqi').classList.toggle('qekin');">ھەرىكەت</button>
</code>
</pre>



مەن بۇ كودتىكى ئۈنۈمنى بىكەتنىڭ JAVASCRIPT دەرسلىرى سەھىپسدىكى«JAVASCRIPT ھەققىدە ››دىگەن مەزمۇنى ئىشلەتتىم،شۇيەردىن تخىمۇ ياخشىراق چۈشەنچىگە ئىگە بولىسىز!
</br>
دىققەت:
</br>
CSSكودىدىكى بەزى خاسلىقلار كونا توركۆرگۈچلەرنى قوللىمايدۇ،شۇڭلاشقا CHROME ياكى FIREFOX نىڭ ئەڭ يىڭى نەشىرىدە قوللىنىڭ!
