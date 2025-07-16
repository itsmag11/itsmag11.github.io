---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
   .left {
      float: left;
   }
   .right {
      float: right;
   }
   .small-gap {
      display: block;
      margin-bottom: 30px; /* Adjust the value as needed */
   }
   .small-gap2 {
      display: block;
      margin-bottom: 50px; /* Adjust the value as needed */
   }
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Ph.D. candidate supervised by [Prof. Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy/) at [MMLab@NTU](https://www.mmlab-ntu.com/), in the College of Computing and Data Science, Nanyang Technological University, Singapore. I am broadly interested in computer vision, with a focus on generative AI.

<span class="small-gap"></span>
Prior to my Ph.D. study, I received my B.Eng. degree with honors (highest distinction) from the same university in 2020. 
During my undergraduate study, I had valuable experience conducting research with [Prof. Lap-Pui Chau](https://www.eie.polyu.edu.hk/~lpchau/) and [Dr. Yi Wang](https://wangyintu.github.io/) on vehicle tracking and crowd counting. 
I also spent a semester at EPFL, working with [Dr. Irene Viola](https://www.ireneviola.com/) and [Dr. Alexiou Evangelos](https://scholar.google.com/citations?user=xFkp8DoAAAAJ&hl=en) on research project about light field and point cloud acquisition.
These experiences collectively contributed to my growth as a researcher and professional.

<!-- <a href='https://scholar.google.com/citations?user=90lIt2QAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> -->


<br />
# &#128240; News
- [06/2025] &#127881; &#127881; &nbsp;<a href="https://itsmag11.github.io/Omegance/" style="text-decoration: none;">Omegance</a> is accepted by ICCV 2025.
- [11/2024] &nbsp;Our recent work <a href="https://arxiv.org/abs/2411.17769" style="text-decoration: none;">Omegance</a> is available on arXiv.
- [06/2024] &nbsp;Our recent work <a href="http://arxiv.org/abs/2406.12805" style="text-decoration: none;">AITTI</a> is available on arXiv.
- [02/2024] &#127881; &#127881; &nbsp;<a href="https://csxmli2016.github.io/projects/w-plus-adapter/" style="text-decoration: none;">W+ Adapter</a> is accepted by CVPR 2024. 
- [08/2023] &#127881; &#127881; &nbsp;<a href="https://proceedings.bmvc2023.org/103/" style="text-decoration: none;">VIRMP</a> is accepted by BMVC 2023. 


<br />
# &#128194; Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/omegance.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Omegance: A Single Parameter for Various Granularities in Diffusion-Based Synthesis

**Xinyu Hou**, Zongsheng Yue, Xiaoming Li, Chen Change Loy <br />
IEEE/CVF International Conference on Computer Vision (**ICCV**), 2025

[arXiv](https://arxiv.org/abs/2411.17769) | [Code](https://github.com/itsmag11/Omegance) | [Project Page](https://itsmag11.github.io/Omegance/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/aitti.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## AITTI: Learning Adaptive Inclusive Token for Text-to-Image Generation

**Xinyu Hou**, Xiaoming Li, Chen Change Loy <br />
arXiv, 2024

[arXiv](http://arxiv.org/abs/2406.12805) | [Supplementary Materials](https://entuedu-my.sharepoint.com/:b:/g/personal/xinyu_hou_staff_main_ntu_edu_sg/EVcLbNo4PYRMkPU3C6av5vcBA3igPLn3eAXG58dpbKwjvw?e=kW8gAK) | [Code](https://github.com/itsmag11/AITTI) | [Project Page](https://itsmag11.github.io/AITTI/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/w+adapter.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## When StyleGAN Meets Stable Diffusion: A W+ Adapter for Personalized Image Generation

Xiaoming Li, **Xinyu Hou**, Chen Change Loy <br />
IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**), 2024

[arXiv](https://arxiv.org/abs/2311.17461) | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_When_StyleGAN_Meets_Stable_Diffusion_a_W_Adapter_for_Personalized_CVPR_2024_paper.pdf) | [Code](https://github.com/csxmli2016/w-plus-adapter) | [Project Page](https://csxmli2016.github.io/projects/w-plus-adapter/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BMVC 2023</div><img src='images/virmp.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Video Infilling with Rich Motion Prior

**Xinyu Hou**, Liming Jiang, Rui Shao, Chen Change Loy <br />
British Machine Vision Conference (**BMVC**), 2023

[Paper](https://papers.bmvc2023.org/0103.pdf) | [Poster](https://bmvc2022.mpi-inf.mpg.de/BMVC2023/0103_poster.pdf) | [Supplementary Materials](https://bmvc2022.mpi-inf.mpg.de/BMVC2023/0103_supp.pdf) | [Project Page](https://proceedings.bmvc2023.org/103/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2021</div><img src='images/wangyi2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## A Self-Training Approach for Point-Supervised Object Detection and Counting in Crowds

Yi Wang, Junhui Hou, **Xinyu Hou**, Lap-Pui Chau <br />
IEEE Transactions on Image Processing (**TIP**), 2021

[Paper](https://ieeexplore.ieee.org/abstract/document/9347744) | [Code](https://github.com/WangyiNTU/Point-supervised-crowd-detection)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICMEW 2021</div><img src='images/wangyi1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Dense Point Prediction: A Simple Baseline for Crowd Counting and Localization

Yi Wang, **Xinyu Hou**, Lap-Pui Chau <br />
IEEE International Conference on Multimedia & Expo Workshops (**ICMEW**), 2021

[Paper](https://ieeexplore.ieee.org/abstract/document/9455954) | [Code](https://github.com/WangyiNTU/SCALNet)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AVSS 2019</div><img src='images/dslcf.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Vehicle Tracking Using Deep SORT with Low Confidence Track Filtering

**Xinyu Hou**, Yi Wang, Lap-Pui Chau <br />
IEEE International Conference on Advanced Video and Signal-Based Surveillance (**AVSS**), 2019

[Paper](https://ieeexplore.ieee.org/abstract/document/8909903)
</div>
</div>


<br /> 
# &#127891; Educations
## Nanyang Technological University, Singapore <br /> 
   <div class="left"><i>Ph.D. in Computer Science</i></div>
   <div class="right">Aug. 2021 &mdash; Present</div>
   <br /> 
   Adviser: [Prof. Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy/)

<span class="small-gap2"></span>
## Nanyang Technological University, Singapore <br /> 
   <div class="left"><i>B.Eng. in Electrical and Electronic Engineering</i></div>
   <div class="right">Aug. 2016 &mdash; Jun. 2020</div>
   <br /> 
   Advisers: [Prof. Lap-Pui Chau](https://www.eie.polyu.edu.hk/~lpchau/) and [Dr. Yi Wang](https://wangyintu.github.io/)
   <br /> 
   - Degree with Honors (Highest Distinction)
   - Dean's List 2019-2020
   - NTU Science and Engineering Scholarship

<span class="small-gap2"></span>
## École Polytechnique Fédérale de Lausanne, Switzerland <br /> 
   <div class="left"><i>Semester Exchange</i></div>
   <div class="right">Sep. 2018 &mdash; Jan. 2019</div>
   <br /> 
   Advisers: [Dr. Irene Viola](https://www.ireneviola.com/) and [Dr. Alexiou Evangelos](https://scholar.google.com/citations?user=xFkp8DoAAAAJ&hl=en)
<br />


<br />
# &#9997; Academic Services
## Conference and Workshop Committee:
- Co-organizer, [4th Mobile Intelligent Photograph and Imaging Workshop (MIPI)](https://mipi-challenge.org/MIPI2025/), ICCV 2025

<span class="small-gap"></span>
## Journal Reviewer:
- International Journal of Computer Vision (IJCV)

<span class="small-gap"></span>
## Conference Reviewer: 
- CVPR 2025
- ICCV 2025
- ICLR 2024, 2025
- NeurIPS 2024, 2025
- ICML 2025
- BMVC 2023, 2024, 2025
- AISTATS 2025


<br />
<script type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=474747&w=350&t=n&d=Yt038fCiB-Z6pytc0E24sPo3vTJPlHp6eY5WSv0eUI4&co=ffffff&cmo=00f2fe&cmn=0069ff&ct=808080"></script>
