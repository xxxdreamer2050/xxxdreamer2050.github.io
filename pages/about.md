---
layout: page
title: About
description: 学无先后 达者为师
keywords: XXXDREAMER, 学匠
comments: true
menu: 关于
permalink: /about/
---

我是学匠，学无先后 达者为师。

一直在路上的小学生。

爱拼才会赢。

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
