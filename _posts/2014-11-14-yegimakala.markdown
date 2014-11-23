---
layout: post
title:  "php دا فۇنكىسيەنىڭ بار يوقلۇقىغا ھۆكۈم قىلىش "
excerpt: "A nice post"
date:   2014-11-14 12:36:00
categories: jekyll update
---


<p>تۆۋەندىكى كود بىلەن php دا فۇنكىسيەنىڭ بار يوقلۇقىغا ھۆكۈم قىلغىلى بولىدۇ：</p>

<pre><code>if(!function_exists("gettext")){

	define("yok","mawjut amas");
	echo yok;
}else{

	define("bar"," bu function barkan");
	echo bar;
}
</code></pre>
