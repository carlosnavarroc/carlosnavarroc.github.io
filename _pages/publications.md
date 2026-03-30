---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div style="text-align: justify;">
  <p>My research focuses on computer vision, machine learning, and biomedical applications, with an emphasis on developing AI-driven methods for real-world problems.</p>
</div>

<p>
You can also find my full list of publications on 
<u><a href="https://scholar.google.com/citations?user=406XjUEAAAAJ&hl=es">my Google Scholar profile</a></u>.
</p>

---

## Selected Publications

- **VolumePeeler: a novel FIJI plugin for geometric tissue peeling to improve visualization and quantification of 3D image stacks**  
  <em>BMC Bioinformatics, 2023</em>  
  Developed a software tool for 3D biomedical image visualization and quantification.

- **3D Nuclei Segmentation through Deep Learning**  
  <em>IEEE Conference on Artificial Intelligence, 2023</em>  
  Deep learning approach for 3D nuclei segmentation, achieving top performance in the Cell Tracking Challenge.

- **Cochlear dysfunction as an early biomarker of cognitive decline**  
  <em>Alzheimer’s & Dementia, 2024</em>  
  Identified cochlear dysfunction as a potential early biomarker using signal processing and data analysis.

- **The impact of social isolation and perceived loneliness in older adults**  
  <em>Frontiers in Psychology, 2026</em>  
  Large-scale study on mental health and social factors in older adults post-pandemic.

---

## All Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
