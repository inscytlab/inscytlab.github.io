---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The InSCyTLab has the following researchers with collective expertise in software engineering, artificial intelligence, cybersecurity, and system development who share a common interest in research innovation for improving and securing software development and systems through artificial intelligence technologies:

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

The InSCyTLab collaborates closely with researchers nationally and internationally, such as Adelaide University, Deakin University, University of Queensland, UNSW, Nanjing University, and Tianjin University. 

{% include section.html %}

{% capture content %}

{% include figure.html image="images/au.png"%}
{% include figure.html image="images/deakin.png"%}
{% include figure.html image="images/uq.png"%}
{% include figure.html image="images/unsw.png"%}
{% include figure.html image="images/nju.png"%}
{% include figure.html image="images/tju.png"%}

{% endcapture %}

{% include grid.html style="square" content=content %}
