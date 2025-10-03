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

# <font id="about-me" > <font color="#000000"> About Me </font>
I am a second-year PhD student at the University of Central Florida, with [Prof. Chen Chen](https://www.crcv.ucf.edu/chenchen/index.html) as my advisor. I am currently interning at TikTok with [Jie Wu](https://wujie1010.github.io/) and [Rui Wang](https://scholar.google.com/citations?user=nGki_EEAAAAJ&hl=zh-CN) to explore visual and multimodal RL. Before this, I conducted research on image editing with [Sijie Zhu](https://jeff-zilence.github.io/) and [Longyin Wen](https://scholar.google.com/citations?user=PO9WFl0AAAAJ&hl=zh-CN).


# <font id="publications" ><font color="#000000"> Publications  </font>

<!-- Self-Forcing++ -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ByteDance Seed Technical Report] &nbsp; </font></strong><a href="https://arxiv.org/abs/2510.02283">Self-Forcing++: Towards Minute-Scale High-Quality Video Generation</a>
    <a href="https://github.com/justincui03/Self-Forcing-Plus-Plus"><img src="https://img.shields.io/github/stars/justincui03/Self-Forcing-Plus-Plus?style=social" alt="GitHub Stars" /></a>
  </p>
  <p>
    Jie Wu, Yu Gao, Zilyu Ye, <strong>Ming Li</strong>, Liang Li, Hanzhong Guo, Jie Liu, Zeyue Xue, Xiaoxia Hou, Wei Liu, Yan Zeng, Weilin Huang
  </p>
</div>

<!-- RewardDance -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ByteDance Seed Technical Report] &nbsp; </font></strong><a href="https://arxiv.org/abs/2509.08826">RewardDance: Reward Scaling in Visual Generation</a>
  </p>
  <p>
    Jie Wu, Yu Gao, Zilyu Ye, <strong>Ming Li</strong>, Liang Li, Hanzhong Guo, Jie Liu, Zeyue Xue, Xiaoxia Hou, Wei Liu, Yan Zeng, Weilin Huang
  </p>
</div>

<!-- SuperEdit -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ICCV'25] &nbsp; </font></strong><a href="https://arxiv.org/abs/2505.02370">SuperEdit: Rectifying and Facilitating Supervision for Instruction-Based Image Editing</a>
    <a href="https://github.com/bytedance/SuperEdit"><img src="https://img.shields.io/github/stars/bytedance/SuperEdit?style=social" alt="GitHub Stars" /></a>
  </p>
  <p>
    <strong>Ming Li</strong>, Xin Gu, Fan Chen, Xiaoying Xing, Longyin Wen, Chen Chen, Sijie Zhu
  </p>
</div>

<!-- Multi-Reward -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ICLR'25] &nbsp; </font></strong><a href="https://arxiv.org/abs/2411.04713">Multi-Reward as Condition for Instruction-based Image Editing.</a>
    <a href="https://github.com/bytedance/Multi-Reward-Editing"><img src="https://img.shields.io/github/stars/bytedance/Multi-Reward-Editing?style=social" alt="GitHub Stars" /></a>
  </p>
  <p>Xin Gu, <strong>Ming Li</strong>, Libo Zhang, Fan Chen, Longyin Wen, Tiejian Luo, Sijie Zhu</p>
</div>

<!-- DiffusionEngine -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [PR'25] &nbsp; </font></strong>
    <a href="https://arxiv.org/abs/2309.03893">DiffusionEngine: Diffusion Model is Scalable Data Engine for Object Detection.</a>
    <a href="https://github.com/bytedance/DiffusionEngine"><img src="https://img.shields.io/github/stars/bytedance/DiffusionEngine?style=social" alt="GitHub Stars" /></a>
  </p>
  <p>
    Manlin Zhang, Jie Wu, Yuxi Ren, <strong>Ming Li</strong>, Jie Qin, Xuefeng Xiao, Wei Liu, Rui Wang, Min Zheng, Andy J. Ma
  </p>
</div>

<!-- ControlNet++ -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ECCV'24] &nbsp; </font></strong><a href="https://arxiv.org/abs/2404.07987">ControlNet++: Improving Conditional Controls with Efficient Consistency Feedback.</a>
    <a href="https://github.com/liming-ai/ControlNet_Plus_Plus"><img src="https://img.shields.io/github/stars/liming-ai/ControlNet_Plus_Plus?style=social" alt="GitHub Stars" /></a>
  </p>
  <p><strong>Ming Li</strong>, Taojiannan Yang, Huafeng Kuang, Jie Wu, Zhaoning Wang, Xuefeng Xiao, Chen Chen</p>
</div>

<!-- Consecutive Brownian Bridge -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ACM MM'24] &nbsp; </font></strong><a href="https://arxiv.org/abs/2405.05953">Frame Interpolation with Consecutive Brownian Bridge Diffusion.</a>
    <a href="https://github.com/ZonglinL/ConsecutiveBrownianBridge"><img src="https://img.shields.io/github/stars/ZonglinL/ConsecutiveBrownianBridge?style=social" alt="GitHub Stars" /></a>
  </p>
  <p>Zonglin Lyu, <strong>Ming Li</strong>, Jianbo Jiao, Chen Chen</p>
</div>


<!-- AlignDet -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ICCV'23] &nbsp; </font></strong><a href="https://arxiv.org/abs/2307.11077">AlignDet: Aligning Pre-training and Fine-tuning in Object Detection.</a>
    <a href="https://github.com/liming-ai/AlignDet"><img src="https://img.shields.io/github/stars/liming-ai/AlignDet?style=social" alt="GitHub Stars" /></a>
  </p>
  <p><strong>Ming Li<sup>*</sup></strong>, Jie Wu<sup>*#</sup>, Xionghui Wang, Chen Chen<sup>#</sup>, Jie Qin, Xuefeng Xiao, Rui Wang, Min Zheng, Xin Pan</p>
</div>


<!-- FreeSeg -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [CVPR'23] &nbsp; </font></strong><a href="https://arxiv.org/abs/2303.17225">FreeSeg: Unified, Universal and Open-Vocabulary Image Segmentation.</a>
    <a href="https://github.com/bytedance/FreeSeg"><img src="https://img.shields.io/github/stars/bytedance/FreeSeg?style=social" alt="GitHub Stars" /></a>
  </p>
  <p>Jie Qin<sup>*</sup>, Jie Wu<sup>*#</sup>, Pengxiang Yan, <strong>Ming Li</strong>, Ren Yuxi, Xuefeng Xiao, Yitong Wang, Rui Wang, Shilei Wen, Xin Pan, Xingang Wang<sup>#</sup></p>
</div>


<!-- MGD -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ECCV'22] &nbsp; </font></strong><a href="https://arxiv.org/abs/2303.17225">Multi-granularity Distillation Scheme Towards Lightweight Semi-supervised Semantic Segmentation.</a>
    <a href="https://github.com/JayQine/MGD-SSSS"><img src="https://img.shields.io/github/stars/JayQine/MGD-SSSS?style=social" alt="GitHub Stars" /></a>
  </p>
  <p>
    Jie Qin, Jie Wu, <strong>Ming Li</strong>, Xuefeng Xiao, Min Zheng, Xingang Wang
  </p>
</div>

<!-- IL-NeRF -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [CVPR'25 Workshop, Computer Vision for Metaverse] &nbsp; </font></strong>
    <a href="https://arxiv.org/abs/2309.03893">IL-NeRF: Incremental Learning for Neural Radiance Fields with Camera Pose Alignment.</a>
  </p>
  <p>
    Letian Zhang, <strong>Ming Li</strong>, Chen Chen, Jie Xu
  </p>
</div>


# <font id="preprints" ><font color="#000000"> Preprints  </font>

<!-- LVLM Interpretation -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [arXiv'25] &nbsp; </font></strong><a href="https://arxiv.org/abs/2411.04713">Where do Large Vision-Language Models Look at when Answering Questions?</a>
    <a href="https://github.com/bytedance/LVLM_Interpretation"><img src="https://img.shields.io/github/stars/bytedance/LVLM_Interpretation?style=social" alt="GitHub Stars" /></a>
  </p>
  <p>
    Xiaoying Xing, Chia-Wen Kuo, Fuxin Li, Yulei Niu, Fan Chen, <strong>Ming Li</strong>, Ying Wu, Longyin Wen, Sijie Zhu
  </p>
</div>



# <font id="internships" ><font color="#000000"> Internships  </font>
- *2024.05 - Now*, [TikTok, ByteDance](https://www.tiktok.com/), USA.
- *2022.01 - 2023.07*, [ByteDance](https://www.bytedance.com/en/), Shenzhen, China.

# <font id="honors" ><font color="#000000"> Honors </font>
- [NeurIPS 2024 Top Reviewers](https://neurips.cc/Conferences/2024/ProgramCommittee#top-reviewers).
- 🏆 Champion of [CVPR 2023 Long-form Video Understanding and Generation Challenge (Track 3: Question-driven Video Understanding)](https://sites.google.com/view/loveucvpr23/track3).
- 🏆 Champion of [CVPR 2022 AVA Accessibility Vision and Autonomy Challenge (Image Segmentation)](https://eval.ai/web/challenges/challenge-page/1690/leaderboard/4046).
- ORCGS Doctoral Fellowship, the University of Central Florida. 2023.

<!-- <h1 id="-educations--"><id="educations"> Educations  </font></h1>
<ul>
  <li><em>2023.09 - Now</em>, Ph.D., Computer Science, University of Central Florida.</li>
  <li><em>2020.09 - 2023.06</em>, Master, Computer Science, Xiamen University.</li>
  <li><em>2016.09 - 2020.06</em>, Bachelar, Software Engineering, Hainan University.</li>
</ul> -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
