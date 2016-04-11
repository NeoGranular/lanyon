---
layout: page
title: Archive
---
{% for post in site.posts %}
* [{% if post.category == "zhan-xian" %}*IE* - {% elsif post.category == "heaven-awakening" %}*HAP* - {% endif %}{{post.title}}]({{site.baseurl}}{{post.url}})
{% endfor %}
