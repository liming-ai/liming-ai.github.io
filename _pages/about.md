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
I am a first-year Computer Science Ph.D. student at the University of Central Florida, under the supervision of [Dr. Chen Chen](https://www.crcv.ucf.edu/chenchen/index.html). I had the opportunity to serve as an intern with the TikTok team at ByteDance, where I collaborated with [Jie Wu](https://wujie1010.github.io/) from January 2022 to July 2023. Prior to that, I earned my Master’s degree from Xiamen University and my Bachelor’s degree from Hainan University.

My primary research interest is in Data-centric AI, aiming to explore the role and applications of data across a range of AIGC, pre-training, and downstream tasks. Specifically, I am investigating how to facilitate models with more efficient data or annotations and how to construct automated data pipelines for various tasks.


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# <font color="#9C2C23" id="publications" > Publications  </font>
(* indicates equal contribution; # indicates corresponding authorship.)


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/LucidDreaming.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LucidDreaming: Controllable Object-Centric 3D Generation.](https://arxiv.org/abs/2312.00588)

Zhaoning Wang, **Ming Li**, Chen Chen<sup>#</sup>.

**<font color="#9C2C23"> arXiv 2023 &nbsp;  </font>**

<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We propose LucidDreaming, a plug-and-play framework to achieve controllable object-centric 3D generation with Large Language Models.
- We introduces clipped ray sampling and object-centric density bias initialization to generate multiple discrete 3D objects within single scene.
- LucidDreaming offers a standard in the dataset, evaluation metrics, and clear strategies for the development of controllable 3D generation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/AlignDet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[AlignDet: Aligning Pre-training and Fine-tuning in Object Detection.](https://arxiv.org/abs/2307.11077)

**Ming Li<sup>*</sup>**, Jie Wu<sup>*#</sup>, Xionghui Wang, Chen Chen<sup>#</sup>, Jie Qin, Xuefeng Xiao, Rui Wang, Min Zheng, Xin Pan.

**<font color="#9C2C23">  ICCV 2023 &nbsp; </font>**
[**[Page]**](https://liming-ai.github.io/AlignDet)
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
[**[Page]**](https://freeseg.github.io)
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
[**[Page]**](https://mettyz.github.io/DiffusionEngine)
[**[Code]**](https://github.com/bytedance/DiffusionEngine)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We reveal the Diffusion Model is a scalable data engine for object detection.
- We present DiffusionEngine to provide high-quality and diversity detection data, by a pre-trained diffusion model and an effective Detection-Adapter.
- We demonstrate data scaling-up via DiffusionEngine can achieve significant improvements in diverse scenarios, including various detection algorithms, self/semi-supervised pretraining, data/label scarce and cross-domain setting.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/DLIP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DLIP: Distilling Language-Image Pre-training.](https://arxiv.org/abs/2308.12956)

Huafeng Kuang, Jie Wu, Xiawu Zheng, **Ming Li**, Xuefeng Xiao, Rui Wang, Min Zheng, Rongrong Ji<sup>#</sup>.

**<font color="#9C2C23"> arXiv 2023 &nbsp;  </font>**

<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We present  simple yet efficient Distilling Language Image Pre-training (DLIP) framework to distil a light Vision-Language Pre-training model.
- We dissect the distillation from multiple aspects, such as the architecture characteristics of modules and the information transfer of modalities.
- DLIP succeeds in retaining more than 95% of the performance with 22.4% parameters and 24.8% FLOPs and accelerates inference speed by $2.7\times$.
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


- [First Place Solution to the CVPR’2023 AQTC Challenge: A Function-Interaction Centric Approach with Spatiotemporal Visual-Language Alignment.](https://arxiv.org/abs/2306.13380) \\
Tom Tongjia Chen, Hongshan Yu, Zhengeng Yang, **Ming Li**, Zechuan Li, Jingwen Wang, Wei Miao, Wei Sun, Chen Chen. \\
[CVPR 2023 Workshop](https://sites.google.com/view/loveucvpr23/track3?authuser=0)  &nbsp; [[Challenge]](https://codalab.lisn.upsaclay.fr/competitions/4642#results)  &nbsp; [[Code]](https://github.com/tomchen-ctj/CVPR23-LOVEU-AQTC)

- [First Place Solution to the CVPR’2022 AVA Challenge: Parallel Pre-trained Transformers for Synthetic Data-based Instance Segmentation.](https://arxiv.org/abs/2206.10845) \\
**Ming Li**<sup>*</sup>, Jie Wu<sup>*#</sup>, Jinhang Cai, Jie Qin, Yuxi Ren, Xuefeng Xiao, Min Zheng, Rui Wang, Xin Pan. \\
[CVPR 2022 Workshop](https://accessibility-cv.github.io/) &nbsp; [[Challenge]](https://eval.ai/web/challenges/challenge-page/1690/leaderboard/4046)


# <font color="#9C2C23" id="internships" > Internships  </font>
- *2022.01 - 2023.07*, [TikTok, ByteDance](https://www.tiktok.com/), China.

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
