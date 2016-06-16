---
layout: page
title: Archive
---
## Announcements
{% for post in site.posts %}
{% if post.category == "announcements" %}

* [{{post.title}}]({{site.baseurl}}{{post.url}})
{% endif %}
{% endfor %}

## Immortal Executioner
{% for post in site.posts %}
{% if post.category == "zhan-xian" %}

* [{{post.title}}]({{site.baseurl}}{{post.url}})
{% endif %}
{% endfor %}

## Heaven Awakening Path
{% for post in site.posts %}
{% if post.category == "heaven-awakening" %}

* [{{post.title}}]({{site.baseurl}}{{post.url}})
{% endif %}
{% endfor %}

## Martial God
{% for post in site.posts %}
{% if post.category == "martial-god" %}

* [{{post.title}}]({{site.baseurl}}{{post.url}})
{% endif %}
{% endfor %}

## Sin City Teaser
{% for post in site.posts %}
{% if post.category == "sin-city" %}

* [{{post.title}}]({{site.baseurl}}{{post.url}})
{% endif %}
{% endfor %}

## Other
{% for post in site.posts %}
{% if post.category != "announcements" and post.category != "zhan-xian" and post.category != "heaven-awakening" and post.category != "sin-city" and post.category != "martial-god" %}
* [{{post.title}}]({{site.baseurl}}{{post.url}})
{% endif %}
{% endfor %}
