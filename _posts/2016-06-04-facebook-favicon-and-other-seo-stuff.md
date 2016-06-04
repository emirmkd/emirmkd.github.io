---
layout: post
title: "Facebook, favicon and other SEO stuff"
date: 2016-06-04
published: true
thumbnail: http://cognitiveseo.com/blog/wp-content/uploads/2013/05/facebook-seo.png
---
<img class="postimg" src="http://cognitiveseo.com/blog/wp-content/uploads/2013/05/facebook-seo.png">
After setting up the basics, I turned to some other basics that some might take for granted: SEO, Favicons, Website Titles and Facebook OpenGraph. <br>
<h3>Favicon</h3>
Interestingly, this was a hard nut to crack because I haven't had a need to set a favicon manually... ever? Wordpress can get you spoiled like that! No need to write a single damn line of code! <br>
<br>
On the other hand, I had no idea what kind of favicon I wanted. I made a simple letter "E" in my favorite color: blue.
<img class="postimg" src="http://emiralkafagi.me/img/fav.png">
What you do is create a 32x32px (for Retina and higher resolution) .png favicon and upload it wherever you want (I try to keep all my images in my /img folder).<br>
Next, you'll need to add this line to the <i>head</i> part: <br>
{% highlight html %}
<link rel="shortcut icon" type="image/png" href="/favicon.png">
{% endhighlight %}
But, you would change "/favicon.png" to the file path of your favicon (mine is /img/fav.png because my favicon "fav.png" is located in the folder "img")
<h3>Facebook stuff</h3>
When I tried sharing my <a href="http://www.emiralkafagi.me/blog/2016/06/03/why-jekyll">first blog post</a> on Facebook, it didn't really look that great. There was no image and the title and description were the ones I set for my website, but not from the blog post. I did some searching and found all the right answers. <br>
First, 
