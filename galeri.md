---
layout: page
title: Galeri
subtitle: "Foto-foto Event J150K"
permalink: /galeri/
feature-img:
---

<div class="flexcontainer pagegallery">
    <img class="flexhalf" src="{{ site.baseurl }}/assets/img/gallery/2.jpg">
</div>

<div class="flexcontainer pagegallery">
  {% for i in (3..12) %}
    <img class="flexhalf" src="{{ site.baseurl }}/assets/img/gallery/{{i}}.jpg">
  {% endfor %}
</div>

<div class="flexcontainer pagegallery">
    <img class="flexhalf" src="{{ site.baseurl }}/assets/img/gallery/13.jpg">
</div>

<div class="flexcontainer pagegallery">
  {% for i in (14..23) %}
    <img class="flexhalf" src="{{ site.baseurl }}/assets/img/gallery/{{i}}.jpg">
  {% endfor %}
</div>

<div class="flexcontainer pagegallery">
    <img class="flexhalf" src="{{ site.baseurl }}/assets/img/gallery/24.jpg">
</div>

<div class="flexcontainer pagegallery">
  {% for i in (25..34) %}
    <img class="flexhalf" src="{{ site.baseurl }}/assets/img/gallery/{{i}}.jpg">
  {% endfor %}
</div>

<div class="flexcontainer pagegallery">
    <img class="flexhalf" src="{{ site.baseurl }}/assets/img/gallery/35.jpg">
</div>

<div class="flexcontainer pagegallery">
  {% for i in (35..50) %}
    <img class="flexhalf" src="{{ site.baseurl }}/assets/img/gallery/{{i}}.jpg">
  {% endfor %}
</div>
