---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
p { font-size : 16px; }
h1 { font-size : 34px; margin : 0; padding : 0; }
h2 { font-size : 20px; margin : 0; padding : 0; }
h3 { font-size : 18px; margin : 8; padding : 0; }
body { padding : 0; font-family : Arial; font-size : 16px; background-color : #fff; }
.title { width : 650px; margin : 20px auto; }
.container { width : 750px; margin : 20px auto; border-radius: 10px;  background-color : #fff; padding : 20px;  clear:both;}
#bio {
    padding-top : 30px;
}
#me { border : 0 solid black; margin-bottom : 50px; border-radius : 10px; }
#sidebar { margin-left : 25px; border : 0 solid black; float : right; margin-bottom : 0;}
a { text-decoration : none; }
a:hover { text-decoration : underline; }
a, a:visited { color : #0050e7; }
.publogo { width: 100 px; margin-right : 20px; float : left; border : 0;}
.publication { clear : left; padding-bottom : 0px; }
.publication p { height : 100px; padding-top : 5px;}
.publication strong a { color : #0000A0; }
.publication .links { position : relative; top : 15px }
.publication .links a { margin-right : 20px; }
.codelogo { margin-right : 10px; float : left; border : 0;}
.code { clear : left; padding-bottom : 10px; vertical-align :middle;} 
.code .download a { display : block; margin : 0 15px; float : left;}
.code strong a { color : #000; }
.external a { margin : 0 10px; }
.external a.first { margin : 0 10px 0 0; }
	</style>
	<script async="" src="./homepage_files/analytics.js"></script>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Ph.D. candidate supervised by <a href="https://www.mmlab-ntu.com/person/ccloy/">Prof. Chen Change Loy</a> at <a href="https://www.mmlab-ntu.com/"> MMLab@NTU</a>, in the School of Computer Science and Engineering, Nanyang Technological University, Singapore. Prior to my Ph.D. study, I also received my B.Eng. degree with honors (highest distinction) in 2020 from Nanyang Technological University, Singapore. I am broadly interested in computer vision and related topics.

<a href='https://scholar.google.com/citations?user=90lIt2QAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>


<br />
# News
- *2023.08*: &nbsp;Our paper <i>Viedo Infilling with Rich Motion Prior</i> is accepted by BMVC 2023. 


<br />
# Publications 

<div class="container">
		<h2>Publications</h2>
        <br>
        <div class="publication">
            <img src="images/virmp.jpg" class="publogo" width="200 px">
            <p> 
                <strong>
                    Video Infilling with Rich Motion Prior
                </strong>
                <br>
                <br>
                <b>Xinyu Hou</b>, Liming Jiang, Rui Shao, Chen Change Loy
                <br>
                <em>British Machine Vision Conference (BMVC), 2023</em>
                <br>
                <span class="links">
                    <a href="https://arxiv.org/abs/2112.01071">Paper</a>
                </span>
            </p>
        </div>
        <br>
        <br>
        <br>
        <br>
	<div class="publication">
            <img src="images/wangyi2.jpg" class="publogo" width="200 px">
            <p> 
                <strong>
                    A self-training approach for point-supervised object detection and counting in crowds
                </strong>
                <br>
                <br>
                Yi Wang, Junhui Hou, <b>Xinyu Hou</b>, Lap-Pui Chau
                <br>
                <em>IEEE Transactions on Image Processing (TIP), 2021 </em>
                <br>
                <span class="links">
                    <a href="https://ieeexplore.ieee.org/abstract/document/9347744">Paper</a>
                </span>
            </p>
        </div>
        <br>
        <br>
        <br>
        <br>
	<div class="publication">
            <img src="images/wangyi1.jpg" class="publogo" width="200 px">
            <p> 
                <strong>
                    Dense point prediction: A simple baseline for crowd counting and localization
                </strong>
                <br>
                <br>
                Yi Wang, <b>Xinyu Hou</b>, Lap-Pui Chau
                <br>
                <em>IEEE International Conference on Multimedia & Expo Workshops (ICMEW), 2021 </em>
                <br>
                <span class="links">
                    <a href="https://ieeexplore.ieee.org/abstract/document/9455954">Paper</a>
                </span>
            </p>
        </div>
        <br>
        <br>
        <br>
        <br>
        <div class="publication">
            <img src="images/dslcf.jpg" class="publogo" width="200 px">
            <p> 
                <strong>
                    Vehicle Tracking Using Deep SORT with Low Confidence Track Filtering
                </strong>
                <br>
                <br>
                <b>Xinyu Hou</b>, Yi Wang, Lap-Pui Chau
                <br>
                <em>IEEE International Conference on Advanced Video and Signal Based Surveillance (AVSS), 2019 </em>
                <br>
                <span class="links">
                    <a href="https://ieeexplore.ieee.org/abstract/document/8909903">Paper</a>
                </span>
            </p>
        </div>
</div>


<br />
# Educations
- *2021.08 - now*, Ph.D. in Computer Science <br /> Nanyang Technological University
- *2016.08 - 2020.06*, B.Eng. in Electrical and Electronic Engineering  <br /> Nanyang Technological University
<br />
