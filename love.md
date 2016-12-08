---
layout: page
title: Love
header: Love
group: navigation
permalink: /love/index.html
start_date: 2015-03-02 00:00:00
---
# Yuanyuan is my girlfriend. 
{% comment %} convert our dates to Number of seconds 
              since 1970-01-01 00:00:00 UTC {% endcomment %}
{% assign nowTimestamp = 'now' | date: '%s' %}

{% comment %} difference in seconds {% endcomment %}
{% assign diffSeconds = nowTimestamp | minus: start_date %}

{% comment %} difference in days {% endcomment %}
{% assign diffDays = diffSeconds | divided_by: 3600 | divided_by: 24 %}

We have been in a romantic relationship for {{ diffDays }} days. 
We love each other so much.
I never thought that I could find a perfect girlfriend like her.

