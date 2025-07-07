---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently pursuing the Ph.D degree in Computer Science and Engineering at [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn/). I received my B.E. degree in Artificial Intelligence at Shanghai Jiao Tong University in 2023. My research interests include computer vision, talking head generation, and 3D animation. 

I plan to graduate with a PhD from Shanghai Jiao Tong University in June 2028. if you are interested in my work, please feel free to contact me (mch3148300494@sjtu.edu.cn).


# 🔥 News
- *2025.07*: &nbsp;🎉🎉 One paper accepted to ACMMM 2025. 
- *2024.07*: &nbsp;🎉🎉 One collaborative paper accepted to ACMMM 2024. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2024</div><img src='images/stylizedfacepoint.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[StylizedFacePoint: Facial Landmark Detection for Stylized Characters](https://dl.acm.org/doi/abs/10.1145/3664647.3680984)

Shengran Cheng, **Chuhang Ma**, Ye Pan

- Facial landmark detection forms the foundation for numerous face-related tasks. Recently, this field has gained substantial attention and made significant advancements. Nonetheless, detecting facial landmarks for stylized characters still remains a challenge. Existing approaches, which are mostly trained on real-human face datasets, struggle to perform well due to the structural variations between real and stylized characters. Additionally, a comprehensive dataset for analyzing stylized characters' facial features is lacking. This study proposes a novel dataset, the Facial Landmark Dataset for Stylized Characters (FLSC), which contains 2674 images and 4086 faces selected from 16 cartoon video clips, together with 98 landmarks per image, labeled by professionals. Besides, we propose StylizedFacePoint: a deep-learning-based method for stylized facial landmark detection that outperforms the existing approaches. This method has also proven to work well for characters with styles outside the training domain. Moreover, we outline two primary types of applications for our dataset and method. For each, we provide a detailed illustrative example.
</div>
</div>


# 📖 Educations
- *2023.06 - Present*, [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/), Ph.D. 
- *2019.09 - 2023.06*, [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/), Bachelor. 
