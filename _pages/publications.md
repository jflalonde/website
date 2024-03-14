---
layout: page
permalink: /publications/
title: publications
description: Also see <a href="https://scholar.google.com/citations?user=hW9fwNYAAAAJ">Google scholar</a> and/or <a href="https://www.semanticscholar.org/author/Jean-François-Lalonde/144430305">semantic scholar</a>.
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2012, 2011, 2010, 2009, 2008, 2007, 2006, 2005, 2004] 
---

<!-- Link to [Google scholar](https://scholar.google.ca/citations?user=hW9fwNYAAAAJ).  -->

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}