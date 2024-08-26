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

# <font color="#9C2C23" id="about-me" > About Me </font>
I am a second-year PhD student in Computer Science at the University of Central Florida, with [Dr. Chen Chen](https://www.crcv.ucf.edu/chenchen/index.html) as my advisor. I am currently interning at TikTok with [Sijie Zhu](https://jeff-zilence.github.io/). Prior to this, I worked as an intern at ByteDance with [Jie Wu](https://wujie1010.github.io/).

My primary research interest is in Data-centric AI, investigating how to facilitate models with more efficient data or annotations and how to construct automated data pipelines for various tasks. Recently, I am working on image/video generation and editing.

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# <font color="#9C2C23" id="publications" > Publications  </font>
(* indicates equal contribution; # indicates corresponding authorship.)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/controlnet++.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[ControlNet++: Improving Conditional Controls with Efficient Consistency Feedback.](https://arxiv.org/abs/2404.07987)

**Ming Li**, Taojiannan Yang, Huafeng Kuang, Jie Wu, Zhaoning Wang, Xuefeng Xiao, Chen Chen

**<font color="#9C2C23">  ECCV 2024 &nbsp; </font>**
[**[Website]**](https://liming-ai.github.io/ControlNet_Plus_Plus)
[**[Code]**](https://github.com/liming-ai/ControlNet_Plus_Plus)
[**[Demo]**](https://huggingface.co/spaces/limingcv/ControlNet-Plus-Plus)

<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Existing efforts in controllable generation still perform poorly in controllability, with generated images deviating from input conditions.
- We show that pre-trained discriminative models can serve as powerful visual reward models to improve the controllability in a cycle-consistency manner.
- We disrupt the consistency between input images and conditions, and enable the single-step denoising for efficient reward fine-tuning.
- We provide a unified and public evaluation of controllability and demonstrate that ControlNet++ comprehensively outperforms existing methods.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/AlignDet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[AlignDet: Aligning Pre-training and Fine-tuning in Object Detection.](https://arxiv.org/abs/2307.11077)

**Ming Li<sup>*</sup>**, Jie Wu<sup>*#</sup>, Xionghui Wang, Chen Chen<sup>#</sup>, Jie Qin, Xuefeng Xiao, Rui Wang, Min Zheng, Xin Pan.

**<font color="#9C2C23">  ICCV 2023 &nbsp; </font>**
[**[Website]**](https://liming-ai.github.io/AlignDet)
[**[Code]**](https://github.com/liming-ai/AlignDet)
[**[Poster]**](https://github.com/liming-ai/AlignDet/blob/page/static/images/Poster_AlignDet.pdf)

<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We point out that existing detection algorithms are constrained by the data, model, and task discrepancies between pre-training and fine-tuning.
- We propose AlignDet to align these discrepancies, which constructs detection-oriented pre-training by learning classification and regression knowledge.
- AlignDet makes the first attempt to fully pre-train all kinds of detectors using a completely unsupervised paradigm, by integrating pre-trained backbones.
- AlignDet can achieve significant improvements across diverse protocols, such as detection algorithm, model backbone, data setting, and training schedule.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/FreeSeg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FreeSeg: Unified, Universal and Open-Vocabulary Image Segmentation.](https://arxiv.org/abs/2303.17225)

Jie Qin<sup>*</sup>, Jie Wu<sup>*#</sup>, Pengxiang Yan, **Ming Li**, Ren Yuxi, Xuefeng Xiao, Yitong Wang, Rui Wang, Shilei Wen, Xin Pan, Xingang Wang<sup>#</sup>.

**<font color="#9C2C23"> CVPR 2023 &nbsp;  </font>**
[**[Website]**](https://freeseg.github.io)
[**[Code]**](https://github.com/bytedance/FreeSeg)

<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We propose FreeSeg, a generic framework to accomplish Unified, Universal and Open-Vocabulary Image Segmentation.
- FreeSeg optimizes an all-in-one network via one-shot training and adaptive prompt learning, making a single model work for diverse segmentation tasks.
- FreeSeg establishes SOTA results on three Open-Vocabulary segmentation tasks, and outperforms the best task-specific architectures by a large margin.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/DED.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DiffusionEngine: Diffusion Model is Scalable Data Engine for Object Detection.](https://arxiv.org/abs/2309.03893)

Manlin Zhang<sup>*</sup>, Jie Wu<sup>*#</sup>, Yuxi Ren<sup>*</sup>, **Ming Li**, Jie Qin, Xuefeng Xiao, Wei Liu, Rui Wang, Min Zheng, Andy J. Ma<sup>#</sup>.

**<font color="#9C2C23"> arXiv 2023 &nbsp;  </font>**
[**[Website]**](https://mettyz.github.io/DiffusionEngine)
[**[Code]**](https://github.com/bytedance/DiffusionEngine)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We reveal the Diffusion Model is a scalable data engine for object detection.
- We present DiffusionEngine to provide high-quality and diversity detection data, by a pre-trained diffusion model and an effective Detection-Adapter.
- We demonstrate data scaling-up via DiffusionEngine can achieve significant improvements in diverse scenarios, including various detection algorithms, self/semi-supervised pretraining, data/label scarce and cross-domain setting.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/MGD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-granularity Distillation Scheme Towards Lightweight Semi-supervised Semantic Segmentation.](https://arxiv.org/abs/2208.10169)


Jie Qin<sup>*</sup>, Jie Wu<sup>*#</sup>, **Ming Li**, Xuefeng Xiao, Min Zheng, Xingang Wang<sup>#</sup>.

**<font color="#9C2C23"> ECCV 2022 &nbsp;  </font>**
[**[Code]**](https://github.com/JayQine/MGD-SSSS)

<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We offer the first attempt to obtain the lightweight model for semi-supervised semantic segmentation.
- We propose a multi-granularity distillation (MGD) to distill task-specific concepts from two complementary teacher models into a student one.
- The labeled-unlabeled data cooperative distillation, and the hierarchical loss paradigm facilitates the lightweight model with less annotations.
- MGD can outperform the competitive approaches by a large margin under diverse partition protocols with signigicant FLOPs reduction.
</div>
</div>

- [Frame Interpolation with Consecutive Brownian Bridge Diffusion.](https://arxiv.org/abs/2405.05953) \\
Zonglin Lyu, **Ming Li**, Jianbo Jiao, Chen Chen. \\
ACM MM 2024 &nbsp; [[Website]](https://zonglinl.github.io/videointerp/) &nbsp; [[Code]](https://github.com/ZonglinL/ConsecutiveBrownianBridge)

- [IL-NeRF: Incremental Learning for Neural Radiance Fields with Camera Pose Alignment.](https://arxiv.org/abs/2312.05748) \\
Letian Zhang, **Ming Li**, Chen Chen, Jie Xu. \\
arXiv 2024 &nbsp; [[Website]](https://ilnerf.github.io/)

- [LucidDreaming: Controllable Object-Centric 3D Generation.](https://arxiv.org/abs/2312.00588) \\
Zhaoning Wang, **Ming Li**, Chen Chen. \\
ECCV 2024 Workshop: Computer Vision For Videogames (CV2) &nbsp; [[Website]](https://www.zhaoningwang.com/LucidDreaming)

- [DLIP: Distilling Language-Image Pre-training.](https://arxiv.org/abs/2308.12956) \\
Huafeng Kuang, Jie Wu, Xiawu Zheng, **Ming Li**, Xuefeng Xiao, Rui Wang, Min Zheng, Rongrong Ji. \\
arXiv 2023 &nbsp;

- [First Place Solution to the CVPR’2023 AQTC Challenge: A Function-Interaction Centric Approach with Spatiotemporal Visual-Language Alignment.](https://arxiv.org/abs/2306.13380) \\
Tom Tongjia Chen, Hongshan Yu, Zhengeng Yang, **Ming Li**, Zechuan Li, Jingwen Wang, Wei Miao, Wei Sun, Chen Chen. \\
[CVPR 2023 Workshop](https://sites.google.com/view/loveucvpr23/track3?authuser=0)  &nbsp; [[Challenge]](https://codalab.lisn.upsaclay.fr/competitions/4642#results)  &nbsp; [[Code]](https://github.com/tomchen-ctj/CVPR23-LOVEU-AQTC)

- [First Place Solution to the CVPR’2022 AVA Challenge: Parallel Pre-trained Transformers for Synthetic Data-based Instance Segmentation.](https://arxiv.org/abs/2206.10845) \\
**Ming Li**<sup>*</sup>, Jie Wu<sup>*#</sup>, Jinhang Cai, Jie Qin, Yuxi Ren, Xuefeng Xiao, Min Zheng, Rui Wang, Xin Pan. \\
[CVPR 2022 Workshop](https://accessibility-cv.github.io/) &nbsp; [[Challenge]](https://eval.ai/web/challenges/challenge-page/1690/leaderboard/4046)


# <font color="#9C2C23" id="internships" > Internships  </font>
- *2024.05 - Now*, [TikTok, ByteDance](https://www.tiktok.com/), San Jose, USA.
- *2022.01 - 2023.07*, [ByteDance](https://www.bytedance.com/en/), Shenzhen, China.

# <font color="#9C2C23" id="honors" > Honors  </font>
- Champion of [CVPR 2023 Long-form Video Understanding and Generation Challenge (Track 3)](https://sites.google.com/view/loveucvpr23/track3).
- ORCGS Doctoral Fellowship, the University of Central Florida. 2023.
- Champion of [CVPR 2022 AVA Accessibility Vision and Autonomy Challenge](https://accessibility-cv.github.io/).
- Excellent Graduation Thesis of Hainan University. 2020.
- China National Inspirational Scholarship. 2017 and 2018.

# <font color="#9C2C23" id="educations" > Educations  </font>
- *2023.09 - Now*, Ph.D., Computer Science, University of Central Florida.
- *2020.09 - 2023.06*, Master, Computer Science, Xiamen University.
- *2016.09 - 2020.06*, Bachelar, Software Engineering, Hainan University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
