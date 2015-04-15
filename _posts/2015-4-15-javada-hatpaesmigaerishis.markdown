---
layout: post
title: "java دا ھەپتە نامىغا ئىرىشىش "
excerpt: "A nice post"
date: 2015-4-15 19:55
categories: java
---
يۇمشاق دېتال ئىچىش ياكى كۈندىلىك خىزمەتلەرنى بىرتەرەپ قىلىشتا بولمىسۇن بىز ھەپتە نامىغا مۇھتاج بولىمىز ،تۆۋەندىكى كود بىلەن بىز java تىلىدىن پايدىلنىپ ھەپتەنىڭ قايسى كۈنى ئىكەنلىكىگە ھۆكۈم قىلالايمىز 

<pre>
<code>
haptaEsmi(Calendar.getInstance());

	public static void haptaEsmi(Calendar c){
		
		  Calendar cal = c.getInstance();
		  int day = cal.get(Calendar.DAY_OF_WEEK);
		  System.out.print("bugun bolsa ");
		  switch(day){
		  case 1: System.out.print("yakxanba");
		  break;
		  case 2: System.out.print("duxanba");
		  break;
		  case 3: System.out.print("sayxanba");
		  break;
		  case 4: System.out.print("qarxanba");
		  break;
		  case 5: System.out.print("payxanba");
		  break;
		  case 6: System.out.print("juma");
		  break;
		  case 7: System.out.print("xanba");
		  break;
		  }
		  System.out.print(".");
		
	}
</code>
</pre>
بۇ كودنى java مۇھىتىدا ئىجرا قىلسىڭىزلا توغرا بولغان ھەپتە ئىسمىغا ئىرىشەلەيىسز 
