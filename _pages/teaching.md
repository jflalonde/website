---
layout: page
permalink: /teaching/
title: teaching
description: All course materials (in French) are available at the links below. Feel free to use. 
---

<h3>MAT-2930 Algèbre linéaire appliquée</h3>

<div class="flex-container">
{% for teaching in site.data.teaching.mat2930 %}
  {% include teaching.html teaching=teaching %}
{% endfor %}
</div>


<h3>GIF-4105/7105 Photographie algorithmique</h3>

<div class="flex-container">
{% for teaching in site.data.teaching.gif4105 %}
  {% include teaching.html teaching=teaching %}
{% endfor %}
</div>

<h3>GIF-1001 Ordinateurs : structure et applications</h3>

<div class="flex-container">
{% for teaching in site.data.teaching.gif1001 %}
  {% include teaching.html teaching=teaching %}
{% endfor %}
</div>


