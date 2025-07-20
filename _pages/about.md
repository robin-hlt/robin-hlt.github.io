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

Hello! I’m a first-year M.S. student at **Nanjing University of Information Science and Technology (NUIST)**, under the supervision of Prof. [Yuan Zhou](https://faculty.nuist.edu.cn/zhouyuan/zh_CN/zhym/43346/list/index.htm). 

# 🌟 Research Interests
My research interests include **image and 3D generation**, **multimodal large models**, and **video understanding**.



# 🔥 News
- *2025.04*: &nbsp;🎉🎉 "Attention in diffusion models: A survey" is released on arXiv (under review).

# 📝 Publications 
<a href='https://scholar.google.com/citations?user=niNZb5IAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arXiv</div>
      <img src='images/AttentionSurvey.png' alt="survey" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Attention in Diffusion Model: A Survey**](https://arxiv.org/abs/2504.03738)

**Litao Hua**, Fan Liu, Jie Su, Xingyu Miao, Zizhou Ouyang, Zeyu Wang, Runze Hu, Zhenyu Wen, Bing Zhai, Yang Long, Haoran Duan, Yuan Zhou

- A unified taxonomy that categorises attention-related modifications into parts according to the structural components they affect.

  </div>
</div>

