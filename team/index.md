---
title: People
nav:
  order: 3
  tooltip: Our team
---


# {% include icon.html icon="fa-solid fa-users" %}Lab members

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}



