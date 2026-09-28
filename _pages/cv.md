---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Haonan Zhang (张皓南)

Ph.D. Student, The Hong Kong University of Science and Technology (Guangzhou)

[Google Scholar](https://scholar.google.com/citations?user=8HUEmMkAAAAJ&hl=en) · [GitHub](https://github.com/southking372)

## Education

- **Ph.D. Student**, The Hong Kong University of Science and Technology (Guangzhou), **2026–Present**
- **M.S. in Biomedical Engineering**, Beihang University, **2023–2026**
- **B.S. in Biomedical Engineering**, Beihang University, **2019–2023**

## Research Interests

- Wearable & Physiological Sensing
- Physiological Signal Processing and Machine Learning
- Biomedical Artificial Intelligence

## Publications

{% for post in site.publications reversed %}
- **{{ post.title }}**  
  {{ post.citation }}  
  {% if post.paperurl %}[Paper]({{ post.paperurl }}){% endif %}
{% endfor %}
