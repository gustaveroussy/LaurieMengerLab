---
description: "Meet the Menger Lab team at Gustave Roussy: immunologists, engineers and bioinformaticians working on T-cell and CAR-T therapies, led by Laurie Menger."
title: Team
nav:
  order: 4
  tooltip: About our team
---

<div class="page_intro"><span class="eyebrow">The people behind the science</span><h1>Different perspectives.<br>A shared curiosity.</h1><p class="lead">An interdisciplinary team connecting immunology, cell engineering and bioinformatics at Gustave Roussy. We learn from each other and celebrate each other's discoveries.</p><a class="button" href="{{ '/opportunities/' | relative_url }}">Explore opportunities <span aria-hidden="true">↗</span></a></div>

{% include section.html %}

## Meet the team

<div class="team_directory">
{% assign role_order = 'pi,md,postdoc,phd,ra,programmer,undergrad,ms' | split: ',' %}
{% for role in role_order %}
{% assign members = site.members | where: 'role', role | sort: 'name' %}
{% for member in members %}
{% include member-card.html member=member %}
{% endfor %}
{% endfor %}
</div>

{% assign alumni = site.members | where: 'role', 'alumni' %}
{% if alumni.size > 0 %}
## Alumni

<div class="team_directory team_alumni">
{% for member in alumni %}{% include member-card.html member=member %}{% endfor %}
</div>
{% endif %}

{% include section.html %}

<div class="team_life"><div><span class="eyebrow">Beyond the bench</span><h2>Good science starts<br>with a strong team.</h2><p>From experiments to shared meals, life in the lab is about the people we work with.</p><a href="{{ '/contact/' | relative_url }}">Get in touch <span aria-hidden="true">↗</span></a></div><figure><img src="{{ 'images/action/gastronomie_team.jpg' | relative_url }}" alt="Team Christmas meal in Paris" loading="lazy"><figcaption>Christmas in Paris · 2024</figcaption></figure></div>

<div class="team_memories">
<figure><img src="{{ 'images/action/photo_lab.png' | relative_url }}" alt="Members of the laboratory" loading="lazy"><figcaption>Life in the lab</figcaption></figure>
<figure><img src="{{ 'images/action/old_photo.png' | relative_url }}" alt="Laboratory team in 2022–2023" loading="lazy"><figcaption>The team · 2022–2023</figcaption></figure>
</div>
