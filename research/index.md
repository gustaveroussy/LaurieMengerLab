---
title: Research
description: "Current research of the Menger Lab at Gustave Roussy: engineered CAR-T cells for pediatric cancers, mIDH tumors, epigenetic reprogramming, academic CAR-T production and in vivo CAR-T for fibrosis."
nav:
  order: 1
  tooltip: What we study
---

<div class="page_intro research_intro_header"><span class="eyebrow">Our research · Advanced T-cell Therapy</span><h1>Understand T cells.<br>Rethink their possibilities.</h1><p class="lead">We investigate what limits T-cell responses and how to overcome those barriers. Our work connects functional genomics, immune regulation and the engineering of cell therapies against cancer.</p></div>

<div class="theme_grid" aria-label="Research themes">
{% for theme in site.data.research_themes %}<a class="theme_card" href="#{{ theme.id }}"><span class="theme_badge" aria-hidden="true">↗</span><span class="theme_number">{{ theme.label }}</span><h3>{{ theme.title }}</h3><p>{{ theme.short }}</p>{% if theme.members %}<span class="theme_members">{{ theme.members }}</span>{% endif %}</a>
{% endfor %}</div>

{% include section.html %}

<div class="research_approach"><div><span class="eyebrow">From a question to a target</span><h2>A functional view<br>of immunity.</h2><p>Rather than studying one candidate at a time, genome-wide screens let us investigate many genes together and identify the mechanisms that shape T-cell behavior in vivo.</p></div><ol class="research_pipeline"><li><strong>Perturb</strong><span>Use CRISPR libraries to disrupt genes in primary T cells.</span></li><li><strong>Observe</strong><span>Study how the edited cells behave during an immune response.</span></li><li><strong>Investigate</strong><span>Examine candidate regulators and their potential for T-cell engineering.</span></li></ol></div>

{% for theme in site.data.research_themes %}
{% include section.html %}

<div class="research_axis" id="{{ theme.id }}">
<div class="research_axis_header"><div><span class="eyebrow">{{ theme.label }}</span><h2>{{ theme.title }}</h2></div><p class="research_question">{{ theme.short }}</p></div>
{% if theme.body %}<div class="research_axis_copy">{% for paragraph in theme.body %}<p>{{ paragraph }}</p>{% endfor %}</div>{% endif %}
<dl class="theme_facts">{% if theme.members %}<div><dt>Team</dt><dd>{{ theme.members }}</dd></div>{% endif %}{% if theme.funders %}<div><dt>Funding</dt><dd><ul class="theme_funders">{% for funder in theme.funders %}<li>{% if funder.logo %}<img src="{{ funder.logo | relative_url }}" alt="" loading="lazy">{% endif %}<span>{{ funder.name }}</span></li>{% endfor %}</ul></dd></div>{% endif %}{% if theme.collab %}<div><dt>Collaborations</dt><dd>{{ theme.collab }}</dd></div>{% endif %}</dl>
</div>
{% endfor %}

{% include section.html %}

<div class="research_outlook"><span class="eyebrow">Continuing the investigation</span><h2>New questions at the intersection<br>of biology and engineering.</h2><p>Our broader interests include epigenetic and epitranscriptomic regulation, T-cell exhaustion and synthetic immunology. Discover the papers behind our work or get in touch to discuss a scientific collaboration.</p><div><a class="button" href="{{ '/publications/' | relative_url }}">Explore our publications ↗</a><a href="{{ '/contact/' | relative_url }}">Discuss a collaboration ↗</a></div></div>
