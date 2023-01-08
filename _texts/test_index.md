---
layout: page
title: Complete Works
permanlink: /complete-works/
---
The catalog is under development, and additional works will be added as information is processed.

Works are organized by instrumentation. 

<div class="toc">

<h3>Chamber Music - Instrumental</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.inst == "cham-inst" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
    
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
    
 <h3>Orchestra and Chorus</h3>
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

<h3>Orchestra and Solo Instrument</h3>
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
    
<h3>Orchestra and Solo Voice</h3>
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
    
 <h3>Organ</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.inst == "organ" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
    
 <h3>Piano - Concert Works</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.inst == "piano-conc" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
    
<h3>Piano - Teaching Pieces</h3>
    <ul class="texts">
    {% for item in site.texts %}
      {% if item.inst == "piano-teach" %}
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
