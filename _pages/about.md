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

I am a Ph.D. student in Computer Science at the University of California, San Diego, advised by [Prof. Julian McAuley](https://cseweb.ucsd.edu/~jmcauley/). My research focuses on multimodal large language models, reinforcement learning for LLM reasoning, and recommender systems. I received my B.E. from the Turing Class, Chu Kochen Honors College at Zhejiang University.

<span class='anchor' id='-news'></span>
# 🔥 News

- *2026.05*: &nbsp; [WS-GRPO](https://arxiv.org/abs/2602.17025) accepted at **ICML 2026**
- *2025.11*: &nbsp; [Image Difference Captioning via Adversarial Preference Optimization](https://aclanthology.org/2025.emnlp-main.1713/) accepted at **EMNLP 2025**
- *2025.10*: &nbsp; [Traceable and Explainable Multimodal Large Language Models](https://openreview.net/forum?id=pQm66IPmeE) accepted at **COLM 2025**
- *2025*: &nbsp; [AutoGeo](https://doi.org/10.1109/TMM.2025.3557720) published in **IEEE Transactions on Multimedia**
- *2024.09*: &nbsp; One paper accepted by **Briefings in Bioinformatics** ([paper link](https://academic.oup.com/bib/article/25/5/bbae443/7754451))
- *2024.06*: &nbsp; Graduated from Chu Kochen Honors College of Zhejiang University with B.E.

<span class='anchor' id='-publications'></span>
# 📝 Publications

## Published

<div class='paper-box'><div class='paper-box-text' markdown="1">

*ICML 2026*

[WS-GRPO: Weakly-Supervised Group-Relative Policy Optimization for Rollout-Efficient Reasoning](https://icml.cc/virtual/2026/poster/64686)

Gagan Mundada, **Zihan Huang**, Rohan Surana, Sheldon Yu, Jennifer Yuntong Zhang, Xintong Li, Tong Yu, Lina Yao, Jingbo Shang, Julian McAuley, Junda Wu

[[Paper](https://arxiv.org/abs/2602.17025)] [[OpenReview](https://openreview.net/forum?id=rXma48njj6)]

</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

*EMNLP 2025*

[Image Difference Captioning via Adversarial Preference Optimization](https://aclanthology.org/2025.emnlp-main.1713/)

**Zihan Huang**, Junda Wu, Rohan Surana, Tong Yu, David Arbour, Raghav Sinha, Julian McAuley

[[Paper](https://aclanthology.org/2025.emnlp-main.1713/)]

</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

*COLM 2025*

[Traceable and Explainable Multimodal Large Language Models: An Information-Theoretic View](https://openreview.net/forum?id=pQm66IPmeE)

**Zihan Huang**, Junda Wu, Rohan Surana, Raghav Jain, Tong Yu, Raghavendra Addanki, David Arbour, Sungchul Kim, Julian McAuley

[[Paper](https://openreview.net/forum?id=pQm66IPmeE)]

</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

*IEEE TMM 2025*

[AutoGeo: Automating Geometric Image Dataset Creation for Enhanced Geometry Understanding](https://autogeo-official.github.io/)

**Zihan Huang**, Tao Wu, Wang Lin, Shengyu Zhang, Jingyuan Chen, Fei Wu

[[Paper](https://doi.org/10.1109/TMM.2025.3557720)] [[Project](https://autogeo-official.github.io/)]

</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

*BIB 2024*

[Global-local aware Heterogeneous Graph Contrastive Learning for multifaceted association prediction in miRNA–gene–disease networks](https://academic.oup.com/bib/article/25/5/bbae443/7754451)

Yang Si, **Zihan Huang**, Zhengqing Fang, Zhen Yuan, Zhen Huang, Yuxuan Li, Yuxuan Wei, Fei Wu, Yong-Fang Yao

[[Paper](https://academic.oup.com/bib/article/25/5/bbae443/7754451)]

</div>
</div>

## Preprints

<div class='paper-box'><div class='paper-box-text' markdown="1">

*arXiv*

[Generate, Filter, Control, Replay: A Comprehensive Survey of Rollout Strategies for LLM Reinforcement Learning](https://arxiv.org/abs/2605.02913)

Rohan Surana, Gagan Mundada, Xunyi Jiang, Chen Wang, Zifan Tang, Dongxu Jiao, **Zihan Huang**, et al.

[[Paper](https://arxiv.org/abs/2605.02913)]

</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

*arXiv*

[AMPS: Adaptive Modality Preference Steering via Functional Entropy](https://arxiv.org/abs/2602.12533)

**Zihan Huang**, Xintong Li, Rohan Surana, Tong Yu, Rui Wang, Julian McAuley, Jingbo Shang, Junda Wu

[[Paper](https://arxiv.org/abs/2602.12533)]

</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

*arXiv*

[Skill-R1: Agent Skill Evolution via Reinforcement Learning](https://arxiv.org/abs/2605.09359)

Yash Vishe, Rohan Surana, Xunyi Jiang, **Zihan Huang**, Xintong Li, Nikki Lijing Kuang, Tong Yu, Ryan A. Rossi, Jingbo Shang, Julian McAuley, Junda Wu

[[Paper](https://arxiv.org/abs/2605.09359)]

</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

*arXiv*

[Skill-CMIB: Multimodal Agent Skill for Consistent Action via Conditional Multimodal Information Bottleneck](https://arxiv.org/abs/2605.08526)

**Zihan Huang**, Junda Wu, Tong Yu, Qianqi Yan, Rohan Surana, Uttaran Bhattacharya, Lina Yao, Xin Eric Wang, Julian McAuley

[[Paper](https://arxiv.org/abs/2605.08526)]

</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

*arXiv*

[Evaluation on Entity Matching in Recommender Systems](https://arxiv.org/abs/2601.17218)

**Zihan Huang**, Rohan Surana, Zhouhang Xie, Junda Wu, Yu Xia, Julian McAuley

[[Paper](https://arxiv.org/abs/2601.17218)] [[Code](https://github.com/huang-zihan/Reddit-Amazon-Entity-Matching)]

</div>
</div>

<span class='anchor' id='-educations'></span>
# 📖 Educations

- *2024.09 – Present*, Ph.D. in Computer Science, University of California San Diego, CA, United States (Advisor: [Julian McAuley](https://cseweb.ucsd.edu/~jmcauley/))
- *2020.09 – 2024.06*, B.E. in Artificial Intelligence, Turing Class, Chu Kochen Honors College, Zhejiang University, Hangzhou, China

<span class='anchor' id='-research-experiences'></span>
# 💼 Research Experiences

- **UC San Diego** — McAuley Lab, *2024.09 – Present*, Advisor: Prof. Julian McAuley
- **Alibaba** — Tmall Meta Research Group, *2024.06 – 2024.09*
- **Shanghai Institute for Advanced Study of Zhejiang University**, *2024.01 – 2024.06*, Supervisor: Prof. Jingyuan Chen
- **ZJU DCD Lab**, *2022.02 – 2023.06*, Supervisor: Prof. Fei Wu

<span class='anchor' id='-honors-and-awards'></span>
# 🎖 Honors and Awards

- Project leader of National Student Research Training Program (SRTP) and rated as Outstanding, 2022–2023
- Honorable Winner of Mathematical Contest in Modeling (MCM), team leader, 2022, COMAP
- Academic Excellence Award 2020–2022, Chu Kochen Honors College of ZJU
- Second-Class Scholarship for Elite Student in Basic Sciences, 2021–2022, ZJU
- NeurIPS emergency Reviewer, 2023
- 2nd Prize of 3D Printing Competition, 2020, ZJU
- 2nd Prize of Zhejiang College Student Physics Competition, 2021
- Half Marathon 1h53m, ranked 84/1000+, 2020, Hangzhou, Zhejiang
- 1st Prize of Search & Rescue, Asia-Pacific Robotics Championship (APRC), 2013
- 1st Prize of Triathlon, Asia-Pacific Robotics Championship (APRC), 2013
