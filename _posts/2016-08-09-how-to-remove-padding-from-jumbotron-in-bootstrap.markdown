---
layout: post
title:  "How to remove padding from jumbotron in Bootstrap"
date:   2016-08-09 07:58:40 +0200
categories: post
---

If you are having trouble removing the padding from a jumbotron that sits in a container-fluid div in you bootstrap layout, there is a simple solution that you can implement.

This is an example of a correctly formatted jumbotron that spans 100% of the available screen space, without any padding on either side. 

In the following code snippet, the jumbotron sits just below the navbar, and it spans the full width of the viewport, just like the navbar above it:

{% highlight html %}
    <div class="container-fluid">
      <div class="row">
       <div id="jumbotron" class="jumbotron text-center">
         <h1>Our Blog</h1>
         <h2>Such a Simple Blog Layout</h2>
       </div><!-- /.jumbotron --> 
      </div><!-- /.row -->
    </div><!-- /.container -->
{% endhighlight %}

Check out the [Our Blog][ourblog-theme] bootstrap theme to see an example of a layout where this is implemented.

[ourblog-theme]: {{ site.url }}/template-overviews/our-simple-blog
