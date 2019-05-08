---
layout: page
title: Links
description: 没有链接的博客是孤独的
keywords: links
comments: true
menu: Links
permalink: /links/
---

> God made relatives. Thank God we can choose our friends.

{% for link in site.data.links %}
* [{{ link.name }}]({{ link.url }})
{% endfor %}
