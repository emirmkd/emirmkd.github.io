---
layout: post
title: "Meta tagss"
date: 2016-06-15
published: true
image: img/fbseo.png
thumbnail: img/fbseo.png
---
<p class="postdescription">After setting up the basics, I turned to some other basics that some might take for granted: SEO, Favicons, Website Titles and Facebook OpenGraph. </p>
<!--more-->
<img class="postimg" src="https://emiralkafagi.me/img/fbseo.png">
First, let me say, I started writing this blog post TEN DAYS AGO! I was a bit lazy to write, and then got hung up with work, social life (imagine that) and being lazy. Now, off to the actual blogging(?).
<h3>Favicon</h3>
Interestingly, this was a hard nut to crack because I haven't had a need to set a favicon manually... ever? Wordpress can get you spoiled like that! No need to write a single damn line of code! <br>
<br>
On the other hand, I had no idea what kind of favicon I wanted. I made a simple letter "E" in my favorite color: blue.
<img class="postimg" src="https://emiralkafagi.me/img/fav.png">
What you do is create a 32x32px (for Retina and higher resolution) .png favicon and upload it wherever you want (I try to keep all my images in my /img folder).<br>
Next, you'll need to add this line to the <i>head</i> part: <br>
<div style="background: #272822; overflow:auto;width:auto;border:solid gray;border-width:.1em .1em .1em .8em;padding:.2em .6em;"><table><tr><td><pre style="margin: 0; line-height: 125%">1</pre></td><td><pre style="margin: 0; line-height: 125%"><span style="color: #f92672">&lt;link</span> <span style="color: #a6e22e">rel=</span><span style="color: #e6db74">&quot;shortcut icon&quot;</span> <span style="color: #a6e22e">type=</span><span style="color: #e6db74">&quot;image/png&quot;</span> <span style="color: #a6e22e">href=</span><span style="color: #e6db74">&quot;/img/fav.png&quot;</span><span style="color: #f92672">&gt;</span>
</pre></td></tr></table></div>
(By the way, I use <a href="http://hilite.me/">http://hilite.me/</a> to highlight any kind of code :) )
But, you would change "/favicon.png" to the file path of your favicon (mine is /img/fav.png because my favicon "fav.png" is located in the folder "img")
<h3>Facebook stuff</h3>
