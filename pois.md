---
layout: page
title: Λίμνες στην Ελλάδα
permalink: /lakesingreece/

---

<ul>
  {% for p in site.pois %}
    <li>
      <a href="{{ p.url | relative_url}}">{{ p.title }}</a>
    </li>
  {% endfor %}
</ul>
