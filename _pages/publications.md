---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<H2>Journals</H2>
1. Pulok Tarafder and Wooyeol Choi*, "MAC protocols for mmWave communication: A comparative survey," Sensors, special issue on "Theory and Techniques for the Deployment of Future Wireless Sensor Networks in 5G and Beyond", vol. 22, no. 10, article no. 3853, May 2022. (IF: 3.847 / JCR 2021). [[doi](https://www.mdpi.com/1424-8220/22/10/3853)]

<H2>Conference papers</H2>
1. Pulok Tarafder, Moonsoo Kang and Wooyeol Choi, "A comparative study on centralized MAC protocols for 60 GHz mmWave communications," International Conference on Information and Communication Technology Convergence (ICTC), Jeju, Republic of Korea, October 20-22, 2021, pp. 888-892, doi: 10.1109/ICTC52510.2021.9620829.
2. Afreen Sultana Meem, Henry Bukenya, Abrar Faisal, Pulok Tarafder and A. K. M Abdul Malek Azad, "A qualitative study of current trends in microwave wireless power transmission including current advancements and challenges," 2019 IEEE Region 10 Symposium (TENSYMP), Kolkata, India, 2019, pp. 367-372, doi: 10.1109/TENSYMP46218.2019.8971375.

<H2>Dissertation</H2>
1. http://dspace.bracu.ac.bd/xmlui/handle/10361/12067

<H2>In preperation</H2>
1. Deep Learning Based Channel Estimation Approach for Massive MIMO System
2. Channel Estimation Survey


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
