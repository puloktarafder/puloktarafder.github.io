---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<H2>Journals</H2>
1. Pulok Tarafder and Wooyeol Choi*, "MAC protocols for mmWave communication: A comparative survey," Sensors, special issue on "Theory and Techniques for the Deployment of Future Wireless Sensor Networks in 5G and Beyond", vol. 22, no. 10, article no. 3853, May 2022. (IF: 3.576 / JCR 2020) [[doi](https://www.mdpi.com/1424-8220/22/10/3853)]

<H2>Conference papers</H2>
1. P. Tarafder, M. Kang and W. Choi, "A Comparative Study on Centralized MAC Protocols for 60 GHz mmWave Communications," 2021 International Conference on Information and Communication Technology Convergence (ICTC), 2021, pp. 888-892, doi: 10.1109/ICTC52510.2021.9620829.
2. A. S. Meem, H. Bukenya, A. Faisal, P. Tarafder and A. K. M Abdul Malek Azad, "A qualitative study of current trends in microwave wireless power transmission including current advancements and challenges," 2019 IEEE Region 10 Symposium (TENSYMP), 2019, pp. 367-372, doi: 10.1109/TENSYMP46218.2019.8971375.

<H2>Dissertation</H2>
1. http://dspace.bracu.ac.bd/xmlui/handle/10361/12067

<H2>In preperation</H2>
1. An LSTM-GRU Model-Based Channel Prediction Approach for High-Quantization Massive MIMO System

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
