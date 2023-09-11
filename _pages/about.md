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

Hou Xinyu is currently a Ph.D. candidate supervised by <a href="https://www.mmlab-ntu.com/person/ccloy/">Prof. Chen Change Loy</a> at <a href="https://www.mmlab-ntu.com/"> MMLab@NTU</a>, in the School of Computer Science and Engineering, Nanyang Technological University, Singapore. Prior to her Ph.D. study, she also received her B.Eng. degree with honors (highest distinction) in 2020 from Nanyang Technological University, Singapore.

My research interest includes neural machine translation and computer vision. I currently have a total citation of <a href='https://scholar.google.com/citations?user=90lIt2QAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- *2023.08*: &nbsp;Our paper <i>Viedo Infilling with Rich Motion Prior</i> is accepted by BMVC 2023. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BMVC 2023</div><img src='images/virmp.jpg' alt="sym" height="200" width="300"></div></div>
<div class='paper-box-text' markdown="1">

[Video Infilling with Rich Motion Prior]()

**Xinyu Hou**, Liming Jiang, Rui Shao, Chen Change Loy

[**Project**]() <strong><span class='show_paper_citations' data='90lIt2QAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

# 📖 Educations
- *2021.08 - now*, Ph.D. in Computer Science <br /> Nanyang Technological University
- *2016.08 - 2020.06*, B.Eng. in Electrical and Electronic Engineering  <br /> Nanyang Technological University 
