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
<div class="card mb-3">
    <img class="card-img-top" src="https://lh3.googleusercontent.com/_k3MGe0OY5-AT0g99MJI6_ILqn3wDlRni76UTV5ZNWKviEf--3poXpu0Z0iWVRtys_kxzGFvzxNVENKGvn6EjRPhmTLTxUOKsVNZGeEAYxdWa_txuPcHMAr7JHCgZJ4ocEwYumJ6144GgEfiWyiFH7C6teiHmoNNKNX3ASADStxnHr3EyLRFUOBAA071GZiPb2BI7PufuUOFY3QZ4qwP3kF-kOPMAQ5WqSjeIHmOh6RqN9DUtmJH1Ki4YtByokoi1CrDSZ2aCgi_x_JFj78e_KIt7oZd7pOACHIEcxcENlkFgAayyTGexkF-m_NJnY-jDX98DcAQvj_mFkdlP08tXo29jCzwHvyU8TNW7AbivnhyGiYDAOJi0lIprEqAyfG8hpOiWVxALBBipa9G0k6Hr4ALSRrJTx13asmg9ijGTnjAclRfdIHpbA8bqnfjzBU2ybVGOtDlRnDRWdMDzJ_0J6bRL_KFcr54ZvwWOm30L4wXQ-Mu3v0Ndf4ufllZmax_Q7R7pyhDNUdnrScdReZwmSLyDYyNC2Hf6nfpPU5UhUTr24gkbpSSDuOyyj2sN0ODm6PuJX9cQnTz6mr_xUvq-GYpGZfe9uxgytTHMtUkphJGdmryX0gyJne4SGgzluDTl-sUEPEcNcobQ9Xyau6fR53OGHgQw41COzQg81VYU3v_gfb5C-rADRNc_eestAw=w721-h592-no?authuser=0"/>
</div>
***modify the _config.yml***

the _config.yml file contains some basic configuration for the general use of the template, one thing that you should pay attention is the base_url.
<div class="card mb-3">
    <img class="card-img-top" src="https://lh3.googleusercontent.com/qjetfyXgQLBxR6W6OK2u9z9U-7S7R1aWWv0LfUhy1uQsAfBqcTmoqsOUbVbA37iXGdKNtcwPchjHoYpR4C5Nze4dVPcmw_DoRXmYzlhnLwl_j9_0JB4jETH56lihukLFXoUhm-htCm_Yz6uqfCgNmwiJen7oe-7vtJT1y9-vkx-wvsFVwNARj0tUiv1U3_2upoCD1QVd93jvVH0MjA1PRG1S2A3nOLa_-r3WNgkVsALvjvuGhgCf04_Bz9mlUZMTebRQyeY4BMjZDuHLzZIZm1sGeSYiHhpQKwo3jx-yaZZS9fAnVHRIwClqTvVw53zZx7LkQwElMdgve8b5PO4I_7CvzWjZb9oI1lWV__XCkDayZ1KoItJ0Bg_1ySDChFN0YDKIzax5QHRb76B9ibNea7dldc5wy_gTwEUbPRVTvCYrvaaxJeZZNXN5DUBJ9C7FUH3bhizzuyd9BNTTiRUP11qQ-39ejOAmWRySkS-w6PtfZvM8Kt5IZlMCV9sKYbRuwSmSZHDvrAMc4BN71gzEmkSSRqDuJlyzHJRhWP8H7jVN6mZuMfVqmIHHwZVV_64ZctXGsXsT2v1j3hF51ZY_4HhpOqdgrMWOEwVvp5ZEEyPVSVRNFTyb6Yh62fSsVDVgZXWO51b3u3PcEKeSBrExxCXHONbee8SqUNYKkfDcoDWCiBeFPz2KZ2ru_bTARjg=w838-h345-no?authuser=0"/>

</div>

the base_url should match the name that you use in the repository, in this case super-awesome-blog (that sounds really cool btw) ##WARNING## if you the names don't match you'll have problems, this is because once the page is uploaded the html file will try to look for a specific address and never find it (realizing this took me 3 days :c).

***Upload the files***

Now you can upload the files as needed, I prefer to use Github desktop.
<!--more-->