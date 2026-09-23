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

- **Ph.D. Student**, The Hong Kong University of Science and Technology (Guangzhou)
- **M.S. in Biomedical Engineering**, Beihang University
- **B.S. in Biomedical Engineering**, Beihang University

## Research Interests

- Physiological sensing
- Wearable and non-invasive health monitoring
- Physiological signal processing and machine learning
- Biomedical artificial intelligence

## Publications

{% for post in site.publications reversed %}
- **{{ post.title }}**  
  {{ post.citation }}  
  {% if post.paperurl %}[Paper]({{ post.paperurl }}){% endif %}
{% endfor %}
