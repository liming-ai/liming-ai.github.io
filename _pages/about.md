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
I am a second-year PhD student at the University of Central Florida, with [Prof. Chen Chen](https://www.crcv.ucf.edu/chenchen/index.html) as my advisor. I am currently interning at TikTok with [Jie Wu](https://wujie1010.github.io/) and [Rui Wang](https://scholar.google.com/citations?user=nGki_EEAAAAJ&hl=zh-CN) to explore visual reward fine-tuning. Before this, I conducted research on image editing with [Sijie Zhu](https://jeff-zilence.github.io/) and [Longyin Wen](https://scholar.google.com/citations?user=PO9WFl0AAAAJ&hl=zh-CN).


# <font color="#9C2C23" id="publications" > Selected Publications  </font>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/controlnet++.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[ControlNet++: Improving Conditional Controls with Efficient Consistency Feedback.](https://arxiv.org/abs/2404.07987)

**Ming Li**, Taojiannan Yang, Huafeng Kuang, Jie Wu, Zhaoning Wang, Xuefeng Xiao, Chen Chen

**<font color="#9C2C23"> ECCV 2024 &nbsp; </font>**
[**[Website]**](https://liming-ai.github.io/ControlNet_Plus_Plus)
[**[Demo]**](https://huggingface.co/spaces/limingcv/ControlNet-Plus-Plus)
[**[Slides]**](https://docs.google.com/presentation/d/1M86CmxF4E48xWXoO4N5M8JVoYSfB6KCN-7y1K0Z7xkE)
<a href="https://github.com/liming-ai/ControlNet_Plus_Plus">
  <img src="https://img.shields.io/github/stars/liming-ai/ControlNet_Plus_Plus?style=social" alt="GitHub Stars">
</a>

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
[**[Poster]**](https://github.com/liming-ai/AlignDet/blob/page/static/images/Poster_AlignDet.pdf)
<a href="https://github.com/liming-ai/AlignDet">
  <img src="https://img.shields.io/github/stars/liming-ai/AlignDet?style=social" alt="GitHub Stars">
</a>

- We point out that existing detection algorithms are constrained by the data, model, and task discrepancies between pre-training and fine-tuning.
- We propose AlignDet to align these discrepancies, which constructs detection-oriented pre-training by learning classification and regression knowledge.
- AlignDet makes the first attempt to unsupervised pre-train all kinds of detectors and achieves significant improvements across diverse protocols.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/FreeSeg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FreeSeg: Unified, Universal and Open-Vocabulary Image Segmentation.](https://arxiv.org/abs/2303.17225)

Jie Qin<sup>*</sup>, Jie Wu<sup>*#</sup>, Pengxiang Yan, **Ming Li**, Ren Yuxi, Xuefeng Xiao, Yitong Wang, Rui Wang, Shilei Wen, Xin Pan, Xingang Wang<sup>#</sup>.

**<font color="#9C2C23"> CVPR 2023 &nbsp;  </font>**
[**[Website]**](https://freeseg.github.io)
<a href="https://github.com/bytedance/FreeSeg">
  <img src="https://img.shields.io/github/stars/bytedance/FreeSeg?style=social" alt="GitHub Stars">
</a>

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
<span class='show_paper_citations' data='F2h7bGwAAAAJ:W7OEmFMy1HYC'></span>
<a href="https://github.com/bytedance/DiffusionEngine">
  <img src="https://img.shields.io/github/stars/bytedance/DiffusionEngine?style=social" alt="GitHub Stars">
</a>
- We reveal the Diffusion Model is a scalable data engine for object detection.
- We present DiffusionEngine to provide high-quality and diversity detection data, by a pre-trained diffusion model and an effective Detection-Adapter.
- We demonstrate data scaling-up via DiffusionEngine can achieve significant improvements in diverse scenarios, including various detection algorithms, self/semi-supervised pretraining, data/label scarce and cross-domain setting.
</div>
</div>


# <font color="#9C2C23" id="internships" > Internships  </font>
- *2024.05 - Now*, [TikTok, ByteDance](https://www.tiktok.com/), San Jose, USA.
- *2022.01 - 2023.07*, [ByteDance](https://www.bytedance.com/en/), Shenzhen, China.

# <font color="#9C2C23" id="honors" > Honors  </font>
- 🏆 Champion of [CVPR 2023 Long-form Video Understanding and Generation Challenge (Track 3)](https://sites.google.com/view/loveucvpr23/track3).
- 🏆 Champion of [CVPR 2022 AVA Accessibility Vision and Autonomy Challenge](https://accessibility-cv.github.io/).
- ORCGS Doctoral Fellowship, the University of Central Florida. 2023.

# <font color="#9C2C23" id="educations" > Educations  </font>
- *2023.09 - Now*, Ph.D., Computer Science, University of Central Florida.
- *2020.09 - 2023.06*, Master, Computer Science, Xiamen University.
- *2016.09 - 2020.06*, Bachelar, Software Engineering, Hainan University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
