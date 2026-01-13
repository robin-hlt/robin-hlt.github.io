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

<style>
@media (max-width: 600px) {
  .pub-row {
    flex-direction: column !important;
    align-items: center !important;
  }
  .pub-row img {
    width: 100% !important;
    height: auto !important;
  }
}
</style>


# 👀 About Me
Hello! I’m a second-year M.S. student at **Nanjing University of Information Science and Technology (NUIST)**, under the supervision of Prof. [Yuan Zhou](https://faculty.nuist.edu.cn/zhouyuan/zh_CN/zhym/43346/list/index.htm). I am closely working with [Haoran Duan](https://haoranduan.com/) in Tsinghua University. My research interests include **image and 3D generation**, **multimodal large models**, and **video understanding**.


# 🔥 News
- *2025.11*: &nbsp; 🎉🎉 Two papers are accepted to AAAI 2026
- *2025.04*: &nbsp; "Attention in diffusion models: A survey" is released on arXiv (under review).


# 📝 Publications <a href='https://scholar.google.com/citations?user=niNZb5IAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> {#publications}

<div style="max-width: 780px; margin: 0 auto;">

  <div class="pub-row" style="display:flex; align-items:flex-start; margin-bottom:25px;">

    <div style="position:relative; margin-right:15px;">
      <img src="../assets/img/ReaSonFramework.png"
           style="
             height:130px;
             width:250px;
             border-radius:8px;
             object-fit:cover;
             box-shadow:0 2px 6px rgba(0,0,0,0.15);
           ">

      <div style="
        position:absolute;
        top:6px;
        left:6px;
        background:#0044CC;
        color:white;
        padding:3px 10px;
        border-radius:6px;
        font-size:12px;
        font-weight:600;
        box-shadow:0px 2px 4px rgba(0,0,0,0.2);
      ">
        AAAI
      </div>
    </div>

    <div style="flex:1;">
      <b style="font-size:17px;">ReaSon: Reinforced Causal Search with Information Bottleneck for Video Understanding</b><br>
      Yuan Zhou (Supervisor), <b>Litao Hua</b>, Shilong Jin, Wentao Huang, Haoran Duan <br>

      <span style="color:#C62828; font-weight:600;">AAAI'26. CCF-A</span> <br>

      <a href="https://arxiv.org/abs/2511.12530" target="_blank">[Paper]</a>
      <a href="https://github.com/robin-hlt/AAAI26-ReaSon" target="_blank" style="margin-left:8px;">[Code]</a>
    </div>

  </div>

</div>


<div style="max-width: 780px; margin: 0 auto;">

  <div class="pub-row" style="display:flex; align-items:flex-start; margin-bottom:25px;">

    <div style="position:relative; margin-right:15px;">
      <img src="../assets/img/TDATTN.png"
           style="
             height:130px;
             width:250px;
             border-radius:8px;
             object-fit:cover;
             box-shadow:0 2px 6px rgba(0,0,0,0.15);
           ">

      <div style="
        position:absolute;
        top:6px;
        left:6px;
        background:#0044CC;
        color:white;
        padding:3px 10px;
        border-radius:6px;
        font-size:12px;
        font-weight:600;
        box-shadow:0px 2px 4px rgba(0,0,0,0.2);
      ">
        AAAI
      </div>
    </div>

    <div style="flex:1;">
      <b style="font-size:17px;">
        Debiasing Diffusion Priors via 3D Attention for Consistent Gaussian Splatting
      </b><br>

      Shilong Jin, Haoran Duan, <b>Litao Hua</b>, Wentao Huang, Yuan Zhou <br>

      <span style="color:#C62828; font-weight:600;">AAAI'26. CCF-A</span> <br>

      <a href="https://arxiv.org/abs/2512.07345" target="_blank">[Paper]</a>
      <a href="https://github.com/kimslong/AAAI26-TDAttn" target="_blank" style="margin-left:8px;">[Code]</a>
    </div>

  </div>

</div>


<div style="max-width: 780px; margin: 0 auto;">

  <div class="pub-row" style="display:flex; align-items:flex-start; margin-bottom:25px;">

    <div style="position:relative; margin-right:15px;">
      <img src="../assets/img/ConsDreamer.png"
           style="
             height:130px;
             width:250px;
             border-radius:8px;
             object-fit:cover;
             box-shadow:0 2px 6px rgba(0,0,0,0.15);
           ">

      <div style="
        position:absolute;
        top:6px;
        left:6px;
        background:#444;
        color:white;
        padding:3px 10px;
        border-radius:6px;
        font-size:12px;
        font-weight:600;
        box-shadow:0px 2px 4px rgba(0,0,0,0.2);
      ">
        arXiv
      </div>
    </div>

    <div style="flex:1;">
      <b style="font-size:17px;">ConsDreamer: Advancing Multi-View Consistency for Zero-Shot Text-to-3D Generation</b><br>
      Yuan Zhou, Shilong Jin, <b>Litao Hua</b>, Wanjun Lv, Haoran Duan, Jungong Han <br>
      <a href="https://arxiv.org/abs/2504.02316" target="_blank">[Paper]</a>
      <a href="https://github.com/GAInuist/ConsDreamer" target="_blank" style="margin-left:8px;">[Code]</a>
    </div>

  </div>

</div>


<div style="max-width: 780px; margin: 0 auto;">

  <div class="pub-row" style="display:flex; align-items:flex-start; margin-bottom:25px;">

    <div style="position:relative; margin-right:15px;">
      <img src="../assets/img/AttentionSurvey.png"
           style="
             height:130px;
             width:250px;
             border-radius:8px;
             object-fit:cover;
             box-shadow:0 2px 6px rgba(0,0,0,0.15);
           ">

      <div style="
        position:absolute;
        top:6px;
        left:6px;
        background:#444;
        color:white;
        padding:3px 10px;
        border-radius:6px;
        font-size:12px;
        font-weight:600;
        box-shadow:0px 2px 4px rgba(0,0,0,0.2);
      ">
        arXiv
      </div>
    </div>

    <div style="flex:1;">
      <b style="font-size:17px;">Attention in Diffusion Model: A Survey</b><br>
      <b>Litao Hua</b>, Fan Liu, Jie Su, Xingyu Miao, Zizhou Ouyang, Zeyu Wang, Runze Hu,
      Zhenyu Wen, Bing Zhai, Yang Long, Haoran Duan, Yuan Zhou <br>
      <a href="https://arxiv.org/abs/2504.03738" target="_blank">[Paper]</a>
    </div>

  </div>

</div>


# 💼 Internships

<div style="max-width: 780px; margin: 0 auto;">

  <!-- Shanghai AI Lab -->
  <div class="pub-row" style="display:flex; align-items:flex-start; margin-bottom:25px;">

    <div style="position:relative; margin-right:15px;">
      <img src="../assets/img/ailab-logo.png"
           style="
             height:90px;
             width:250px;
             border-radius:8px;
             object-fit:contain;
             background:#fff;
             padding:8px;
             box-shadow:0 2px 6px rgba(0,0,0,0.12);
           ">
    </div>

    <div style="flex:1;">
      <b style="font-size:17px;">Shanghai AI Laboratory</b><br>
      System Platform Center <br>
      <span style="color:#444; font-weight:500;">
        Engineering Intern · Jan. 2026 – Present
      </span><br>
      <span style="color:#555;">
        Embodied Intelligence · Reinforcement Learning Computing Framework
      </span>
    </div>

  </div>

  <!-- Hikvision -->
  <div class="pub-row" style="display:flex; align-items:flex-start; margin-bottom:25px;">

    <div style="position:relative; margin-right:15px;">
      <img src="../assets/img/Hikvision-logo.png"
           style="
             height:90px;
             width:250px;
             border-radius:8px;
             object-fit:contain;
             background:#fff;
             padding:8px;
             box-shadow:0 2px 6px rgba(0,0,0,0.12);
           ">
    </div>

    <div style="flex:1;">
      <b style="font-size:17px;">Hikvision</b><br>
      <span style="color:#444; font-weight:500;">
        Technical Intern · Feb. 2023 – May 2023
      </span><br>
      <span style="color:#555;">
        Security System Deployment and Maintenance for Government and Universities
      </span>
    </div>

  </div>

</div>

