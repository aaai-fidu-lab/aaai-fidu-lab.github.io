---
title: Home
---

<style>
.section-card {
  background-color: #f8f9fa;
  border-radius: 8px;
  padding: 20px;
  margin-top: 20px;
  border-left: 4px solid #e0e0e0;
}
.site-banner {
  margin-bottom: 20px;
  text-align: center;
}
.banner-image {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
h1, h2, h3 {
  margin-top: 1.5em;
  margin-bottom: 0.5em;
}
a {
  color: #0366d6;
}
</style>

<div class="site-banner">
  <img src="{{ '/images/site-banner.png' | relative_url }}" alt="EvalEval 2024 Workshop Banner" class="banner-image">
</div>

<div class="section-card" markdown="1">

# Evaluating Evaluations: Examining Best Practices for Measuring Broader Impacts of Generative AI

A workshop co-located with [NeurIPS 2024](https://neurips.cc/)

*Date: December 14 or 15, 2024 [TBD]*

</div>

<div class="section-card" markdown="1">

## Workshop Overview

Generative AI systems are becoming increasingly prevalent in society, producing text, images, audio, and video content with far-reaching implications. While the NeurIPS Broader Impact statement has notably shifted norms for AI publications to consider negative societal impact, no standard exists for approaching these impact assessments.

This workshop addresses this critical gap by bringing together experts on evaluation science and practitioners who develop and analyze technical systems. We will share existing findings, develop future directions for effective community-driven evaluations, and create comprehensive frameworks for documenting and standardizing evaluation practices.

</div>

<div class="section-card" markdown="1">

### Key Focus: Breadth of Participation

A key focus of this workshop is broadening the expertise involved in shaping evaluations. Involving all participants and stakeholders in a system, not just Machine Learning and AI experts, can yield wide benefits. By encouraging collaboration among experts, practitioners, and the wider community, the workshop aims to create more comprehensive evaluations and develop AI community resources and policy recommendations.

</div>

<div class="section-card" markdown="1">

### Workshop Objectives

1. Share existing findings and methodologies with the NeurIPS community
2. Collectively develop future directions for effective community-built evaluations
3. Address barriers to broader adoption of social impact evaluation of Generative AI systems
4. Develop policy recommendations for investment in future directions for social impact evaluations
5. Create a framework for documenting and standardizing evaluation practices

</div>

<div class="section-card">

## Contents

<div class="toc" markdown="1">
{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

</div>
