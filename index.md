---
description: "The Menger Lab (Laurie Menger, Gustave Roussy, INSERM U1356) studies and engineers T cells to advance CAR-T and cancer immunotherapy."
title: Advanced T-cell Therapy at Gustave Roussy
---

<div class="hero hero_immersive">
  <div class="hero_text">
    <span class="eyebrow">Menger Lab · Advanced T-cell Therapy</span>
    <h1 class="hero_title">Engineering T&nbsp;cells to <span class="accent">outsmart cancer</span>.</h1>
    <p class="lead">How can we help immune cells overcome cancer? At Gustave Roussy, we combine CRISPR screening and T-cell engineering to turn that question into new therapeutic strategies.</p>
    <div class="hero_actions">
      <a class="button" href="{{ '/research' | relative_url }}">Explore our research <span aria-hidden="true">↗</span></a>
      <a class="button" data-style="ghost" href="{{ '/team' | relative_url }}">Meet the team</a>
    </div>
  </div>
  <div class="hero_visual">
    <img src="{{ 'images/home/crispr_hero.jpg' | relative_url }}" alt="Illustration of CRISPR-Cas9 editing a DNA double helix" loading="eager" fetchpriority="high" />
    <span class="hero_caption">Exploring the potential of living therapies</span>
  </div>
</div>

<div class="lab_affiliations" aria-label="Research environment">
  <span>Based at <strong>Gustave Roussy</strong></span>
  <span>Research unit <strong>INSERM U1356</strong></span>
  <a href="{{ '/publications' | relative_url }}">Discover our publications <span aria-hidden="true">↗</span></a>
</div>

<div class="research_path" aria-labelledby="research-path-title">
  <div class="research_intro"><span class="eyebrow">Our scientific approach</span><h2 id="research-path-title">Understand the barriers.<br>Expand the possibilities.</h2></div>
  <a href="{{ '/research' | relative_url }}" class="research_step"><span class="research_label">Discover</span><h3>Find what holds T cells back.</h3><p>Use in vivo CRISPR screening to investigate the factors that limit immunity inside tumors.</p><span class="research_more">CRISPR screening <span aria-hidden="true">↗</span></span></a>
  <a href="{{ '/research' | relative_url }}" class="research_step"><span class="research_label">Engineer</span><h3>Build on the biology.</h3><p>Explore CAR-T strategies and edit tumor-infiltrating lymphocytes to improve their function.</p><span class="research_more">T-cell engineering <span aria-hidden="true">↗</span></span></a>
  <a href="{{ '/publications' | relative_url }}" class="research_step"><span class="research_label">Advance</span><h3>Connect discovery to therapy.</h3><p>Bring functional genomics and synthetic immunology together to inform future cell therapies.</p><span class="research_more">Research publications <span aria-hidden="true">↗</span></span></a>
</div>

{% include section.html %}

{% capture text %}
Laurie is an INSERM researcher and young group leader of the Advanced T-cell Therapy team (U1356) at Gustave Roussy, specialized in Onco/Immunobiotechnology. She has built her career on multidisciplinary approaches to drive immunotherapeutic projects toward translational development. In 2019 she obtained an ANR Jeune Chercheur grant, and in 2021 an ATIP-Avenir (INSERM) and a Gustave Roussy starting package. Her research feeds two flagship medico-scientific programs: precision medicine (PRISM) and Innovative Therapeutics.

{%
  include link.html
  link="/members/lmenger.html"
  text="Learn more"
  icon="fas fa-arrow-right"
  flip=true
%}
{% endcapture %}

{%
  include feature.html
  image="images/home/laurie_menger.jpeg"
  title="Dr. Laurie Menger"
  component="portrait"
  text=text
%}

{% include section.html %}

<span class="eyebrow">What we do</span>
## Research at a glance

{% capture text %}
Our team was the first in Europe to establish in&nbsp;vivo CRISPR-Cas9 screening in primary T cells, building a functional pipeline for the systematic, unbiased characterization of the factors that limit T-cell function in complex immunosuppressive environments.

{%
  include button.html
  link="research"
  text="See our research"
  icon="fas fa-arrow-right"
  flip=true
%}
{% endcapture %}
{%
  include feature.html
  image="images/home/crispr_hero.jpg"
  title="In vivo CRISPR screening"
  text=text
%}

{% capture text %}
We integrate genome-wide CRISPR activation, editing of tumour-infiltrating lymphocytes and combinatorial CAR strategies to design more effective, safer and more affordable adoptive cell therapies against cancer.

{%
  include button.html
  link="research"
  text="Our therapeutic approaches"
  icon="fas fa-arrow-right"
  flip=true
%}
{% endcapture %}
{%
  include feature.html
  image="images/home/car_t_attack.jpg"
  title="Engineering CAR-T therapies"
  flip=true
  text=text
%}

{% capture text %}
By modulating the epigenetic regulators of the antitumor response and combining metabolic and single-cell profiling, we turn the biology of T cells into a programmable platform for synthetic immunology.

{%
  include button.html
  link="publications"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{% endcapture %}
{%
  include feature.html
  image="images/home/nwDbPcKC.jpeg"
  title="Synthetic immunology"
  text=text
%}

{% include section.html %}

<div class="lab_invitation">
  <img src="{{ 'images/action/gastronomie_team.jpg' | relative_url }}" alt="Menger Lab team sharing a meal" loading="lazy" />
  <div class="lab_invitation_text">
    <span class="eyebrow">Science is a team effort</span>
    <h2>Bring your curiosity.<br>Help shape what comes next.</h2>
    <p>We bring together immunology, biotechnology and data science to explore new directions in cancer immunotherapy. Get to know the people behind the research.</p>
    <div class="hero_actions"><a class="button" href="{{ '/opportunities' | relative_url }}">Explore opportunities <span aria-hidden="true">↗</span></a><a class="invitation_link" href="{{ '/contact' | relative_url }}">Collaborate with us <span aria-hidden="true">↗</span></a></div>
  </div>
</div>

{% include section.html %}

<span class="eyebrow">With the support of</span>
## Our research is funded by

{%
  include gallery.html
  style="square"

  image1="images/home/founding/Gustave-Roussy.jpg"
  image2="images/home/founding/logo-inserm.jpg"
  image3="images/home/founding/marie_curie.jpeg"
  image4="images/home/founding/ligue_contre_le_cancer.jpeg"
  image5="images/home/founding/atip.jpeg"
  image6="images/home/founding/logo_institut_national_du_cancer-400x400.png"
  image7="images/home/founding/u_paris_saclay.png"
  image8="images/home/founding/anr_logo.jpg"
  image9="images/home/founding/PKC_logo.png"
%}
