---
layout: page
title: 大家好！
tagline: 此心光明，亦复何言
---
{% include JB/setup %}

## 测试
这是首页

## 文章测试


文章列表。

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 其他测试

无他
> 这是引用

*  第一
*  第二

**以上列表测试失败，回去研究MD**



