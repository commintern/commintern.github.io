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

I am very happy everyday just becasue I can see her anytime I want.

She is lovely, vivaciously and energetic.

We both believe that out relationship can last forever.

<script>
var end = new Date('02/19/2012 10:1 AM');

    var _second = 1000;
    var _minute = _second * 60;
    var _hour = _minute * 60;
    var _day = _hour * 24;
    var timer;

    function showRemaining() {
        var now = new Date();
        var distance = end - now;
        if (distance < 0) {

            clearInterval(timer);
            document.getElementById('countdown').innerHTML = 'EXPIRED!';

            return;
        }
        var days = Math.floor(distance / _day);
        var hours = Math.floor((distance % _day) / _hour);
        var minutes = Math.floor((distance % _hour) / _minute);
        var seconds = Math.floor((distance % _minute) / _second);

        document.getElementById('countdown').innerHTML = days + 'days ';
        document.getElementById('countdown').innerHTML += hours + 'hrs ';
        document.getElementById('countdown').innerHTML += minutes + 'mins ';
        document.getElementById('countdown').innerHTML += seconds + 'secs';
    }

    timer = setInterval(showRemaining, 1000);
</script>
<div id="countdown"></div>
