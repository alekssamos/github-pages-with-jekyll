---
title: "Welcome to my cool blog"
---

I'm glad you are here. I plan to talk about ...

I didn't know what could be created from markddown, I thought only HTML is supported, and I already have to build HTML from markdown locally and upload it here.

### navigation
{% assign doclist = site.data.samplelist.docs | sort: 'title'  %}
<ol>
{% for item in doclist %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
</ol>
