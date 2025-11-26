---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you are interested in our research or would like to collaborate with us, you can contact us by email or phone, or visit us at Level 5, Building B, Southern Cross University Gold Coast Campus. 

{%
  include button.html
  type="email"
  text="haifeng.shen@scu.edu.au"
  link="haifeng.shen@scu.edu.au"
%}
{%
  include button.html
  type="phone"
  text="+61 7 5589 3519"
  link="+61-7-5589-3519"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Building+B,+Terminal+Dr,+Bilinga+QLD+4225/@-28.168364,153.5182642,19.2z/data=!4m14!1m7!3m6!1s0x6b9101d962e68801:0xc00f29e5dbc48ba0!2sSouthern+Cross+University,+Gold+Coast+Campus!8m2!3d-28.1686714!4d153.5186189!16s%2Fm%2F0dl5f5x!3m5!1s0x6b9101da2909aab5:0xdcb43de6bfdcbe48!8m2!3d-28.1683343!4d153.5191128!16s%2Fg%2F11b773tbd_?entry=ttu&g_ep=EgoyMDI1MTExNy4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/campus_map.png"
  caption="Campus Map"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/campus_b.png"
  caption="Building B"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
InSCyTLab comprises like-minded researchers who share a common vision of transforming future through technological innovation. 
{% endcapture %}

{% capture col2 %}
InSCyTLab is part of the Information Technology Discipline in the Faculty of Science and Engineering at Southern Cross University in Australia.
{% endcapture %}

{% capture col3 %}
Visit InSCyTLab at Level 5, Building B, Southern Cross University, Gold Coast Campus, next to the Gold Coast Airport.
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
