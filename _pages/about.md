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
Hello! I'm currently wrapping up my Ph.D. journey at Zhejiang University, supervised by Prof. [Kun Kuang](https://kunkuang.github.io/) and Prof. [Fei Wu](https://mypage.zju.edu.cn/wufei). I obtained my B.S. degree from Zhejiang University. I closely collaborate with Prof. [Xiaozhong Liu](https://www.wpi.edu/people/faculty/xliu14) from Worcester Polytechnic Institute and Prof. [Adam Jatowt](https://adammo12.github.io/aj/) from the University of Innsbruck.

My research interests include LLM, NLP, LegalAI, and Causal Inference. I have published more than 10 papers in conferences such as ACL, EMNLP, NAACL, SIGIR, and AAAI, among others.

I am the main contributor to the open-source legal LLM project [wisdomInterrogatory](https://github.com/zhihaiLLM/wisdomInterrogatory), which led to an invitation to participate in the [Yunqi Conference](https://yunqi.aliyun.com/).

Currently, I am also a visiting student at the University of Innsbruck, Austria. I expect to graduate in June 2024 and am seeking job opportunities. Please feel free to [contact me](mailto:wuyiquan@zju.edu.cn) if you are interested!

# 🔥 News
- *2024.03*: &nbsp;🎉🎉 **One** paper is accepted by NAACL'24! 
- *2024.02*: &nbsp;🎉🎉 **Two** papers are accepted by COLING'24! 
- *2023.12*: &nbsp;🎉🎉 **One** paper is accepted by AAAI'24!
- *2023.10*: &nbsp;🎉🎉 **One** paper is accepted by EMNLP'23!
- *2023.08*: &nbsp;🎉🎉 The open-sourced legal large language model [wisdomInterrogatory](https://github.com/zhihaiLLM/wisdomInterrogatory) is released!

# 📝 Projects and Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='../images/luwen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[**wisdomInterrogatory**](https://github.com/zhihaiLLM/wisdomInterrogatory) \| [![](https://img.shields.io/github/stars/zhihaiLLM/wisdomInterrogatory?style=social&label=Stars)](https://github.com/zhihaiLLM/wisdomInterrogatory) (智海-录问 in Chinese) is an open-source Legal LLM that involves constructing training data, accelerating model training, integrating knowledge bases, and developing evaluation metrics. The model offers legal assistance services such as Q&A, case analysis, and legal document generation. It has garnered over 400 stars, more than 6,730 downloads, and over 110,000 uses. As the **project leader**, I was invited to participate in the [Yunqi Conference](https://yunqi.aliyun.com/).

The model can also be accessed [online](https://modelscope.cn/studios/wisdomOcean/wisdomInterrogatory/summary).
</div>
</div>

- ``AAAI'24`` ["De-biased Attention Supervision for Text Classification with Causality"](), **Yiquan Wu**, Yifei Liu, Ziyu Zhao, Weiming Lu, Yating Zhang, Changlong Sun, Fei Wu, Kun Kuang. 

- ``NAACL'24-Findings`` ["Unleashing the Power of LLMs in Court View Generation by Stimulating Internal Knowledge and Incorporating External Knowledge"](), Yifei Liu, **Yiquan Wu**, Ang Li, Yating Zhang, Changlong Sun, Weiming Lu, Fei Wu, Kun Kuang

- ``COLING'24`` ["Enhancing Court View Generation with Knowledge Injection and Guidance"](https://arxiv.org/html/2403.04366v1), Ang Li, **Yiquan Wu**, Yifei Liu, Kun Kuang, Fei Wu, Ming Cai.

- ``COLING'24`` ["From Graph to Word Bag: Introducing Domain Knowledge to Confusing Charge Prediction"](https://arxiv.org/pdf/2403.04369.pdf), Ang Li, Qiangchao Chen, **Yiquan Wu**, Xiang Zhou, Kun Kuang, Fei Wu and Ming Cai.

- ``EMNLP'23(oral)`` ["Precedent-Enhanced Legal Judgment Prediction with LLM and Domain-Model Collaboration"](https://aclanthology.org/2023.emnlp-main.740/), **Yiquan Wu**, Siying Zhou, Yifei Liu, Weiming Lu, Xiaozhong Liu, Yating Zhang, Changlong Sun, Fei Wu, Kun Kuang. 

- ``ACL'23-Findings`` ["Focus-aware Response Generation in Inquiry Conversation"](https://aclanthology.org/2023.findings-acl.797.pdf), **Yiquan Wu**, Weiming Lu, Yating Zhang, Adam Jatowt, Jun Feng, Changlong Sun, Fei Wu, Kun Kuang.

- ``SIGIR'23`` ["ML-LJP: MultiLaw Aware Legal Judgment Prediction"](https://dl.acm.org/doi/pdf/10.1145/3539618.3591731?casa_token=WszNtDgTojEAAAAA:2flLNOaXZKg0fkrt_ZcjU3xvpri9m7dXIYbI17MN3XotC2ePuIeONg3R25Qs7kVKsx9y_qOQ2EZK), Yifei Liu*, **Yiquan Wu**\*, Yating Zhang, Changlong Sun, Weiming Lu, Fei Wu, Kun Kuang.

- ``EMNLP'22`` ["Towards Interactivity and Interpretability: A Rationale-based Legal Judgment Prediction Framework"](https://aclanthology.org/2022.emnlp-main.316.pdf), **Yiquan Wu**, Yifei Liu, Weiming Lu, Yating Zhang, Jun Feng, Changlong Sun, Fei Wu, Kun Kuang.

- ``ACL'22`` ["De-Bias for Generative Extraction in Unified NER Task"](https://aclanthology.org/2022.acl-long.59.pdf), Shuai Zhang, Yongliang Shen, Zeqi Tan, **Yiquan Wu**, Weiming Lu.

- ``CICAI'22`` ["Similar Case Based Prison Term Prediction"](https://link.springer.com/chapter/10.1007/978-3-031-20503-3_23), Siying Zhou, Yifei Liu, **Yiquan Wu**, Kun Kuang, Chunyan Zheng, Fei Wu.

- ``Artificial Intelligence and Law`` ["LK-IB: a hybrid framework with legal knowledge injection for compulsory measure prediction"](https://link.springer.com/article/10.1007/s10506-023-09362-x), Xiang Zhou, Qi Liu, **Yiquan Wu**, Qiangchao Chen, and Kun Kuang.

- ``EMNLP'20`` ["De-biased Court’s View Generation with Causality"](https://aclanthology.org/2020.emnlp-main.56/), **Yiquan Wu**, Kun Kuang, Yating Zhang, Xiaozhong Liu, Changlong Sun, Jun Xiao, Yueting Zhuang, Luo Si, Fei Wu.

- ``SIGIR'20-Workshop`` ["Automatic Text Revision with Application to Legal Documents"](https://legalai2020.github.io/file/wuyiquan.pdf), **Yiquan Wu**, Kun Kuang, Fei Wu.

# 📖 Educations
- *2019.06 - Present*, Ph.D., Zhejiang University, Hangzhou, China.

- *2023.12 - Present*, Visiting student, University of Innsbruck, Innsbruck, Austria.

- *2015.09 - 2019.06*, Undergraduate, Computer Science, Zhejiang University, Hangzhou, China.

- *2012.09 - 2015.06*, Yuyao High School, Ningbo, China.

# 🎖 Honors and Awards
- ``2019`` Zhejiang Province Excellent Graduate (Top 3%) 
- ``2023`` BOC Fundamental Subjects Scholarship (Top 1%)
- ``2017,2022`` Sports and Arts Scholarship (Top 1%)
- ``2016,2017,2018,2020,2021,2023`` Excellent Student of Zhejiang University (Top 8%) 
- ``2016,2017,2018`` Academic Scholarship (Top 20%) 

# 🏃 Sport Awards
<div align="center">
<img src='/images/basketball.png' alt="basketball" width="60%">
</div>

<!-- ![Image](../images/basketball.png "basketball") -->

- ``2019 - Present`` Captain of the Zhejiang University Men's Basketball Team.

- ``2019, 2020, 2021`` Recognized as an Outstanding Athlete by the Chinese University Basketball Association (CUBA).

- ``2021`` 🥈 Second Place in the Chinese University Basketball Association (CUBA).

- ``2016, 2018, 2019, 2020, 2022`` 🥇🥇🥇🥇🥇 First Place in the Zhejiang Province University Basketball Association (ZUBA).

- ``2019`` 🥇🥇 First Place in both the Men's 100 meters and Javelin throw at the school sports meeting



# 💻 Internships
- *2018.11 - Present*, [Damo Academy](https://damo.alibaba.com/), Hangzhou.

- *2018.06 - 2018.10*, [YiWise](https://www.yiwise.com/), Hangzhou.
