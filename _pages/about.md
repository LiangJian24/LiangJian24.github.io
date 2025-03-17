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
  dl {
    margin-top: 1px;
    margin-bottom: 5px; /* 调整这个值以获得合适的间距 */
    clear: both;
  }

  img {
    display: block;
    margin: 0px 10px 10px 0px; /* 图片居中 上右下左*/ 
    max-width: 100%; /* 限制图片最大宽度 */
  }

  hr {
    border: 1px solid #ebebeb; /* 调整分隔线的颜色和样式 */
    /* margin: 10px;  */
    clear: both; 
  }


  dl dd {
  color: #; 
  margin-top: 1px; 
  margin-bottom: 1px;
}

  dl dd strong {
  font-weight: bold;
  }


  .publication-title {
    font-weight: bold;
  }

  .image-container {
    display: flex;
    justify-content: center;
    gap: 10px; /* 控制图片间距 */
    margin: 20px 0;
  }

  .image-container img {
    max-width: 150px; /* 控制最大宽度 */
    height: auto;
    margin: 0; /* 移除原来的 margin */
  }

  .co-first {
    color: #B02418;
  }
  
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


# 🧐 About Me

Hi there! My name is Jian Liang（梁健）

My research focuses on **Mutimodal Large Language Models and Parameter-Efficient Fine-Tuning**.




# 🔥 News
<div style="max-height: 200px; overflow-y: auto;">
<ul>
  <li><em>2025.02:</em> 🚀 LoRASculpt was accepted to <strong>CVPR 2025</strong>.</li>
</ul>
</div>

# 📝 Publications 

&dagger;: equal contribution, * : corresponding author

<hr>

<dl>
  <dt><img align="left" width="400" src="../images/paper/LoRASculpt.png" alt="LVLM_Safety_Survey"></dt>
  <dd><a href="" class="publication-title">LoRASculpt: Sculpting LoRA for Harmonizing General and Specialized Knowledge in Multimodal Large Language Models</a></dd>
  <dd><strong>Jian Liang</strong>, Wenke Huang, Guancheng Wan, Qu yang, Mang Ye*</dd>
  <dd>Conference on Computer Vision and Pattern Recognition **(CVPR)**, 2025</dd>
</dl>

<hr>

## ⌛️ In Submission & Preprint
<hr>

<dl>
  <dt><img align="left" width="400" src="../images/paper/MLLMFT_Survey.png" alt="Client As Navigator"></dt>
  <dd><a href="https://arxiv.org/abs/2503.04543" class="publication-title">Keeping Yourself is Important in Downstream Tuning Multimodal Large Language Model</a></dd>
  <dd>Wenke Huang&dagger;, <strong>Jian Liang&dagger;</strong> <span class="co-first">(co-first)</span>, Xianda Guo, Yiyang Fang, Guancheng Wan, Xuankun Rong, Chi Wen, Zekun Shi, Qingyun Li, Didi Zhu, Yanbiao Ma, Ke Liang, Bin Yang, He Li, Jiawei Shao, Mang Ye*, Bo Du*</dd>
  <dd>Under Review</dd>
</dl>

<hr>

<dl>
  <dt><img align="left" width="400" src="../images/paper/SPIDER.png" alt="MLLM_Finetune_Survey"></dt>
  <dd><a href="https://arxiv.org/abs/2411.10928" class="publication-title">Learn from Downstream and Be Yourself in Multimodal Large Language Model Fine-Tuning</a></dd>

  <dd>Wenke Huang, <strong>Jian Liang</strong>, Zekun Shi, Didi Zhu, Guancheng Wan, He Li, Bo Du, Dacheng Tao, Mang Ye*</dd>
  <dd>Under Review</dd>
</dl>

<hr>


# 🎖 Honors and Awards


# 📖 Educations

