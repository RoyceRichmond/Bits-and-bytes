---
title:  Hey, do you wanna know about jekyll ?
tags:
  - Jekyll
  - Github pages
  - Markdown
---  
Hey, nice to see you.

Well one of the things that i struggle the most when setting up this blog was the configuration, for starters i have no idea of web design, so you may ask, how did you made this blog, well i used a tool (i dont know if it's called that way, but follow me).

Jekyll converts regular text into web pages, kinda like readthedocs, another excellent tool.
Jekyll also has this awesome page with lots of [templates](http://jekyllthemes.org) where you can choose from, and here are some of the things you have to keep in mind if you wanna do a blog hosted on github pages.

***Download the template***

First choose a template from jekyll, download the file from github,	in my case i choose the friday-theme, because it looks cool and simple.

***Create a repository***

OK now you can create the repository with the name that you want, make sure that you remember the exact name, we'll use it later, and initialize it with the README.md
<img src="{{site.baseurl}}/assets/p1_im1.png">
***modify the _config.yml***

the _config.yml file contains some basic configuration for the general use of the template, one thing that you should pay attention is the base_url.
<img src="{{site.baseurl}}/assets/img2.png">
the base_url should match the name that you use in the repository, in this case super-awesome-blog (that sounds really cool btw) ##WARNING## if you the names don't match you'll have problems, this is because once the page is uploaded the html file will try to look for a specific address and never find it (realizing this took me 3 days :c).

***Upload the files***

Now you can upload the files as needed, I prefer to use Github desktop.
<!--more-->