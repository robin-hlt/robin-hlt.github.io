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


# 📝 Publications <a href='https://scholar.google.com/citations?user=niNZb5IAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> {#-publications}

<div style="max-width: 780px; margin: 0 auto;">

  <div style="display:flex; align-items:flex-start; margin-bottom:25px; flex-wrap:wrap;">

    <div style="position:relative; margin-right:15px;
                width:30vw; max-width:165px;
                aspect-ratio:1;
                ">
      
      <img src="../assets/img/ReaSonFramework.png"
           style="
             width:100%;
             height:100%;
             object-fit:cover;
             border-radius:8px;
             box-shadow:0 2px 6px rgba(0,0,0,0.15);
           ">

      <div style="
        position:absolute;
        top:4px;
        left:4px;
        background:#0044CC;
        color:white;
        padding:3px 9px;
        border-radius:5px;
        font-size:11px;
        font-weight:600;
        box-shadow:0px 1px 3px rgba(0,0,0,0.2);
      ">
        AAAI
      </div>

    </div>

    <div style="flex:1; min-width:200px;">
      <b style="font-size:17px;">ReaSon: Reinforced Causal Search with Information Bottleneck for Video Understanding</b><br>
      Yuan Zhou (Supervisor), <b>Litao Hua</b>, Shilong Jin, Wentao Huang, Haoran Duan <br>

      <span style="color:#C62828; font-weight:600;">AAAI'26. CCF-A</span> <br>

      <a href="https://arxiv.org/abs/2511.12530" target="_blank">[Paper]</a>
      <a href="https://github.com/robin-hlt/AAAI26-ReaSon" target="_blank" style="margin-left:8px;">[Code]</a>
    </div>

  </div>

</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arXiv</div>
      <img src='../assets/img/AttentionSurvey.png' alt="survey" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Attention in Diffusion Model: A Survey**](https://arxiv.org/abs/2504.03738)

**Litao Hua**, Fan Liu, Jie Su, Xingyu Miao, Zizhou Ouyang, Zeyu Wang, Runze Hu, Zhenyu Wen, Bing Zhai, Yang Long, Haoran Duan, Yuan Zhou

- A unified taxonomy that categorises attention-related modifications into parts according to the structural components they affect.

 </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arXiv</div>
      <img src='../assets/img/ConsDreamer.png' alt="consdreamer" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**ConsDreamer: Advancing Multi-View Consistency for Zero-Shot Text-to-3D Generation**](https://arxiv.org/abs/2504.02316)

Yuan Zhou, Shilong Jin, **Litao Hua**, Wanjun Lv, Haoran Duan, Jungong Han

- We propose ConsDreamer, a novel framework that mitigates view bias by refining both the conditional and unconditional terms in the score distillation process.

 </div>
</div>
