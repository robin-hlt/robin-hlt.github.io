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

# 👀 About Me
Hello! I’m a second-year M.S. student at **Nanjing University of Information Science and Technology (NUIST)**, under the supervision of Prof. [Yuan Zhou](https://faculty.nuist.edu.cn/zhouyuan/zh_CN/zhym/43346/list/index.htm). I am closely working with [Haoran Duan](https://haoranduan.com/) in Tsinghua University. My research interests include **image and 3D generation**, **multimodal large models**, and **video understanding**.


# 🔥 News
- *2025.04*: &nbsp; 🎉🎉 Two papers are accepted to AAAI 2026
- *2025.04*: &nbsp; "Attention in diffusion models: A survey" is released on arXiv (under review).


# 📝 Publications <a href='https://scholar.google.com/citations?user=niNZb5IAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> {#publications}

<div class="pub-card">

  <div class="pub-img-wrapper">
    <img src="../assets/img/ReaSonFramework.png">
    <div class="badge badge-aaai">AAAI</div>
  </div>

  <div class="pub-text">
    <b style="font-size:17px;">ReaSon: Reinforced Causal Search with Information Bottleneck for Video Understanding</b><br>
    Yuan Zhou (Supervisor), <b>Litao Hua</b>, Shilong Jin, Wentao Huang, Haoran Duan <br>
    <span style="color:#C62828; font-weight:600;">AAAI'26. CCF-A</span> <br>

    <a href="https://arxiv.org/abs/2511.12530" target="_blank">[Paper]</a>
    <a href="https://github.com/robin-hlt/AAAI26-ReaSon" target="_blank" style="margin-left:8px;">[Code]</a>
  </div>

</div>


<div class="pub-card">

  <div class="pub-img-wrapper">
    <img src="../assets/img/AttentionSurvey.png">
    <div class="badge badge-arxiv">arXiv</div>
  </div>

  <div class="pub-text">
    <b style="font-size:17px;">Attention in Diffusion Model: A Survey</b><br>
    <b>Litao Hua</b>, Fan Liu, Jie Su, Xingyu Miao, Zizhou Ouyang, Zeyu Wang, Runze Hu, Zhenyu Wen, Bing Zhai, Yang Long, Haoran Duan, Yuan Zhou <br>
  </div>

</div>


<div class="pub-card">

  <div class="pub-img-wrapper">
    <img src="../assets/img/ConsDreamer.png">
    <div class="badge badge-arxiv">arXiv</div>
  </div>

  <div class="pub-text">
    <b style="font-size:17px;">ConsDreamer: Advancing Multi-View Consistency for Zero-Shot Text-to-3D Generation</b><br>
    Yuan Zhou, Shilong Jin, <b>Litao Hua</b>, Wanjun Lv, Haoran Duan, Jungong Han <br>
  </div>

</div>
