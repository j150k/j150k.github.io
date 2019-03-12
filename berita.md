---
layout: default
title: Berita
permalink: /berita/
feature-img:
---

<!--Berita Terbaru -->
<article class="feature-image">
  <header {% if page.feature-img %}style="background-image: url('{{ site.baseurl }}/{{ page.feature-img }}')"{% endif %} class="yellow-navy">
    <h1 class="title">{{ page.title }}</h1>
    {% if page.subtitle %}<h2 class="subtitle">{{ page.subtitle }}</h2>{% endif %}
  </header>
</article>
<div class="posts flexcontainer">
  {% for post in site.posts %}
  <div class="post-teaser flexhalf">
    <header>
      <h1>
        <a class="post-link" href="{{ post.url | relative_url }}">
          {{ post.title }}
        </a>
      </h1>
      <p class="meta">
        {{ post.date | date: "%B %-d, %Y" }}
      </p>
    </header>
    <div class="excerpt">
      {% if post.image %}<img src="{{ post.image }}">{% endif %}
      <br>{{ post.excerpt }}<br>
      <a class="button" href="{{ post.url | relative_url }}">
        {{ site.theme_settings.str_continue_reading }}
      </a>
    </div>
  </div>
  {% endfor %}
</div>
