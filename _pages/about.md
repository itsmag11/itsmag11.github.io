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
   .small-gap {
      display: block;
      margin-bottom: 30px; /* Adjust the value as needed */
   }
   .research-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5em;
      margin: 1em 0 0.5em;
   }
   .research-tags span {
      font-size: 0.8em;
      padding: 0.2em 0.8em;
      border-radius: 999px;
      background: #eef2fa;
      color: #4a6db3;
      border: 1px solid #d6e0f3;
   }
   .paper-links {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 0.45em;
      margin-top: 0.6em;
   }
   .paper-links a.pbtn {
      display: inline-flex;
      align-items: center;
      gap: 0.35em;
      font-size: 0.78em;
      padding: 0.2em 0.7em;
      border: 1px solid #d0d7e2;
      border-radius: 6px;
      color: #4a5568;
      text-decoration: none;
      background: #fafbfc;
      transition: all 0.15s ease;
   }
   .paper-links a.pbtn:hover {
      border-color: #4a6db3;
      color: #4a6db3;
      background: #eef2fa;
   }
   .paper-links img {
      vertical-align: middle;
   }
   .edu-item {
      display: flex;
      align-items: flex-start;
      gap: 1.1em;
      margin-bottom: 1.6em;
   }
   .edu-logo {
      flex: 0 0 60px;
      width: 60px;
      height: 60px;
      padding: 8px;
      box-sizing: border-box;
      border: 1px solid #e6ecf5;
      border-radius: 12px;
      background: #fff;
      box-shadow: 0 2px 6px rgba(74, 109, 179, 0.08);
      display: flex;
      align-items: center;
      justify-content: center;
   }
   .edu-logo img {
      max-width: 100%;
      max-height: 100%;
      object-fit: contain;
   }
   .edu-body {
      flex: 1 1 auto;
      min-width: 0;
   }
   .edu-head {
      display: flex;
      justify-content: space-between;
      align-items: baseline;
      flex-wrap: wrap;
      gap: 0.3em 1em;
   }
   .edu-title {
      display: inline-flex;
      align-items: center;
      flex-wrap: wrap;
      gap: 0.3em 0.6em;
   }
   .edu-school {
      font-size: 1.1em;
      font-weight: 700;
   }
   .edu-loc {
      display: inline-flex;
      align-items: center;
      gap: 0.35em;
      font-size: 0.75em;
      font-weight: 600;
      padding: 0.15em 0.65em;
      border-radius: 999px;
      background: #eef2fa;
      color: #4a6db3;
      border: 1px solid #d6e0f3;
      white-space: nowrap;
   }
   .edu-loc i {
      font-size: 0.9em;
   }
   .edu-date {
      font-family: Menlo, Consolas, monospace;
      font-size: 0.85em;
      color: #888;
      white-space: nowrap;
   }
   .edu-degree {
      font-style: italic;
      margin: 0.15em 0;
   }
   .edu-meta {
      font-size: 0.92em;
      color: #666;
   }
   .edu-item ul {
      margin: 0.4em 0 0 0;
      font-size: 0.92em;
   }
   .service-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(210px, 1fr));
      gap: 0.35em 1.5em;
      list-style: none;
      margin: 0.4em 0 0 0;
      padding: 0;
   }
   .service-grid li {
      margin: 0;
      padding-left: 0.8em;
      border-left: 3px solid #d6e0f3;
   }
   .service-grid .venue {
      font-weight: 700;
      margin-right: 0.4em;
   }
   .service-grid .years {
      color: #777;
      font-size: 0.92em;
   }   .news-list {
      list-style: none;
      margin: 0.5em 0 0 0;
      padding: 0 0.6em 0 0;
      max-height: 22em;
      overflow-y: auto;
   }
   .news-list li {
      display: flex;
      align-items: baseline;
      gap: 0.7em;
      padding: 0.45em 0;
      margin: 0;
      border-bottom: 1px dashed #e5e5e5;
      line-height: 1.5;
   }
   .news-list li:last-child {
      border-bottom: none;
   }
   .news-date {
      flex: 0 0 5.2em;
      font-family: Menlo, Consolas, monospace;
      font-size: 0.85em;
      color: #888;
   }
   .news-tag {
      flex: 0 0 auto;
      min-width: 5.6em;
      text-align: center;
      font-size: 0.72em;
      font-weight: 600;
      padding: 0.1em 0.5em;
      border-radius: 4px;
      text-transform: uppercase;
      letter-spacing: 0.03em;
   }
   .news-text {
      flex: 1 1 auto;
   }
   .news-text a {
      text-decoration: none;
      font-weight: 600;
   }
   .tag-accepted { background: #e6f4ea; color: #1e7e34; }
   .tag-arxiv    { background: #eef2fa; color: #4a6db3; }
   .tag-release  { background: #e3f6f5; color: #0f7b75; }
   .tag-service  { background: #fff4e0; color: #b26a00; }
   .tag-talk     { background: #f3e8fd; color: #7b2cbf; }
   .tag-award    { background: #fff8d6; color: #9a7b00; }
   @media (max-width: 600px) {
      .news-list li { flex-wrap: wrap; gap: 0.4em; }
      .news-text { flex-basis: 100%; }
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

<div class="research-tags">
  <span>Generative AI</span>
  <span>Diffusion Models</span>
  <span>Controllable Image Generation</span>
  <span>Image Editing</span>
  <span>Computational Photography</span>
  <span>Responsible Text-to-Image</span>
</div>

<!-- <a href='https://scholar.google.com/citations?user=90lIt2QAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> -->


<br />
# &#128240; News
<!-- Available tags: tag-accepted, tag-arxiv, tag-release, tag-service, tag-talk, tag-award -->
<ul class="news-list">
  <li><span class="news-date">Sep 2026</span><span class="news-tag tag-accepted">Accepted</span><span class="news-text">&#127881; <a href="https://itsmag11.github.io/AnyBokeh/">AnyBokeh</a> is accepted by <b>NeurIPS 2026</b>.</span></li>
  <li><span class="news-date">Jul 2026</span><span class="news-tag tag-arxiv">arXiv</span><span class="news-text">Our recent work <a href="https://arxiv.org/abs/2606.31959">AnyBokeh</a>, physics-guided any-to-any bokeh editing, is available on arXiv.</span></li>
  <li><span class="news-date">Dec 2025</span><span class="news-tag tag-accepted">Accepted</span><span class="news-text">&#127881; <a href="https://itsmag11.github.io/AITTI/">AITTI</a> is accepted by <b>IJCV</b>.</span></li>
  <li><span class="news-date">Sep 2025</span><span class="news-tag tag-service">Service</span><span class="news-text">Co-organizing the <a href="https://mipi-challenge.org/MIPI2025/">4th MIPI Workshop</a> at <b>ICCV 2025</b>.</span></li>
  <li><span class="news-date">Jun 2025</span><span class="news-tag tag-accepted">Accepted</span><span class="news-text">&#127881; <a href="https://itsmag11.github.io/Omegance/">Omegance</a> is accepted by <b>ICCV 2025</b>.</span></li>
  <li><span class="news-date">Nov 2024</span><span class="news-tag tag-arxiv">arXiv</span><span class="news-text">Our recent work <a href="https://arxiv.org/abs/2411.17769">Omegance</a>, a single parameter for granularity control in diffusion models, is available on arXiv.</span></li>
  <li><span class="news-date">Jun 2024</span><span class="news-tag tag-arxiv">arXiv</span><span class="news-text">Our recent work <a href="http://arxiv.org/abs/2406.12805">AITTI</a>, on inclusive text-to-image generation, is available on arXiv.</span></li>
  <li><span class="news-date">Feb 2024</span><span class="news-tag tag-accepted">Accepted</span><span class="news-text">&#127881; <a href="https://csxmli2016.github.io/projects/w-plus-adapter/">W+ Adapter</a> is accepted by <b>CVPR 2024</b>.</span></li>
  <li><span class="news-date">Aug 2023</span><span class="news-tag tag-accepted">Accepted</span><span class="news-text">&#127881; <a href="https://proceedings.bmvc2023.org/103/">VIRMP</a> is accepted by <b>BMVC 2023</b>.</span></li>
</ul>


<br />
# &#128194; Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS<span class="sep"></span><span class="y">2026</span></div><img src='images/anybokeh.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## AnyBokeh: <span class="nw">Physics-Guided</span> <span class="nw">Any-to-Any</span> Bokeh Editing with Optical Fingerprint&nbsp;Transfer

**Xinyu Hou**, Xiaoming Li, Zongsheng Yue, Chen Change Loy <br />
<span class="pub-venue"><i class="fas fa-landmark"></i><span>Conference on Neural Information Processing Systems (<span class="ab">NeurIPS</span>), <span class="yr">2026</span></span></span>

<div class="paper-links">
  <a class="pbtn" href="https://arxiv.org/abs/2606.31959"><i class="ai ai-arxiv"></i>arXiv</a>
  <a class="pbtn" href="https://github.com/itsmag11/AnyBokeh"><i class="fab fa-github"></i>Code</a>
  <a class="pbtn" href="https://itsmag11.github.io/AnyBokeh/"><i class="fas fa-globe"></i>Project Page</a>
  <a href="https://github.com/itsmag11/AnyBokeh"><img src="https://img.shields.io/github/stars/itsmag11/AnyBokeh?style=social" alt="GitHub stars"></a>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV<span class="sep"></span><span class="y">2025</span></div><img src='images/omegance.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Omegance: A Single Parameter for Various Granularities in <span class="nw">Diffusion-Based</span>&nbsp;Synthesis

**Xinyu Hou**, Zongsheng Yue, Xiaoming Li, Chen Change Loy <br />
<span class="pub-venue"><i class="fas fa-landmark"></i><span>IEEE/CVF International Conference on Computer Vision (<span class="ab">ICCV</span>), <span class="yr">2025</span></span></span>

<div class="paper-links">
  <a class="pbtn" href="https://arxiv.org/abs/2411.17769"><i class="ai ai-arxiv"></i>arXiv</a>
  <a class="pbtn" href="https://openaccess.thecvf.com/content/ICCV2025/papers/Hou_Omegance_A_Single_Parameter_for_Various_Granularities_in_Diffusion-Based_Synthesis_ICCV_2025_paper.pdf"><i class="fas fa-file-pdf"></i>Paper</a>
  <a class="pbtn" href="https://github.com/itsmag11/Omegance"><i class="fab fa-github"></i>Code</a>
  <a class="pbtn" href="https://itsmag11.github.io/Omegance/"><i class="fas fa-globe"></i>Project Page</a>
  <a href="https://github.com/itsmag11/Omegance"><img src="https://img.shields.io/github/stars/itsmag11/Omegance?style=social" alt="GitHub stars"></a>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV<span class="sep"></span><span class="y">2025</span></div><img src='images/aitti.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## AITTI: Learning Adaptive Inclusive Token for <span class="nw">Text-to-Image</span>&nbsp;Generation

**Xinyu Hou**, Xiaoming Li, Chen Change Loy <br />
<span class="pub-venue"><i class="fas fa-book"></i><span>International Journal of Computer Vision (<span class="ab">IJCV</span>), <span class="yr">2025</span></span></span>

<div class="paper-links">
  <a class="pbtn" href="http://arxiv.org/abs/2406.12805"><i class="ai ai-arxiv"></i>arXiv</a>
  <a class="pbtn" href="https://entuedu-my.sharepoint.com/:b:/g/personal/xinyu_hou_staff_main_ntu_edu_sg/EVcLbNo4PYRMkPU3C6av5vcBA3igPLn3eAXG58dpbKwjvw?e=kW8gAK"><i class="fas fa-paperclip"></i>Supplementary</a>
  <a class="pbtn" href="https://github.com/itsmag11/AITTI"><i class="fab fa-github"></i>Code</a>
  <a class="pbtn" href="https://itsmag11.github.io/AITTI/"><i class="fas fa-globe"></i>Project Page</a>
  <a href="https://github.com/itsmag11/AITTI"><img src="https://img.shields.io/github/stars/itsmag11/AITTI?style=social" alt="GitHub stars"></a>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR<span class="sep"></span><span class="y">2024</span></div><img src='images/w+adapter.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## When StyleGAN Meets Stable Diffusion: A W+ Adapter for Personalized Image&nbsp;Generation

Xiaoming Li, **Xinyu Hou**, Chen Change Loy <br />
<span class="pub-venue"><i class="fas fa-landmark"></i><span>IEEE/CVF Conference on Computer Vision and Pattern Recognition (<span class="ab">CVPR</span>), <span class="yr">2024</span></span></span>

<div class="paper-links">
  <a class="pbtn" href="https://arxiv.org/abs/2311.17461"><i class="ai ai-arxiv"></i>arXiv</a>
  <a class="pbtn" href="https://openaccess.thecvf.com/content/CVPR2024/papers/Li_When_StyleGAN_Meets_Stable_Diffusion_a_W_Adapter_for_Personalized_CVPR_2024_paper.pdf"><i class="fas fa-file-pdf"></i>Paper</a>
  <a class="pbtn" href="https://github.com/csxmli2016/w-plus-adapter"><i class="fab fa-github"></i>Code</a>
  <a class="pbtn" href="https://csxmli2016.github.io/projects/w-plus-adapter/"><i class="fas fa-globe"></i>Project Page</a>
  <a href="https://github.com/csxmli2016/w-plus-adapter"><img src="https://img.shields.io/github/stars/csxmli2016/w-plus-adapter?style=social" alt="GitHub stars"></a>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BMVC<span class="sep"></span><span class="y">2023</span></div><img src='images/virmp.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Video Infilling with Rich Motion&nbsp;Prior

**Xinyu Hou**, Liming Jiang, Rui Shao, Chen Change Loy <br />
<span class="pub-venue"><i class="fas fa-landmark"></i><span>British Machine Vision Conference (<span class="ab">BMVC</span>), <span class="yr">2023</span></span></span>

<div class="paper-links">
  <a class="pbtn" href="https://papers.bmvc2023.org/0103.pdf"><i class="fas fa-file-pdf"></i>Paper</a>
  <a class="pbtn" href="https://bmvc2022.mpi-inf.mpg.de/BMVC2023/0103_poster.pdf"><i class="fas fa-image"></i>Poster</a>
  <a class="pbtn" href="https://bmvc2022.mpi-inf.mpg.de/BMVC2023/0103_supp.pdf"><i class="fas fa-paperclip"></i>Supplementary</a>
  <a class="pbtn" href="https://proceedings.bmvc2023.org/103/"><i class="fas fa-globe"></i>Project Page</a>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP<span class="sep"></span><span class="y">2021</span></div><img src='images/wangyi2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## A <span class="nw">Self-Training</span> Approach for <span class="nw">Point-Supervised</span> Object Detection and Counting in&nbsp;Crowds

Yi Wang, Junhui Hou, **Xinyu Hou**, Lap-Pui Chau <br />
<span class="pub-venue"><i class="fas fa-book"></i><span>IEEE Transactions on Image Processing (<span class="ab">TIP</span>), <span class="yr">2021</span></span></span>

<div class="paper-links">
  <a class="pbtn" href="https://ieeexplore.ieee.org/abstract/document/9347744"><i class="fas fa-file-pdf"></i>Paper</a>
  <a class="pbtn" href="https://github.com/WangyiNTU/Point-supervised-crowd-detection"><i class="fab fa-github"></i>Code</a>
  <a href="https://github.com/WangyiNTU/Point-supervised-crowd-detection"><img src="https://img.shields.io/github/stars/WangyiNTU/Point-supervised-crowd-detection?style=social" alt="GitHub stars"></a>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICMEW<span class="sep"></span><span class="y">2021</span></div><img src='images/wangyi1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Dense Point Prediction: A Simple Baseline for Crowd Counting and&nbsp;Localization

Yi Wang, **Xinyu Hou**, Lap-Pui Chau <br />
<span class="pub-venue"><i class="fas fa-landmark"></i><span>IEEE International Conference on Multimedia & Expo Workshops (<span class="ab">ICMEW</span>), <span class="yr">2021</span></span></span>

<div class="paper-links">
  <a class="pbtn" href="https://ieeexplore.ieee.org/abstract/document/9455954"><i class="fas fa-file-pdf"></i>Paper</a>
  <a class="pbtn" href="https://github.com/WangyiNTU/SCALNet"><i class="fab fa-github"></i>Code</a>
  <a href="https://github.com/WangyiNTU/SCALNet"><img src="https://img.shields.io/github/stars/WangyiNTU/SCALNet?style=social" alt="GitHub stars"></a>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AVSS<span class="sep"></span><span class="y">2019</span></div><img src='images/dslcf.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Vehicle Tracking Using Deep SORT with Low Confidence Track&nbsp;Filtering

**Xinyu Hou**, Yi Wang, Lap-Pui Chau <br />
<span class="pub-venue"><i class="fas fa-landmark"></i><span>IEEE International Conference on Advanced Video and <span class="nw">Signal-Based</span> Surveillance (<span class="ab">AVSS</span>), <span class="yr">2019</span></span></span>

<div class="paper-links">
  <a class="pbtn" href="https://ieeexplore.ieee.org/abstract/document/8909903"><i class="fas fa-file-pdf"></i>Paper</a>
</div>
</div>
</div>


<br /> 
# &#127891; Education

<div class="edu-item">
  <div class="edu-logo"><img src="images/logo_ntu.svg" alt="NTU logo"></div>
  <div class="edu-body">
    <div class="edu-head"><span class="edu-title"><span class="edu-school">Nanyang Technological University</span><span class="edu-loc"><i class="fas fa-map-marker-alt"></i>Singapore</span></span><span class="edu-date">Aug 2021 &ndash; Present</span></div>
    <div class="edu-degree">Ph.D. in Computer Science</div>
    <div class="edu-meta">Adviser: <a href="https://www.mmlab-ntu.com/person/ccloy/">Prof. Chen Change Loy</a></div>
  </div>
</div>

<div class="edu-item">
  <div class="edu-logo"><img src="images/logo_ntu.svg" alt="NTU logo"></div>
  <div class="edu-body">
    <div class="edu-head"><span class="edu-title"><span class="edu-school">Nanyang Technological University</span><span class="edu-loc"><i class="fas fa-map-marker-alt"></i>Singapore</span></span><span class="edu-date">Aug 2016 &ndash; Jun 2020</span></div>
    <div class="edu-degree">B.Eng. in Electrical and Electronic Engineering</div>
    <div class="edu-meta">Advisers: <a href="https://www.eie.polyu.edu.hk/~lpchau/">Prof. Lap-Pui Chau</a> and <a href="https://wangyintu.github.io/">Dr. Yi Wang</a></div>
    <ul>
      <li>Degree with Honors (Highest Distinction)</li>
      <li>Dean's List 2019&ndash;2020</li>
      <li>NTU Science and Engineering Scholarship</li>
    </ul>
  </div>
</div>

<div class="edu-item">
  <div class="edu-logo"><img src="images/logo_epfl.svg" alt="EPFL logo"></div>
  <div class="edu-body">
    <div class="edu-head"><span class="edu-title"><span class="edu-school">École Polytechnique Fédérale de Lausanne</span><span class="edu-loc"><i class="fas fa-map-marker-alt"></i>Switzerland</span></span><span class="edu-date">Sep 2018 &ndash; Jan 2019</span></div>
    <div class="edu-degree">Semester Exchange</div>
    <div class="edu-meta">Advisers: <a href="https://www.ireneviola.com/">Dr. Irene Viola</a> and <a href="https://scholar.google.com/citations?user=xFkp8DoAAAAJ&hl=en">Dr. Alexiou Evangelos</a></div>
  </div>
</div>


<br />
# &#127963;&#65039; Academic Services
## Conference and Workshop Committee
- Co-organizer, [4th Mobile Intelligent Photograph and Imaging Workshop (MIPI)](https://mipi-challenge.org/MIPI2025/), ICCV 2025

<span class="small-gap"></span>
## Journal Reviewer
<ul class="service-grid">
  <li><span class="venue">IJCV</span><span class="years">Int. J. Computer Vision</span></li>
  <li><span class="venue">TMM</span><span class="years">IEEE Trans. Multimedia</span></li>
</ul>

<span class="small-gap"></span>
## Conference Reviewer
<ul class="service-grid">
  <li><span class="venue">CVPR</span><span class="years">2025, 2026</span></li>
  <li><span class="venue">ICCV</span><span class="years">2025</span></li>
  <li><span class="venue">ECCV</span><span class="years">2026</span></li>
  <li><span class="venue">ICLR</span><span class="years">2024 &ndash; 2027</span></li>
  <li><span class="venue">NeurIPS</span><span class="years">2024 &ndash; 2026</span></li>
  <li><span class="venue">ICML</span><span class="years">2025</span></li>
  <li><span class="venue">BMVC</span><span class="years">2023 &ndash; 2026</span></li>
  <li><span class="venue">AISTATS</span><span class="years">2025</span></li>
</ul>

<span class="small-gap"></span>
## Teaching Assistant
- NTU AI6126: Advanced Computer Vision
- NTU SC4001: Neural Networks and Deep Learning


<br />
