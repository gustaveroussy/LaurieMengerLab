---
title: Team
nav:
  order: 4
  tooltip: About our team
---

{% include section.html %}

# <i class="fas fa-users"></i>Team

We're an interdisciplinary team of researchers who strive to be rigorous, reproducible, and transparent. Our core values include learning from each other and celebrating the success of others.

## Current lab members
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: md"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: ^(?!pi$)"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: ra"
%}

## Alumni

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: alumni"
%}

{% include section.html %}

## Some Pictures

{% capture content %}

{%
  include figure.html
  image="images/action/gastronomie_team.jpg"
  caption="Noël gastronomiques 2024 Paris"
  link="team"
  width="100%"
%}

{%
  include figure.html
  image="images/action/photo_lab.png"
  caption="lab member"
  link="team"
  width="100%"
%}

{%
  include figure.html
  image="images/action/old_photo.png"
  caption="lab member 2022-2023"
  link="team"
  width="100%"
%}

{% endcapture %}

{% include grid.html content=content %}
