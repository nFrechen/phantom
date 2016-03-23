---
layout: inner
title: Kontakt
permalink: /kontakt/
---

# Kontakt

Tobias Nanu Frechen\\
Schillerstr. 63\\
03046 Cottbus

bitte kontaktieren Sie uns per Mail

<div class="logo-center">
  <img  src="/img/nStat-logo.svg" alt="nStatistics">
</div>






<div class="hero-buttons">
  <a href="mailto:{{ 'mail@n-statistics.de' | encode_email }}"><button class="btn btn-default btn-lg"><i class="fa fa-envelope fa-lg"></i>Mail</button></a>
  {% if site.data.global.twitter != '' %}
    <a href="https://twitter.com/{{ site.data.global.twitter }}"><button class="btn btn-default btn-lg"><i class="fa fa-twitter fa-lg"></i>Twitter</button></a>
  {% endif %}
  {% if site.data.global.github != '' %}
    <a href="https://github.com/{{ site.data.global.github }}"><button class="btn btn-default btn-lg"><i class="fa fa-github fa-lg"></i>Github</button></a>
  {% endif %}
  {% if site.data.global.medium != '' %}
    <a href="http://{{ site.data.global.medium }}"><button class="btn btn-default btn-lg"><i class="fa fa-tablet fa-lg"></i>Blog</button></a>
  {% endif %}

</div>
