---
title: "Research"
layout: post
permalink: /research/
published: true
---

This area will eventually fill up with research related stuff.

{% for post in site.posts %}
<h3><a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a></h3>
{% endfor %}
