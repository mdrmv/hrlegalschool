---
layout: single
title: "Наши семинары"
permalink: /seminars/
---

{% for seminar in site.data.seminars.seminars %}
## {{ seminar.title }}

{{ seminar.excerpt }}

---
{% endfor %}
