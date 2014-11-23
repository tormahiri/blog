---
layout: post
title: "SQL دىكى LIKE جۈملىسنى قوللىنىش"
excerpt: "A nice post"
date: 2014-11-15 14:24
categories: jekyll update
---
sql دىكى like جۈملىسى سانلىق مەلۇمات جەدۋىلى ئىچىدىكى مەلۇم بۆلەكتىن ماس شەكىلنى ئىزدەشكە قوللىنىلىدۇ! sql جۈملىسى ئارقىلىق بىز jadwalnami دىگەن جەدۋەلنىڭ شەھەر دەپ نام بىرىلگەن بۆلىكدىن (cloumn) دىن h ھەرىپىگە ماسلاشقان بارلىق شەھەر ئىسمنى تاپالايمىز
<pre>
<code>
SELECT * FROM jadwalnami WHERE xahar LIKE 'h%';
</code>
</pre>
