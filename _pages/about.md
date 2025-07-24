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

I am a postdoctoral fellow at the [Department of Computer Science and Engineering (CSE)](https://cse.hkust.edu.hk/), [Hong Kong University of Science and Technology (HKUST)](https://hkust.edu.hk//), advised by [Prof. Long Chen](https://zjuchenlong.github.io/). Prior to this, I obtained my PhD degree in Computer Science and Technology from the DCD Lab, Zhejiang University (ZJU), under the supervision of [Prof. Jun Xiao](https://person.zju.edu.cn/junx).

# 💬 Research Interests
- Computer Vision, Machine Learning
- Vision and Language, Multimodal Generation and Editing


# 📝 Publications 

(Selected works are shown. Full publication list in Google Scholar)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/2025-FreeEvent.png' alt="sym" width="500" height="300""></div></div>
<div class='paper-box-text' markdown="1">

[Event-Customized Image Generation](https://arxiv.org/abs/2410.02483)

**Zhen Wang**, Yilei Jiang, Dong Zheng, Jun Xiao, Long Chen

[**Paper**](https://arxiv.org/pdf/2410.02483)/[**Code**](https://github.com/HKUST-LongGroup/FreeEvent/)

- Customize your event (actions, poses, relations and interactions) with only one single image!
- Training-free, Plug-and-Play and Effective.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/2025-FreeEvent.png' alt="sym" width="500" height="300"></div></div>
<div class='paper-box-text' markdown="1">

[IterIS: Iterative Inference-Solving Alignment for LoRA Merging](https://openaccess.thecvf.com/content/CVPR2025/html/Chen_IterIS_Iterative_Inference-Solving_Alignment_for_LoRA_Merging_CVPR_2025_paper.html)

Hongxu Chen, **Zhen Wang**, Runshi Li, Bowei Zhu, Long Chen

[**Paper**](https://openaccess.thecvf.com/content/CVPR2025/papers/Chen_IterIS_Iterative_Inference-Solving_Alignment_for_LoRA_Merging_CVPR_2025_paper.pdf)/[**Code**](https://github.com/HKUST-LongGroup/IterIS-merging)

- A sample-efficient and broadly applicable LoRA merging method based on an iterative inference-solving framework with enhanced performance.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CLIPDrag: Combining Text-based and Drag-based Instructions for Image Editing](https://proceedings.iclr.cc/paper_files/paper/2025/hash/10162500bd9745ac0d4dc321b726e49e-Abstract-Conference.html)

Ziqi Jiang, **Zhen Wang**, Long Chen

[**Paper**](https://proceedings.iclr.cc/paper_files/paper/2025/file/10162500bd9745ac0d4dc321b726e49e-Paper-Conference.pdf)/[**Code**](https://github.com/HKUST-LongGroup/CLIPDrag)

- Incorporating text signals into drag-based methods for precise and flexible image editing.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning combinatorial prompts for universal controllable image captioning](https://link.springer.com/article/10.1007/s11263-024-02179-4)

**Zhen Wang**, Jun Xiao, Yueting Zhuang, Fei Gao, Jian Shao, Long Chen

[**Paper**](https://link.springer.com/content/pdf/10.1007/s11263-024-02179-4.pdf)

- A lightweight prompt-based framework for controllable image captioning.
- Effective and efficient for both single and combined controls.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Decap: Towards generalized explicit caption editing via diffusion mechanism](https://link.springer.com/chapter/10.1007/978-3-031-72775-7_21)

**Zhen Wang**, Xinyun Jiang, Jun Xiao, Tao Chen, Long Chen

[**Paper**](https://link.springer.com/content/pdf/10.1007/978-3-031-72775-7.pdf)

- A diffusion-based explicit caption editing framework with strong generalization ability across various editing and generation scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Freetuner: Any subject in any style with training-free diffusion](https://arxiv.org/abs/2405.14201)

Youcan Xu, **Zhen Wang**, Jun Xiao, Wei Liu, Long Chen

[**Paper**](https://arxiv.org/pdf/2405.14201)

- A flexible and training-free method for compositional personalization.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Explicit image caption editing](https://link.springer.com/chapter/10.1007/978-3-031-20059-5_7)

**Zhen Wang**, Long Chen, Wenbo Ma, Guangxing Han, Yulei Niu, Jian Shao, Jun Xiao

[**Paper**](https://link.springer.com/content/pdf/10.1007/978-3-031-20059-5.pdf)/[**Code**](https://github.com/baaaad/TIger)/[**Benchmark**](https://github.com/baaaad/ECE)

- An interesting new task: explicit caption editing (ECE), and new benchmarks.
- An effective and efficient ECE model.
</div>
</div>



<div style="display: none;">
  
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
</div>
