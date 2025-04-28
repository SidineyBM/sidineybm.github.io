---
layout: page
title: titles.cv
permalink: /cv/
nav: true
nav_order: 3
cv_pdf: Sidiney_Montanhano_Curriculum_Vitae.pdf
description: #descriptions.cv
toc:
  sidebar: #left
---

#<iframe src="/assets/pdf/en/Sidiney_Montanhano_Curriculum_Vitae.pdf" width="100%" height="1000px" style="border:none;"></iframe>

<div class="container-pdf" style="width: 100%; height: 1000px;">
  {% if page.lang == "en" %}
    <iframe src="{{ '/assets/pdf/en/Sidiney_Montanhano_Curriculum_Vitae-en.pdf' | relative_url }}" width="100%" height="1000px" style="border: none;"></iframe>
  {% else %}
    <iframe src="{{ '/assets/pdf/pt-br/Sidiney_Montanhano_Curriculum_Vitae.pdf' | relative_url }}" width="100%" height="1000px" style="border: none;"></iframe>
  {% endif %}
</div>
