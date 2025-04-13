---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our group is part of the [Department of Mathematics](https://ciencias.medellin.unal.edu.co/escuelas/matematicas/) and the [Department of Physics](https://ciencias.medellin.unal.edu.co/escuelas/fisica/) of the [Faculty of Sciences](https://ciencias.medellin.unal.edu.co) of the [Universidad Nacional de Colombia](https://unal.edu.co). We are an interdisciplinary team with presence in different regions of the country.

{%
  include button.html
  type="email"
  text="crbellor@unal.edu.co"
  link="crbellor@unal.edu.co"
%}
{%
  include button.html
  type="phone"
  text="(+57) 3102023120"
  link="+57-3102023120"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/NYdzTpLUNCdrvA7D9"
  new_tab=true
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/contact1.jpg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contact2.jpg"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/contact3.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3%}