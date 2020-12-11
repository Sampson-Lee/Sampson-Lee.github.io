---
title: "Presentations [(Google Scholar Profile)](https://scholar.google.com/citations?user=pA-TqMEAAAAJ)"
permalink: /presentations/
author_profile: true

---

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

Facial Expression Recognition with IFR, HOS and CC 
Jun. 2018 - May. 2021 (Expected)

Postgraduate Student, Supervised by Prof. Changxing Ding and Prof. Dacheng Tao.
We recognize the categorized emotion of an image which is captured in the challenging wild and accomplish accuracies of 78.46\% on RAF database and 34.48\% on EMOTIC database. 

The main processes include: 
Key Responsibilities:
1) excavate important expression regions (IER) based on keypoints and attention mechanism to detect subtle facial motion, improve the accuracy on RAF database by 0.54% 
<p align="center">
  <img src="https://caozhangjie.github.io/files/caozhangjie_img.jpg?raw=true" alt="Photo" style="width: 450px;"/> 
</p>

2) calculate high-order statistics(HOS) based on low-rank bilinear pooling, improve the accuracy on RAF database by 0.4\% compared to normal bilinear pooling.


3) incorporate context clues (CC) based on specific multi-view attention fusion, improve the accuracy on EMOTIC database by 0.91\% compared to normal attention fusion. 
