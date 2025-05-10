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

I am currently a third-year Ph.D. candidate at Peking University, advised by Professor [Yibo Lin](http://yibolin.com/). Previously, I obtained my Master's degree in 2022 from the University of Chinese Academy of Sciences, ShenZhen Institute of Advanced Technology, MMLab, where I was co-advised by Professors [Shifeng Chen](https://people.ucas.ac.cn/~sfchen?language=en), [Chao Dong](https://xpixel.group/2010/01/20/chaodong.html), and [Yu Qiao](https://mmlab.siat.ac.cn/yuqiao). 

My currently research insterests lie in AI-driven methodologies for physical design automation.


# 🔥 News
- *2025.05*: &nbsp; Our paper *DeepLayout* is accepted by ICML 2025. 

- *2024.11*: &nbsp; Our paper *PDNNet* is accepted by TCAD. 
- *2024.08*: &nbsp; Our paper *Large Circuit Model* is accepted by Science China.
- *2024.02*: &nbsp; Our paper *CircuitNet2.0* is accepted by ICLR 2024. 
- *2024.01*: &nbsp; Our paper *PowPrediCT* is accepted by ICLR 2024.

- *2023.08*: &nbsp; Our paper *Accelerating Routability and Timing Optimization with Open-Source AI4EDA Dataset CircuitNet and Heterogeneous Platforms* is accepted by ICCAD 2023. 
- *2023.05*: &nbsp; Our paper *CircuitNet* is accepted by TCAD. 
- *2023.03*: &nbsp; Our paper *HybridNet* is accepted by ISEDA 2023. 
- *2023.01*: &nbsp; Our paper *Rethinking 3D cost aggregation in stereo matchin* is accepted by PRL. 

- *2022.11* &nbsp; Winner in EDAthon 2022 programming contest. 
- *2022.10*: &nbsp; Our paper *CircuitNet* is accepted by Science China. 
- *2022.09* &nbsp; Joined CECA@PKU as research assiatant. Started working on AI4EDA. 
- *2022.06* &nbsp; Graduated with outstanding student award of UCAS. 

- *2021.07*: &nbsp; Our paper *DSANet* is accepted by ACMMM 2021. 
- *2021.05*: &nbsp; Our paper *Good Practices and a Strong Baseline for Traffic Anomaly Detection* is accepted by CVPRW 2021. 
- *2021.04*: &nbsp; Winner in the Traffic Anomaly Detection Track of the CVPR 2021 AI CITY CHALLENGE.

- *2019.09* &nbsp; Joined MMLab@SIAT as research assiatant. Started working on Computer Vision. 
- *2019.06* &nbsp; Graduated with provincial outstanding graduate honor. 


# 📝 Publications 

<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">ICML 2025</div><img src='images/DeepLayout-ICML2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[DeepLayout: Learning Neural Representations of Circuit Placement Layout](https://endeavourzyx.github.io/)

**Yuxiang Zhao**, Zhuomin Chai, Xun Jiang, Qiang Xu, Runsheng Wang, Yibo Lin
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">TCAD</div><img src='images/PDNNet-TCAD2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[PDNNet: PDN-Aware GNN-CNN Heterogeneous Network for Dynamic IR Drop Prediction](https://arxiv.org/abs/2403.18569)

**Yuxiang Zhao**, Zhuomin Chai, Xun Jiang, Yibo Lin, Runsheng Wang, Ru Huang
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">Science China</div><img src='images/LCM-ScienceChina.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[The Dawn of AI-Native EDA: Opportunities and
Challenges of Large Circuit Models](https://arxiv.org/abs/2403.07257v2)

Many co-authors
</div>
</div>



<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">ICLR 2024</div><img src='images/Circuitnet2.0-ICLR2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[CircuitNet 2.0: An Advanced Dataset for Promoting Machine Learning Innovations in Realistic Chip Design Environmen](https://openreview.net/pdf?id=nMFSUjxMIl)

Xun Jiang, Zhuomin Chai, **Yuxiang Zhao**, Yibo Lin, Runsheng Wang, and Ru Huang
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">DAC 2024</div><img src='images/PowPrediCT-DAC2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[PowPrediCT: Cross-Stage Power Prediction with Circuit-Transformation-Aware Learning](https://dl.acm.org/doi/abs/10.1145/3649329.3657349)

Yufan Du, Zizheng Guo, Xun Jiang, Zhuomin Chai, **Yuxiang Zhao**, Yibo Lin, Runsheng Wang, Ru Huang
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">ICCAD 2023</div><img src='images/INVITED-ICCAD2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Invited Paper: Accelerating Routability and Timing Optimization with Open-Source AI4EDA Dataset CircuitNet and
Heterogeneous Platforms](https://ieeexplore.ieee.org/abstract/document/10323938)

Xun Jiang, Zizheng Guo, Zhuomin Chai, **Yuxiang Zhao**, Yibo Lin, Runsheng Wang, Ru Huang
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">TCAD</div><img src='images/Circuitnet1.0-TCAD2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[CircuitNet: An Open-
Source Dataset for Machine Learning in VLSI CAD Applications With Improved Domain-Specific Evaluation
Metric and Learning Strategies](https://ieeexplore.ieee.org/document/10158384/)

Zhuomin Chai, **Yuxiang Zhao**, Wei Liu, Yibo Lin, Runsheng Wang, Ru Huang
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">Pattern Recognition Letters</div><img src='images/3D-PRL2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Rethinking 3D cost aggregation in stereo matching](https://www.sciencedirect.com/science/article/abs/pii/S0167865523000417)

Wanshui Gan, Wenhao Wu, Shifeng Chen, **Yuxiang Zhao**, and Pak Kin Wong
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">Science China</div><img src='images/Circuitnet1.0-ScienceChina.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[CircuitNet: An Open-
Source Dataset for Machine Learning Applications in Electronic Design Automation (EDA)](https://arxiv.org/abs/2208.01040)

Zhuomin Chai, **Yuxiang Zhao**, Yibo Lin, Wei Liu, Runsheng Wang, Ru Huang
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">ISEDA 2023</div><img src='images/HybridNet-ISEDA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[HybridNet: Dual-Branch Fusion of
Geometrical and Topological Views for VLSI Congestion Prediction (Extended Abstract)](https://arxiv.org/abs/2305.05374)

**Yuxiang Zhao**, Zhuomin Chai, Yibo Lin, Runsheng Wang,  Ru Huang
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">ACMMM 2021</div><img src='images/DSANet-ACMM2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[DSANet: Dynamic Segment Aggregation Network for Video-Level Repre-
sentation Learning](https://arxiv.org/abs/2105.12085)

Wenhao Wu*, **Yuxiang Zhao***, Yanwu Xu, Xiao Tan, Dongliang He, Zhikang Zou, Jin Ye, Yingying Li, Mingde
Yao, Zichao Dong, Yifeng Shi
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">CVPRW 2021</div><img src='images/AD-CVPRW2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Good Practices and a Strong
Baseline for Traffic Anomaly Detection](https://arxiv.org/abs/2105.03827)

**Yuxiang Zhao***, Wenhao Wu*, Yue He, Yingying Li, Xiao Tan, Shifeng Chen
</div>
</div>




# 🎖 Honors and Awards
- *2022.11* &nbsp; Champion of EDAthon 2022 programming contest. 
- *2022.06* &nbsp; Outstanding Student Award of UCAS. 
- *2022.06* &nbsp; Outstanding Students of ShenZhen Institute of Advanced Technology. 

- *2021.06* &nbsp; Champion of CVPR NVIDIA AI City Challenge Track4, Traffic Anomaly Detection.
- *2021.04* &nbsp; Outstanding Award of "Traffic & 3D Intelligent Perception Project " in Baidu.

- *2019.06* &nbsp; Outstanding Graduate Student (Shandong Province).

- *2018.10* &nbsp; National Scholarship.
- *2018.10* &nbsp; "My Favorite Project" of the 11th National College Students Innovation and Entrepreneurship Annual
Conference (First Prize).
- *2018.09* &nbsp; National Electronic Design Competition (Second Prize of Shandong Province).
- *2018.09* &nbsp; Innovation Scholarship.

- *2017.12* &nbsp; Science and Technology Innovation Competition (First Prize of Shandong Province).
- *2017.11* &nbsp; The Start of Innovation and Entrepreneur.
- *2017.11* &nbsp; "My Favorite Project" of the 10th National College Students Innovation and
Entrepreneurship Annual Conference (First Prize).
- *2017.11* &nbsp; "Best Creative Project" of the 10th National College Students Innovation and
Entrepreneurship Annual Conference (First Prize).
- *2017.10* &nbsp; National Electronic Design Competition (First Prize of Shandong Province).
- *2017.10* &nbsp; Robot Competition (Second Prize of Shandong Province).
- *2017.09* &nbsp; Physics Innovation Competition (First Prize of Shandong Province).
- *2017.09* &nbsp; Innovation Scholarship.
- *2017.05* &nbsp; Challenge Cup Innovation Contest (Second Prize of Shandong Province).

- *2016.12* &nbsp; Science and Technology Innovation Competition (Third Prize of Shandong Province).
- *2016.10* &nbsp; Innovation Scholarship.


# 📖 Educations
- *2022.09 - now*,  &nbsp; Peking Univiersity, China, Ph.D candidate of Ingergreted Circuit. 
- *2019.09 - 2022.06*, &nbsp; University of Chinese Academy of Sciences, China, Master of control engerning. 
- *2019.09 - 2022.06*, &nbsp; Shenzhen Institute of Advanced Technology, Chinese Academy of Science, China, Research Assistant. 
- *2015.09 - 2019.06*, &nbsp; China University of Petroleum, China, Bachelor of Optoelectronic Information Science and Engineering. 


# 💻 Internships
- *2024.06 - Now*, [National Center of Technology Innovation for EDA](https://www.nctieda.com/), Nanjing, China.
- *2023.07 - 2023.09*, [Institue of Electronic Design Automation, Peking University](http://pkueda.org.cn/), Wuxi, China.
- *2021.08 - 2022.05*, [Tencent AI Lab](https://ailab.tencent.com/), Shenzhen, China.
- *2020.10 - 2021.06*, [Baidu Visual Technology Department](https://vis.baidu.com/), Shenzhen, China.
