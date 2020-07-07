---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* Peer-Reviewed Conference Papers
    * [C2] **Yikun Li**, Mohamed Soliman, Paris Avgeriou. “Identification and Remediation of Self-Admitted Technical Debt in Issue Trackers”. In 2020 46th Euromicro Conference on Software Engineering and Advanced Applications (SEAA), Portorož, Slovenia, 2020, Accepted. [PDF](https://yikun-li.github.io/publications/SEAA2020.pdf)  [BIB](https://raw.githubusercontent.com/yikun-li/yikun-li.github.io/master/_publications/SEAA2020_BIB.html)
    
    * [C1] **Yikun Li**, Lambert Schomaker, S. Hamidreza Kasaei. “Learning to Grasp 3D Objects using Deep Residual U-Nets”. In 2020 29th IEEE International Conference on Robot and Human Interactive Communication (RO-MAN), Naples, Italy, 2020, Accepted. [PDF](https://yikun-li.github.io/publications/RO-MAN2020.pdf)  [BIB](https://raw.githubusercontent.com/yikun-li/yikun-li.github.io/master/_publications/RO-MAN2020_BIB.html)
    
* Workshop Papers
    * [W1] **Yikun Li**, Lambert Schomaker, S. Hamidreza Kasaei, “Learning to Detect Grasp
Affordances of 3D Objects using Deep Convolutional Neural Networks”. In Robotics: Science and Systems (RSS), 2nd Workshop on Task-Informed Grasping (TIG-II): From Perception to Physical Interaction, Freiburg, Germany, 2019. [PDF](https://yikun-li.github.io/publications/TIG-II2019.pdf)  [BIB](https://raw.githubusercontent.com/yikun-li/yikun-li.github.io/master/_publications/TIG-II2019_BIB.html)