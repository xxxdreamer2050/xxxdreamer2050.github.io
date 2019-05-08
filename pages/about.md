---
layout: page
title: About
description: A long way to go.
keywords: XXXDREAMER
comments: true
menu: About
permalink: /about/
---

Many many dreams.

Dreams don't die.

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## About me

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
