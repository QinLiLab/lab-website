---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html %}
# {% include icon.html icon="fa-solid fa-bullhorn" %}Join us!

The Li Lab has open positions at all levels.

We also welcomes graduate students interested in rotation projects! We are affiliated with the CAMB, GCB, IGG, and Bioengineering programs. If interested, please email Dr. Li with a brief statement of your interest and CV at qinli[at]pennmedicine.upenn.edu.

<!-- {% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %} -->
