---
layout: page
title: Complete Works Index
permanlink: /complete-works/
---
This index is under development, and additional works will be added.

Works are organized by instrumentation and genre. 

<div class="toc">

<h3>Full Orchestra</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.inst == "orchestra" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>

 <h3>Solo Piano</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.inst == "piano" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>

  <h3>Solo Voice and Piano</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.century == "20th" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
</div>