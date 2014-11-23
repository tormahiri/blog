---
layout: post
title: "aدىن zغىچە بولغان ھەرىپنىڭ hex كودىغا ئىرىشىش"
excerpt: "nice post"
date: 2014-11-16 21:27
categories: javascript
---
تۆۋەندىكى كود بىلەن بىز javascript دىن پايدىلنىپ ئا دىن زىغىچە بولغان ھەرىپلەرنىڭ 16لىك كودىغا ئىرىشەلەمىز
كود
<pre>

<code>
// tormahiri
var data = [];
var alphabet = "abcdefghijklmnopqrsuvwxyz".split('');
alphabet.forEach(function (char) {
  data.push({
    lowerCase : char,
    upperCase : char.toUpperCase(),
    hex       : "0x" + char.charCodeAt(0).toString(16)
  });
});

console.table(data);
</code>
</pre>
