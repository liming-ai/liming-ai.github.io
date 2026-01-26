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
I am a second-year PhD student at the University of Central Florida, with [Prof. Chen Chen](https://www.crcv.ucf.edu/chenchen/index.html) as my advisor. I am currently interning at ByteDance-Seed with [Jie Wu](https://wujie1010.github.io/) and [Rui Wang](https://scholar.google.com/citations?user=nGki_EEAAAAJ&hl=zh-CN) to explore visual and multimodal RL.


# <font id="publications" ><font color="#000000"> Selected Publications  </font>

<!-- Seedance 1.5 -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ByteDance Seed Technical Report] &nbsp; </font></strong><a href="https://arxiv.org/abs/2512.13507">Seedance 1.5 pro: A Native Audio-Visual Joint Generation Foundation Model</a>
  </p>
  <p>
    ByteDance Seed Team
  </p>
</div>

<!-- ViPO -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ICLR'26] &nbsp; </font></strong><a href="https://openreview.net/forum?id=x5zP3k64Nl">ViPO: Visual Preference Optimization at Scale</a>
  </p>
  <p>
    <strong>Ming Li</strong>, Jie Wu, Justin Cui, Xiaojie Li, Rui Wang, Chen Chen
  </p>
</div>

<!-- Self-Forcing++ -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ByteDance Seed Technical Report] [ICLR'26] &nbsp; </font></strong><a href="https://arxiv.org/abs/2510.02283">Self-Forcing++: Towards Minute-Scale High-Quality Video Generation</a>
    <a href="https://github.com/justincui03/Self-Forcing-Plus-Plus"><img src="https://img.shields.io/github/stars/justincui03/Self-Forcing-Plus-Plus?style=social" alt="GitHub Stars" /></a>
  </p>
  <p>
    Justin Cui, Jie Wu, <strong>Ming Li</strong>, Tao Yang, Xiaojie Li, Rui Wang, Andrew Bai, Yuanhao Ban, Cho-Jui Hsieh
  </p>
</div>

<!-- Video Reasoning -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [Preprint] &nbsp; </font></strong><a href="https://arxiv.org/abs/2511.13853">Can World Simulators Reason? Gen-ViRe: A Generative Visual Reasoning Benchmark</a>
    <a href="https://github.com/L-CodingSpace/GVR"><img src="https://img.shields.io/github/stars/L-CodingSpace/GVR?style=social" alt="GitHub Stars" /></a>
  </p>
  <p>
    Xinxin Liu, Zhaopan Xu, <strong>Ming Li</strong>, Kai Wang, Yong Jae Lee, Yuzhang Shang
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

<!-- ControlNet++ -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ECCV'24] &nbsp; </font></strong><a href="https://arxiv.org/abs/2404.07987">ControlNet++: Improving Conditional Controls with Efficient Consistency Feedback.</a>
    <a href="https://github.com/liming-ai/ControlNet_Plus_Plus"><img src="https://img.shields.io/github/stars/liming-ai/ControlNet_Plus_Plus?style=social" alt="GitHub Stars" /></a>
  </p>
  <p><strong>Ming Li</strong>, Taojiannan Yang, Huafeng Kuang, Jie Wu, Zhaoning Wang, Xuefeng Xiao, Chen Chen</p>
</div>

<!-- AlignDet -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [ICCV'23] &nbsp; </font></strong><a href="https://arxiv.org/abs/2307.11077">AlignDet: Aligning Pre-training and Fine-tuning in Object Detection.</a>
    <a href="https://github.com/liming-ai/AlignDet"><img src="https://img.shields.io/github/stars/liming-ai/AlignDet?style=social" alt="GitHub Stars" /></a>
  </p>
  <p><strong>Ming Li<sup>*</sup></strong>, Jie Wu<sup>*</sup>, Xionghui Wang, Chen Chen, Jie Qin, Xuefeng Xiao, Rui Wang, Min Zheng, Xin Pan</p>
</div>

<!-- FreeSeg -->
<div class="paper-box-text">
  <p>
    <strong><font color="#9C2C23"> [CVPR'23] &nbsp; </font></strong><a href="https://arxiv.org/abs/2303.17225">FreeSeg: Unified, Universal and Open-Vocabulary Image Segmentation.</a>
    <a href="https://github.com/bytedance/FreeSeg"><img src="https://img.shields.io/github/stars/bytedance/FreeSeg?style=social" alt="GitHub Stars" /></a>
  </p>
  <p>Jie Qin<sup>*</sup>, Jie Wu<sup>*</sup>, Pengxiang Yan, <strong>Ming Li</strong>, Ren Yuxi, Xuefeng Xiao, Yitong Wang, Rui Wang, Shilei Wen, Xin Pan, Xingang Wang</p>
</div>



# <font id="internships" ><font color="#000000"> Internships  </font>
- *2025.01 - Now*, [ByteDance Seed](https://seed.bytedance.com/en/), USA.
- *2024.05 - *2024.12*, [TikTok, ByteDance](https://www.tiktok.com/), USA.
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
