---
layout: post
title: "ئاندرويىدا تا id نومۇرىنى تىپىش"
date: 2014-12-4 21:27
categories: android
---
android قا ئەپ ئاچقاندا مەلۇم مەقسەتنى ئەمەلگە ئاشۇرۇش ئۈچۈن يانفۇننىڭ كىملىكىگە ھۆكۈم قىلىش زۆرۈر بولىدۇ،بۇ ئەھۋالدا تۆۋەندىكى ئىككى قۇر كود ئارقىلىق بۇ مەقسەتكە يەتكىلى بولىدۇ
<hr>
<img src="http://javatechig.com/wp-content/uploads/2013/11/Get-Device-ID-Example-in-Android-300x438.png">
<pre>

<code>
String id = Secure.getString(getContentResolver(), Secure.ANDROID_ID);

		//textview گە يانفۇننىڭ id ئۇچۇرىنى ئوقۇپ بىرىدۇ
		
		TextView tv = (TextView) findViewById(R.id.textView1);
		tv.setText(id);
</code>
</pre>
