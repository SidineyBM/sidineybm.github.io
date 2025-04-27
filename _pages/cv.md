---
layout: cv
title: titles.cv
permalink: /cv/
nav: true
nav_order: 3
cv_pdf: Sidiney_Montanhano_Curriculum_Vitae.pdf
description: #descriptions.cv
toc:
  sidebar: #left
lang: pt
---

# {{ site.data.translations[page.lang].titles.cv }}

{% if page.lang == "en" %}
<iframe src="/assets/pdf/en/Sidiney_Montanhano_Curriculum_Vitae.pdf" style="width:100%; height:800px;" frameborder="0"></iframe>
{% else %}
<iframe src="/assets/pdf/pt-br/Sidiney_Montanhano_Curriculum_Vitae.pdf" style="width:100%; height:800px;" frameborder="0"></iframe>
{% endif %}
