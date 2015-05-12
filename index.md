---
layout: archive
permalink: /
title: ""
excerpt: ""
image:
  feature: ban2.png

---

<div class="wrap" style="margin-top:5%">

<div class="titles">
{% for post in site.categories.media limit:8 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.titles -->
</div>

<div class="wrap" style="margin-top:10%; margin-bottom:10%; color: gray; background:  ">

<div class="content" style="margin-top:5%; margin-left: 20%; margin-right: 20%">
<center>

<h1><font color="#FE2E64">.. Trick And Trip ..</font></h1>
<br><br>

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/OKN7eeNYHho" frameborder="0" allowfullscreen></iframe></center>

<div class="tiles tiles-3-4">
{% for post in site.categories.articles limit:4 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles-3-4 -->



