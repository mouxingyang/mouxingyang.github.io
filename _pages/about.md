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

Hi, I am Mouxing Yang (杨谋星). I am currently a Research Fellow / Postdoctoral Fellow at the  [XLearning](https://xlearning-lab.com) research group, College of Computer Science, Sichuan University. I obtained my Ph.D. degree from Sichuan University in Dec. 2025 (ahead of schedule，提前毕业) under the supervision of Prof. [Xi Peng](https://cs.scu.edu.cn/info/1282/13557.htm) (彭玺). My work has received over 2,300 citations and has been recognized among the world’s top 2% of scientists and the National Postdoctoral Innovation Talents Support Program, which selects only 18 candidates annually in the Computer Science and Technology discipline across China.

I have authored more than 30 papers in tier-1 journals and conferences, including 8 IEEE TPAMI/IJCV papers, 2 ICLR Oral papers (~ top 1% of accepted papers). My work has received over 2,300 citations and has been awarded the World’s Top 2% of Scientists and the National Postdoctoral Innovation Talents Support Program. My research mainly focuses on Reliable Multi-modal Learning, Multi-modal Test-time Computing/Adaptation and Agentic AI in the Wild, with contribution in:

+ Reliable Multi-modal Learning: I have worked extensively on tackling challenges such as noisy correspondence (NeurIPS'26, ICLR'26, TPAMI'26, TPAMI'25, IJCV'24, TIP'24, NeurIPS'24, ICCV'23, etc.) and missing modality (TPAMI'26, AAAI'24, TPAMI'23, TPAMI'22) in the image-text, multi-view data. For more insights on noisy correspondence, please refer to our repository: [Noisy Correspondence Summary](https://github.com/XLearning-SCU/Awesome-Noisy-Correspondence).
+ Multi-modal Test-time Computing/Adaptation: I believe the future of foundation models lies in self-evolving systems. My recent research focuses on unleashing their potential during inference by addressing reliability challenges in dynamic environments, with applications in multi-modal recognition (ICLR'24, AAAI'26), cross-modal retrieval (TPAMI'26, ICLR'25, ICML'25), and multi-modal CoT (ICML'26).
+ Agentic AI in the Wild: I am currently exploring how to extend LLM agents to diverse, open-ended real-world scenarios, with recent work on skill retrieval, software engineering, and efficient coding agents. More studies are underway.

杨谋星，四川大学计算机学院研究员（专职科研）、研究生导师，入选国家博新计划、全球前2%顶尖科学家年度榜单，主要研究方向为鲁棒多模态学习（缺失模态、噪声关联）、多模态测试时自适应、Agentic AI。已在Nature子刊及CCF-A类刊物上发表论文30余篇，谷歌学术引用2300余次，获国自然青C项目、国自然博士生项目、第十二届百度奖学金（全球10人，我国中西部地区唯一）等的资助。  

**招生要求**：如您对我研究方向感兴趣，且有意愿与我一起开展研究，请先阅读[XLearning](https://xlearning-lab.com)实验室招生细则，随后联系 (Email: yangmouxing[at]gmail.com, yangmouxing[at]scu.edu.cn)

# 🔥 News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2026.09*: &nbsp; Two NeurIPS'26 paper has been accepted. Congrats to Zhichao and Yijie.
- *2026.08*: &nbsp; I will serve as Area Chair for ICLR'27.
- *2026.08*: &nbsp; One TPAMI'27 paper has been accepted. Congrats to Haobin.
- *2026.08*: &nbsp; I will serve as SPC member for AAAI'27.
- *2026.05*: &nbsp; Two ICML'26 paper have been accepted. Congrats to Haobin and Yuxin.
- *2026.02*: &nbsp; Two ICLR'26 paper have been accepted as Orals (~1.3%). Big Congrats to Haobin and Haochen.
- *2025.12*: &nbsp; One TPAMI'26 paper has been accepted. Congrats to Haobin.
- *2025.10*: &nbsp; One AAAI'26 paper has been accepted. Congrats to Yutong.
- *2025.05*: &nbsp; One IJCAI'25 paper and two ICML'25 have been accepted. Congrats to Yiding and Guofeng.
- *2025.02*: &nbsp; I am honored to be awarded the Baidu Research Fellowship (百度奖学金，10 PhD candidates worldwide).
- *2025.01*: &nbsp; One paper has been accepted by ICLR'25 as Spotlight (acc rate=5.1%). Congrats to Haobin.
- *2024.12*: &nbsp; My research is granted by Fundamental Research Project for Young Ph.D. students from NSFC (国家自然科学基金青年学生基础研究项目(博士生)).
- *2024.09*: &nbsp; One TPAMI'25 paper and one NeurIPS'24 paper have been accepted.
- *2024.02*: &nbsp; One paper has been accepted by TIP'24.
- *2024.01*: &nbsp; One ICLR'24 paper and one IJCV'24 paper have been accepted.
- *2023.12*: &nbsp; One AAAI'24 paper and one TPAMI'24 paper have been accepted. Congrats to Yiding.
- *2023.09*: &nbsp; One paper has been accepted by Nature Communications. Big congrats to Yunfan.
- *2023.07*: &nbsp; One paper has been accepted by ICCV'23. Congrats to Yijie.
- *2023.04*: &nbsp; One paper has been accepted by IJCAI'23. Congrats to Haobin.
- *2022.06*: &nbsp; One paper has been accepted by IJCV'22. Congrats to Yunfan.
- *2022.03*: &nbsp; One paper has been accepted by CVPR'22.
- *2022.02*: &nbsp; One paper has been accepted by TPAMI'23.
- *2021.03*: &nbsp; One paper has been accepted by CVPR'21.

<!-- 

# 📝 Selected Publications 

(#: Equal contribution, &dagger;: Corresponding author)

- `ICML'26` [Reliable Thinking with Images](https://arxiv.org/pdf/2602.12916), Haobin Li, Yutong Yang, Yijie Lin, Xiang Dai, **Mouxing Yang**&dagger;, Xi Peng&dagger;
- `ICLR'26 Oral` [Learning with Dual-level NoisyCorrespondence for Multi-modal Entity Alignment](https://arxiv.org/pdf/2510.18240), Haobin Li, Yijie Lin, Peng Hu, **Mouxing Yang**&dagger;, Xi Peng&dagger;
- `TPAMI'26` [Community-aware Multi-view Representation Learning with Incomplete Information](https://xlearning-lab.com/assets/2026-TPAMI-Community-aware-Multi-view-Representation-Learning-with-Incomplete-Information.pdf), Haobin Li, Yijie Lin, Peng Hu, **Mouxing Yang**&dagger;, Xi Peng&dagger;
- `AAAI'26` [Endowing Vision-Language Models with System 2 Thinking for Fine-grained Visual Recognition](https://xlearning-lab.com/assets/2026-AAAI-Endowing-Vision-Language-Models-with-System-2-Thinking-for-Fine-grained-Visual-Recognition.pdf), Yutong Yang, Lifu Huang, Yijie Lin, Xi Peng, **Mouxing Yang**&dagger;
- `ICLR'25 Spotlight` [Test-time Adaptation for Cross-modal Retrieval with Query Shift](https://openreview.net/pdf?id=BmG88rONaU), Haobin Li, Peng Hu, Qianjun Zhang, Xi Peng, XitingLiu, **Mouxing Yang**&dagger; 
- `TPAMI'25` [Noise-robust Vision-language Pre-training with Positive-negative Learning](https://ieeexplore.ieee.org/abstract/document/10684058), Zhenyu Huang#, **Mouxing Yang**#, Xinyan Xiao, Peng Hu, Xi Peng
- `TIP'24` [Cross-modal Retrieval with Noisy Correspondence via Consistency Refining and Mining](http://pengxi.me/wp-content/uploads/2024/03/pengxime-online.pdf), Xinran Ma#, **Mouxing Yang**#, Yunfan Li, Peng Hu, Jiancheng Lv, Xi Peng
- `NeurIPS'24` Robust Contrastive Multi-view Clustering against Dual Noisy Correspondence, Ruiming Guo#, **Mouxing Yang**#, Yijie Lin, Xi Peng, Peng Hu
- `ICLR'24` [Test-time Adaption against Multi-modal Reliability Bias](https://openreview.net/pdf?id=TPZRq4FALB), **Mouxing Yang**, Yunfan Li, Changqing Zhang, Peng Hu, Xi Peng
- `IJCV'24` [Robust Object Re-identification with Coupled Noisy Labels](http://pengxi.me/wp-content/uploads/2024/02/online_version.pdf), **Mouxing Yang**, Zhenyu Huang, Xi Peng
- `CVPR'22` [Learning with Twin Noisy Labels for Visible-Infrared Person Re-Identification](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Learning_With_Twin_Noisy_Labels_for_Visible-Infrared_Person_Re-Identification_CVPR_2022_paper.pdf), **Mouxing Yang**, Zhenyu Huang, Peng Hu, Taihao Li, Jiancheng Lv, Xi Peng
- `TPAMI'23 (ESI Hot Paper)` [Robust Multi-view Clustering with Incomplete Information](http://pengxi.me/wp-content/uploads/2022/03/Robust-Multi-view-Clustering-with-Incomplete-Information.pdf), **Mouxing Yang**, Yunfan Li, Peng Hu, Jinfeng Bai, Jiancheng Lv, Xi Peng
- `CVPR'21` [Partially View-aligned Representation Learning with Noise-robust Contrastive Loss](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Partially_View-Aligned_Representation_Learning_With_Noise-Robust_Contrastive_Loss_CVPR_2021_paper.pdf), **Mouxing Yang**, Yunfan Li, Zhenyu Huang, Zitao Liu, Peng Hu, Xi Peng  -->

<!-- under review -->



# 🎖 Honors and Awards
- World's Top 2% Scientists (全球前 2% 顶尖科学家榜单)
- National Postdoctoral Innovation Talents Support Program (国家博士后创新人才支持计划)
- 四川大学第二批“海纳博士后”支持计划 (全校9人)
- Baidu Research Fellowship (百度奖学金，10 PhD candidates worldwide)
- Fundamental Research Project for Young Ph.D. students from NSFC (国家自然科学基金青年学生基础研究项目(博士生))
- National Scholarship (国家奖学金， three times)

<!-- # 📖 Educations

- 2020.09 - now, Ph.D. student, Sichuan Univeristy, Chengdu.
- 2016.09 - 2020.06, Undergraduate, Sichuan Univeristy, Chengdu. -->

# 💬 Invited Talks
- *2026.07*, *Imperfect Chain-of-Thoughts in Multi-modal Reasoning*, Special Sessions of ChinaMM 2026, Taiyuan
- *2025.09*, *Learning with Noisy Correspondence*, Special Sessions of the 22nd Annual Academic Conference on Signal Processing of CIE, Beijing
- *2022.06*, *Noisy Correspondences: A New Paradigm for Learning with Noisy Labels*, TrustML Young Scientist Seminar, RIKEN AIP (Online)
- *2022.05*, CVPR 2022 Pre-conference Sharing Session, Chengdu

# 🙋 Service
- **Conference AC/SPC**: ICLR, AAAI

- **Journal Reviewer**: IEEE TPAMI, IEEE TIP, IEEE TKDE, etc.

- **Conference Reviewer**: ICLR, NeurIPS (Top reviewer), ICML (Gold reviewer), CVPR, ICCV, etc.

