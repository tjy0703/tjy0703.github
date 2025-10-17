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

# 😎 About Me
I am a **final-year Ph.D. candidate** at the [Intelligent Computing Laboratory](https://thusigsiclab.github.io/thu.github.io/index.html){:target="_blank" rel="noopener"}, SIGS, **Tsinghua University**, advised by Prof. [Xiangyang Ji](https://www.au.tsinghua.edu.cn/info/1080/3178.htm){:target="_blank" rel="noopener"} and Prof. [Xiu Li](https://www.sigs.tsinghua.edu.cn/lx/main.htm){:target="_blank" rel="noopener"}.  
I received both my B.Eng. and M.Eng. from the School of Mechanical Engineering, Northwestern Polytechnical University (NPU).  
Before my Ph.D., I spent one year at Peng Cheng Laboratory as an assistant engineer.

My research interests focus on **computer vision for robotics** in challenging environments — **6D object pose estimation, 3D reconstruction,** and **underwater perception**.

Close collaborators include Dr. [Gu Wang](https://scholar.google.com.sg/citations?user=htu3c7wAAAAJ&hl=zh-CN){:target="_blank" rel="noopener"}, [Bowen Fu](https://fubowen1229.github.io/){:target="_blank" rel="noopener"}, and [Zeyu Chen](https://zeyuuuchen.github.io/){:target="_blank" rel="noopener"}.

<span style="color: #FF5733;">**Currently, I am seeking a Postdoctoral position starting in Spring 2026.**</span>

<a href="https://scholar.google.com/citations?user=gJGdfrYAAAAJ" target="_blank" rel="noopener">Google Scholar</a>

# 🔥 News
- *2025.01*: &nbsp;🎉 One paper presented at an **ICRA 2025 Workshop**.
- *2024.06*: &nbsp;🎉🎉 One paper accepted by **ECCV 2024**.
- *2024.06*: &nbsp;🎉🎉 One paper accepted by **IROS 2024**.
- *2024.01*: &nbsp;🎉🎉 One paper published in **RA-L** and accepted by **ICRA 2024**.
- *2022.10*: &nbsp;🏆 **Winner of BOP Challenge 2022**.
- *2022.04*: &nbsp;🎉 One paper published in **Optics Express**.

# 📝 Publications 

<h2 style="color: #008B8B; font-weight: bold;">Topic 1: 6D Pose Estimation</h2>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L / ICRA 2024</div><img src='images/ROV6D.png' alt="ROV6D" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ROV6D: 6D Pose Estimation Benchmark Dataset for Underwater Remotely Operated Vehicles**

**Jingyi Tang**, Zeyu Chen, Bowen Fu, Wenjie Lu, Shengquan Li, Xiu Li, and Xiangyang Ji.

[**Paper**](https://ieeexplore.ieee.org/document/10313927){:target="_blank" rel="noopener"}
<!-- 如需显示该文被引，把下面这行的 data= 换成该论文在 Scholar 里的 citation_for_view 字符串；不确定就先删掉这行 -->
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
[**DATASET**](https://github.com/THUSIGSICLAB/ROV6D){:target="_blank" rel="noopener"}
</div>
</div>
- **J. Tang**, Z. Chen, B. Fu, W. Lu, S. Li, X. Li, and X. Ji. “ROV6D: 6D Pose Estimation Benchmark Dataset for Underwater Remotely Operated Vehicles.” **IEEE Robotics and Automation Letters (RA-L)**, 2023; presented at **ICRA 2024**.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/FAFA.png' alt="FAFA" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FAFA: Frequency-Aware Flow-Aided Self-Supervision for Underwater Object Pose Estimation**

**Jingyi Tang**, Gu Wang, Zeyu Chen, Shengquan Li, Xiu Li, and Xiangyang Ji.

[**Paper**](https://arxiv.org/abs/2409.16600){:target="_blank" rel="noopener"}
</div>
</div>
- **J. Tang**, G. Wang, Z. Chen, S. Li, X. Li, and X. Ji. “FAFA: Frequency-Aware Flow-Aided Self-Supervision for Underwater Object Pose Estimation.” **ECCV 2024**.



<h2 style="color: #008B8B; font-weight: bold;">Topic 2: 3D Reconstruction</h2>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2024</div><img src='images/UWSDF.png' alt="UW-SDF" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**UW-SDF: Exploiting Hybrid Geometric Priors for Neural SDF Reconstruction from Underwater Multi-view Monocular Images**

Zeyu Chen, **Jingyi Tang**, Gu Wang, Shengquan Li, Xinghui Li, Xiangyang Ji, and Xiu Li.

[**Paper**](https://arxiv.org/abs/2410.08092){:target="_blank" rel="noopener"}
</div>
</div>
- Z. Chen, **J. Tang**, G. Wang, S. Li, X. Li, X. Ji, and X. Li. “UW-SDF: Exploiting Hybrid Geometric Priors for Neural SDF Reconstruction from Underwater Multi-view Monocular Images.” **IROS 2024**.


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA Workshop 2025</div><img src='images/aquasim.jpg' alt="AquaSim" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**AquaSim: A Unity3D-based Framework for Multimodal Underwater Simulation in Computer Vision Research**

Zeyu Chen, **Jingyi Tang**, Kunyi Li, Gu Wang, and Xiu Li.

[**Paper**](https://sites.google.com/view/aq2uasim/call-for-papers){:target="_blank" rel="noopener"}
</div>
</div>
- Z. Chen, **J. Tang**, K. Li, G. Wang, X. Li. “AquaSim: A Unity3D-based Framework for Multimodal Underwater Simulation in Computer Vision Research.” **ICRA Workshop**, 2025.


<h2 style="color: #008B8B; font-weight: bold;">Topic 3: Underwater Tracking & Aiming</h2>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Optics Express 2022</div><img src='images/optx.png' alt="Optics Express Paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Monocular vision aided optical tracking for underwater optical wireless communications**

**Jingyi Tang** (first author), Rui Jiang, Zhen Chen, and Zhengjia Zhu.  
*Optics Express*, **30**(9):14737–14747, **2022-04**.

[**Publisher page**](https://opg.optica.org/abstract.cfm?uri=oe-30-9-14737){:target="_blank" rel="noopener"} &nbsp;|&nbsp; [**DOI: 10.1364/OE.453981**](https://pubmed.ncbi.nlm.nih.gov/35473211/){:target="_blank" rel="noopener"}
</div>
</div>
- **J. Tang**, R. Jiang, Z. Chen, and Z. Zhu. “Monocular vision aided optical tracking for underwater optical wireless communications.” *Optics Express* **30**(9):14737–14747, **Apr 2022**.

# 🏆 Competitions
- *2022.10*: **BOP Challenge 2022** — **The Overall Best Method**, **The Best RGB-only Method**, etc.  
  **Team**: Xingyu Liu, Ruida Zhang, Chenyangguang Zhang, Bowen Fu, Jiwen Tang, Xiquan Liang, **Jingyi Tang**, Xiaotian Cheng, Yukang Zhang, Gu Wang, Xiangyang Ji  
  **Links**: [Code](https://github.com/shanice-l/gdrnpp_bop2022){:target="_blank" rel="noopener"} · [Slides](https://cmp.felk.cvut.cz/s))
