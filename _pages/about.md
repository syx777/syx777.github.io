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

 I am currently a Master student at the Department of Computer Science and Technology, University of Science and Technology of China (USTC), supervised by Prof. Zhenya Huang at the State Key Laboratory of Cognitive Intelligence.


My research interest includes large language models and agentic coding.  

<!-- I have published several papers. <a href='https://scholar.google.com/citations?user=j9fZB5gAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. -->


<!--
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Findings</div><img src='images/publications/swe-mutation.png' alt="The four-stage SWE-Mutation benchmark construction framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### [SWE-Mutation: Can LLMs Generate Reliable Test Suites in Software Engineering?](https://aclanthology.org/2026.findings-acl.1976/)

**Yuxuan Sun**, Yuze Zhao, Yufeng Wang, Yao Du, Zhiyuan Ma, Jinbo Wang, Mengdi Zhang, Kai Zhang, Zhenya Huang

*Findings of the Association for Computational Linguistics: ACL 2026*, 39651–39674

[**PDF**](https://aclanthology.org/2026.findings-acl.1976.pdf) · [**Code & Data**](https://github.com/Sunny4Coding/SWE-Mutation) · [**arXiv**](https://arxiv.org/abs/2605.22175)

- Introduces a benchmark that stress-tests LLM-generated test suites with realistic semantic mutants. Its agentic pipeline locates mutation scopes, generates and judges candidate bugs, and uses self-play to retain hard mutants; the final benchmark contains 2,636 mutants from 800 instances, including a nine-language subset. Even DeepSeek-V3.1 reaches only 10.20% verified reproduction and 36.15% relative detection, exposing a substantial test-generation gap.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TPAMI 2025</div><img src='images/publications/efficient-benchmarking.svg' alt="Overview of bias-bounded benchmark subset selection" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### [Efficient Benchmarking via Bias-Bounded Subset Selection](https://doi.org/10.1109/TPAMI.2025.3598031)

Yan Zhuang, Junhao Yu, Qi Liu, **Yuxuan Sun**, Jiatong Li, Zhenya Huang, Enhong Chen

*IEEE Transactions on Pattern Analysis and Machine Intelligence*, 47(12):11785–11801, 2025

[**PDF**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11123151) · [**Supplement**](https://ieeexplore.ieee.org/ielx8/34/11230086/11123151/supp1-3598031.pdf?arnumber=11123151)

- Formalizes efficient evaluation as a subset-selection problem, proves that the objective is submodular, and derives a simple greedy method with bias-control and generalization guarantees. Across 11 language-model benchmarks, the selected subsets preserve score estimates and model rankings while using no more than 30% of the original evaluation items.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/publications/fast-catch-up.png' alt="Fast catch-up effect under late batch-size switching" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### [Fast Catch-Up, Late Switching: Optimal Batch Size Scheduling via Functional Scaling Laws](https://proceedings.iclr.cc/paper_files/paper/2026/hash/0c7aaeb2745951f01224b3f95c75b528-Abstract-Conference.html)

Jinbo Wang, Binghui Li, Zhanpeng Zhou, Mingze Wang, **Yuxuan Sun**, Jiaqi Zhang, Xunliang Cai, Lei Wu

*International Conference on Learning Representations (ICLR), 2026*

[**PDF**](https://proceedings.iclr.cc/paper_files/paper/2026/file/0c7aaeb2745951f01224b3f95c75b528-Paper-Conference.pdf) · [**Code (Supplemental)**](https://proceedings.iclr.cc/paper_files/paper/2026/file/0c7aaeb2745951f01224b3f95c75b528-Supplemental-Conference.zip) · [**arXiv**](https://arxiv.org/abs/2602.14208)

- Extends functional scaling laws to batch-size scheduling and identifies a fast catch-up effect: on hard tasks, training can remain at a small batch for most of the run and switch late without losing the large-batch trajectory. Experiments across Dense and MoE language models from 50M to 1.1B parameters, with up to 1T training tokens, consistently favor late switching over constant or early-switch schedules.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 Findings</div><img src='images/publications/testagent.png' alt="TestAgent architecture from question-bank construction to diagnosis report" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### [TestAgent: An Adaptive and Intelligent Expert for Human Assessment](https://aclanthology.org/2025.findings-acl.40/)

Junhao Yu, Yan Zhuang, **Yuxuan Sun**, Weibo Gao, Qi Liu, Mingyue Cheng, Zhenya Huang, Enhong Chen

*Findings of the Association for Computational Linguistics: ACL 2025*, 724–747

[**PDF**](https://aclanthology.org/2025.findings-acl.40.pdf) · [**arXiv**](https://arxiv.org/abs/2506.03032)

- Combines conversational LLM interaction with adaptive question selection, cognitive diagnosis, autonomous feedback, anomaly handling, and personalized report generation. Experiments spanning personality, educational, and mental-health assessment achieve comparable ability estimation with 20% fewer questions; a 50-person study also reports significant gains in fluency, speed, and interaction experience.
</div>
</div>

[View all publications and current citation counts on Google Scholar](https://scholar.google.com/citations?user=j9fZB5gAAAAJ).

# 🎖 Honors and Awards
- *2025* Outstanding Graduate, University of Science and Technology of China
- *2024* Soong Ching Ling Future Scholarship, University of Science and Technology of China
- *2023* Outstanding Student Scholarship Award, University of Science and Technology of China
- *2022* Outstanding Student Scholarship Award, University of Science and Technology of China

# 📖 Educations
- *2025.09 - present*, Master's Degree, University of Science and Technology of China, Computer Science and Technology.
- *2021.08 - 2025.06*, Bachelor's Degree, University of Science and Technology of China, Computer Science and Technology.
- *2018.09 - 2021.06*, Senior High School Student, Zhengzhou Foreign Language School.

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

-->

# 💻 Internships
- *2025.04 - present*, [Meituan](https://www.meituan.com/), 3A Team, Post training.
