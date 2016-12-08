---
layout: page
title: Love
header: Love
group: navigation
permalink: /love/index.html
start_date: 2016-10-15
---
# Yuanyuan is my girlfriend. 
{% comment %} convert our dates to Number of seconds 
              since 1970-01-01 00:00:00 UTC {% endcomment %}
{% assign nowTimestamp = 'now' | date: '%s' %}

{% comment %} difference in seconds {% endcomment %}
{% assign diffSeconds = nowTimestamp | minus: 1476525600 %}

{% comment %} difference in days {% endcomment %}
{% assign diffDays = diffSeconds | divided_by: 3600 | divided_by: 24 %}

We have been in a romantic relationship for {{ diffDays }} days. 
We love each other so much.
I never thought that I could find a perfect girlfriend like her.
I am very happy every day just becasue I can see her anytime I want.
We both hope that out relationship lasts forever.


