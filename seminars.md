---
layout: single
title: "Наши семинары"
permalink: /seminars/
---

# Наши семинары

{% for seminar in site.data.seminars.seminars %}
<div style="margin-bottom: 2em;">
  <img src="{{ seminar.image_path }}" alt="{{ seminar.title }}" style="max-width: 300px; height: auto; border-radius: 10px;">
  <h2>{{ seminar.title }}</h2>
  <p>{{ seminar.excerpt }}</p>
</div>
<hr/>
{% endfor %}
