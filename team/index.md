---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Current team members. 

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}

{% include section.html %}

## {% include icon.html icon="fa-solid fa-user-group" %}Alumni

<ul class="alumni-list">
{% for person in site.data.alumni %}
  <li>{{ person.name }}</li>
{% endfor %}
</ul>

{% include section.html background="images/background.jpg" dark=true %}

About our team:

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
