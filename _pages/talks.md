---
layout: page
permalink: /talks/
title: Talks and Trips
description:  
years: [2025, 2024,2023,2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013]
nav: false
heading: Talks
---


<div class="publications">


I have given many on my research area as well as outreach talks over the years. Below you can find a complete list.


{%- for y in page.years %}
   {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>
