---
layout: page
permalink: /talks/
title: Talks
description:  
nav: true
nav_order: 5
heading: Talks
---


<div class="publications">


I have given many on my research area as well as outreach talks over the years. Below you can find a complete list.


{%- for y in page.years %}
   {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>
