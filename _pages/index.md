---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome adventurer
---

## What is this?

{% include components/intro.md %}

## Navigate the site.

First things first, where am i ?
Well you're in a sort of home page, a basic introduction of the site, I'll explain it.

[About me]({% link _pages/about.md %}) it's a brief summary about me, what i do and stuff like that.

[The blog posts]({% link list/posts.html %}) has the whole list of the post entries, you can search by tag or scroll all the way

<hr />

## Recent Posts
here you have the latest post i have made, have fun.
{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


