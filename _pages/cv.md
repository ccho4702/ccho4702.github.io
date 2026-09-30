---
layout: page
permalink: /cv/
title: CV
description: Curriculum vitae of Changho Choi.
nav: true
nav_order: 2
---

{% include site_style.liquid %}

{% assign cv_pdf = site.static_files | where: "path", "/assets/pdf/Changho_Choi_CV.pdf" | first %}
{% if cv_pdf %}
[Download my CV (PDF)]({{ '/assets/pdf/Changho_Choi_CV.pdf' | relative_url }})
{% else %}
My CV PDF will be available here soon.
{% endif %}
