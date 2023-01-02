---
layout: page
title: Complete Works
permanlink: /complete-works/
---
The catalog is under development, and additional works will be added as information is processed.

Works are organized by instrumentation and genre. 

<div class="toc">

<h3>Orchestra</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.inst == "orch" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
    
<h3>Solo Instrument and Orchestra</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.inst == "orch-inst" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
    
<h3>Solo Voice and Orchestra</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.inst == "orch-voice" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
    
 <h3>Chorus and Orchestra</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.inst == "orch-chor" %}
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
      {% if item.inst == "pno-voice" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
</div>
