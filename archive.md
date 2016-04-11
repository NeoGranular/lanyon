---
layout: page
title: Archive
---
{% for post in site.posts %}
* [{% if post.category == "zhan-xian" %}Immortal Executioner - {% elsif post.category == "heaven-awakening" %}Heaven Awakening Path - {% endif %}{{post.title}}]({{site.baseurl}}{{post.url}})
{% endfor %}
