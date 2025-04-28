---
layout: single
title: "Наши семинары"
permalink: /seminars/
---

# Наши семинары

<div style="display: flex; flex-direction: column; gap: 2em;">

{% for seminar in site.data.seminars.seminars %}
  <div style="display: flex; align-items: center; gap: 1.5em;">
    <img src="{{ seminar.image_path }}" alt="{{ seminar.title }}" style="width: 150px; height: auto; border-radius: 10px; object-fit: cover;">
    <div>
      <h2 style="margin: 0;">{{ seminar.title }}</h2>
      <p style="margin: 0;">{{ seminar.excerpt }}</p>
    </div>
  </div>
{% endfor %}

</div>
