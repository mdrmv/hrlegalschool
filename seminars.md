---
layout: single
title: "Наши семинары"
permalink: /seminars/
---

<section>

{% for seminar in site.data.seminars.seminars %}
<div style="margin-bottom: 2em; display: flex; align-items: center; gap: 1.5em;">
  <div style="flex: 0 0 150px;">
    <img src="{{ site.baseurl }}{{ seminar.image_path }}" alt="{{ seminar.title }}" style="width: 150px; height: 150px; border-radius: 50%; object-fit: cover;">
  </div>
  <div>
    <h3 style="margin-bottom: 0.2em;">{{ seminar.title }}</h3>
    <p style="margin: 0;">{{ seminar.excerpt }}</p>
  </div>
</div>
<hr/>
{% endfor %}

</section>
