---
layout: front
permalink: /
title: home
image:
    banner: 
---

<div class="tiles">
{% for member in site.data.members %}
   {% if member.year == 2020 %}
   {% include post-grid.html %}
   {% endif %}
{% endfor %}
</div>
<hr/>
