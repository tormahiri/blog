---
layout: post
title:  "css3دا رەسىمگە مەزمۇن چىقىدىغان ھەرىكەت ئۈنۈمى قوشۇش"
excerpt: "A nice post"
date:   2014-12-3 12:36:00
categories: css
---
<img src="http://codropspz.tympanus.netdna-cdn.com/codrops/wp-content/uploads/2011/11/OriginalHoverEffects.jpg"/>
<hr>

<hr>
```html
<h2>div قىسمىغا بۇنى يىزىڭ</h2>

<pre>
    <div class="view">  
     <img src="image.gif" />  
     <div class="mask">  
     <h2>Title</h2>  
     <p>Your Text</p>  
         <a href="#" class="info">Read More</a>  
     </div>  
</div>  
</pre>
```

css كودىغا بۇن يىزىڭ
<pre>
<code>
.view {
    width: 300px;
    height: 200px;
    margin: 10px;
    float: left;
    border: 10px solid #fff;
    overflow: hidden;
    position: relative;
    text-align: center;
    box-shadow: 1px 1px 2px #e6e6e6;
    cursor: default;
    background: #fff url(../images/bgimg.jpg) no-repeat center center
}
.view .mask, .view .content {
    width: 300px;
    height: 200px;
    position: absolute;
    overflow: hidden;
    top: 0;
    left: 0
}
.view img {
    display: block;
    position: relative
}
.view h2 {
    text-transform: uppercase;
    color: #fff;
    text-align: center;
    position: relative;
    font-size: 17px;
    padding: 10px;
    background: rgba(0, 0, 0, 0.8);
    margin: 20px 0 0 0
}
.view p {
    font-family: Georgia, serif;
    font-style: italic;
    font-size: 12px;
    position: relative;
    color: #fff;
    padding: 10px 20px 20px;
    text-align: center
}
.view a.info {
    display: inline-block;
    text-decoration: none;
    padding: 7px 14px;
    background: #000;
    color: #fff;
    text-transform: uppercase;
    box-shadow: 0 0 1px #000
}
.view a.info:hover {
    box-shadow: 0 0 5px #000
}
</code>

</pre>



