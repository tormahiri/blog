---
layout: post
title: "JAVASCRIPTدىكى بارلىق ھادىسىلەر تىپىغا ئىرىشىش"
excerpt: "A nice post"
date: 2014-11-15 14:30
categories: jekyll update
---
تۆۋەندىكى كودنى ئىجرا قىلسىڭىزلا،javascript دىكى بارلىق ھادىسىلەر تىپنىڭ تىزىملىكىگە ئىرىشەلەيىسز
<pre>

<code>

Object.getOwnPropertyNames(document)
.concat(Object.getOwnPropertyNames(Object.getPrototypeOf(Object.getPrototypeOf(document))))
.filter(function(i) {return !i.indexOf('on') 
&&(document[i]==null||typeof document[i]=='function');})
</code>
</pre>
