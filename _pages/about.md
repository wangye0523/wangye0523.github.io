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

Ye Wang is an Associate Professor in the School of Artificial Intelligence at [Chongqing University of Posts and Telecommunications](https://english.cqupt.edu.cn/) (CQUPT). He received his Ph.D. in Computer Engineering from [Texas A&M University](https://engineering.tamu.edu/ce/index.html) and previously worked as a Research Scientist at [Samsung Research America](https://sra.samsung.com/).

His research develops **human-centered multimodal AI** systems that understand human intentions and emotions, align with human preferences, and reason from reliable evidence under uncertainty. His work spans affective computing, image aesthetics, multimodal generation, hallucination correction, long-tailed learning, and multimodal reasoning.

He has published in leading journals and conferences, including IEEE TIP, IEEE TAFFC, IEEE TKDE, IEEE TASLP, IEEE TCSVT, ICML, and ICLR. His work has received **ICML 2026 Spotlight (Top 2.2%)**, the **Best Student Paper Award at NCAA 2026**, the **Best Conference Paper Award at Brain Informatics 2024**, and a **Best Paper Candidate recognition at IEEE ISPCE-ASIA 2023**.

He has served as principal investigator for projects supported by the National Natural Science Foundation of China and provincial research programs. He is deeply committed to student mentorship. His students have received national innovation awards and major prizes in the Challenge Cup, RoboCom, and the MCM/ICM. His graduates have joined leading technology companies such as Tencent, ByteDance, and Xiaohongshu, or continued their studies at universities including the University of Michigan and Zhejiang University.

[Google Scholar](https://scholar.google.com/citations?user=UNxKb0cAAAAJ&hl=en) · [DBLP](https://dblp.org/pid/44/6292-6.html) · [ORCID](https://orcid.org/0000-0002-1748-6890) · [Chinese Homepage](https://faculty.cqupt.edu.cn/wangye/zh_CN/index.htm) · [Curriculum Vitae (August 2026)](https://wangye0523.github.io/Ye_Wang_CV.pdf)


# Employment

- **Associate Professor**, School of Artificial Intelligence, Chongqing University of Posts and Telecommunications, 2026–present.
- **Assistant Professor**, School of Computer Science and Technology, Chongqing University of Posts and Telecommunications, 2020–2025.
- **Project Manager (on secondment)**, China Scholarship Council, 2020–2021.
- **Research Scientist**, Samsung Research America, 2019.

# Education

- **Ph.D. in Computer Engineering**, Texas A&M University, 2014–2019.
- **M.S. in Electrical Engineering**, The University of Texas at Dallas, 2012–2014.
- **B.Eng. in Microelectronics**, Chongqing University of Posts and Telecommunications, 2007–2011.

# Research

My research studies how AI can comprehensively understand people, reflect diverse human judgments, and remain reliable when evidence is uncertain. I pursue this question through three connected directions:

- **Human Understanding** — modeling emotions, preferences, human attributes and activities from multimodal data ([J12](#J12), [J5](#J5), [J4](#J4), [C7](#C7)).
- **Human–AI Alignment** — aligning model learning and generation with human preferences, cognitive structures, and multiple criteria ([J12](#J12), [J2](#J2), [C7](#C7)).
- **Evidence-Grounded Reasoning** — improving reliability under hallucinations, missing evidence, uncertainty, distribution shifts, and long-tailed data ([J11](#J11), [J10](#J10), [J9](#J9), [J8](#J8), [C6](#C6)).

# Honors and Awards

- **2026** — Spotlight Paper, International Conference on Machine Learning (ICML), Top 2.2% ([C7](#C7)).
- **2026** — ICML 2026 Gold Reviewer.
- **2026** — Best Student Paper Award, International Conference on Neural Computing for Advanced Applications (NCAA) ([C6](#C6)).
- **2024** — Best Conference Paper, International Conference on Brain Informatics ([C4](#C4)).
- **2023** — Best Paper Candidate, IEEE ISPCE-ASIA ([C3](#C3)).

# Research Funding

**Principal Investigator**

- **2024–2026:** National Natural Science Foundation of China, Young Scientists Fund (No. 62306056).
- **2022–2023:** Chongqing Returned Overseas Scholars Innovation and Entrepreneurship Support Program.
- **2021–2024:** Science and Technology Research Program of Chongqing Municipal Education Commission (No. KJQN202100629).

# News

- **2026.08:** One paper was accepted by IEEE Transactions on Knowledge and Data Engineering (TKDE). EnDist corrects distribution shifts in explanatory subgraphs for more reliable GNN explanations. [[paper](https://ieeexplore.ieee.org/document/11627428)] [[code](https://github.com/hegy1024/EnDist)]
- **2026.07:** Our paper received the Best Student Paper Award at NCAA 2026. The work studies natural-language-guided generation of rare and high-risk scenarios for autonomous-driving safety evaluation. [[conference](https://aaci.org.hk/ncaa2026/)]
- **2026.05:** Our paper was accepted as an ICML 2026 Spotlight paper (Top 2.2%). AGREE reveals and mitigates gradient conflict among aesthetic attributes in image aesthetic assessment. [[paper](https://openreview.net/pdf?id=GrIs035ec3)] [[code](https://github.com/Dahat364/AGREE)]
- **2026.04:** One paper was accepted by IEEE Transactions on Image Processing (TIP). HCFace uses hierarchical causal learning to model dependencies among age-related facial attributes. [[paper](https://ieeexplore.ieee.org/document/11511429)] [[code](https://github.com/SE-hash/HCFace)]
- **2026.03:** One paper was accepted by IEEE Transactions on Audio, Speech, and Language Processing (TASLP). UME addresses challenging-tailed sequence learning through expert specialization and uncertainty fusion. [[paper](https://ieeexplore.ieee.org/abstract/document/11447416/)] [[code](https://github.com/CQUPTWZX/Multi-experts)]
- **2026.01:** One paper was accepted at ICLR 2026. LouisKV retrieves KV cache at semantic boundaries and accelerates long-sequence reasoning by up to 4.7 times. [[paper](https://openreview.net/forum?id=6RJ8fZwm4P)]

<details markdown="1">
<summary><strong>Earlier news</strong></summary>

- **2025.09:** One paper was accepted by IEEE Transactions on Circuits and Systems for Video Technology. The work rectifies object hallucinations and restores missing content in LLM-based video captioning. [[paper](https://ieeexplore.ieee.org/document/11177574)] [[code](https://github.com/no-zjc/VEaCap)]

- **2025.09:** One paper was accepted by Information Fusion. GCFA improves long-tailed medical text classification through generative class features and agent attention. [[paper](https://www.sciencedirect.com/science/article/abs/pii/S1566253525007110)] [[code](https://github.com/WQYwqy123456/GCFA-123)]

- **2025.09:** One paper was accepted by IEEE Transactions on Consumer Electronics. CRMED performs continuous entity reasoning for multi-turn medical dialogue generation. [[paper](https://ieeexplore.ieee.org/document/11123515)] [[code](https://github.com/xinyang183/CRMED)]

- **2025.08:** One paper was accepted by IEEE Journal of Biomedical and Health Informatics. The work models Chinese character structures and boundaries for clinical named entity recognition. [[paper](https://ieeexplore.ieee.org/document/11112630/authors)] [[code](https://github.com/jl7650/CCS)]

- **2025.02:** One paper was accepted by Information Processing & Management. The work uses multimodal large language models for spatio-temporal action detection in football. [[paper](https://doi.org/10.1016/j.ipm.2025.104094)] [[code](https://github.com/LeopoldSimmons/HCBS)]

- **2024.12:** Our paper received the Best Conference Paper Award at the 17th International Conference on Brain Informatics. [[paper](https://rdcu.be/edXQi)]

- **2024.09:** One paper was accepted by IEEE Transactions on Affective Computing. DEDNet models inter- and intra-speaker dependencies for multimodal emotion recognition. [[paper](https://ieeexplore.ieee.org/document/10680310)] [[code](https://github.com/ZhangW1212)]

- **2024.08:** One paper was accepted by Artificial Intelligence Review. The work models interactions between Chinese characters and lexical information for Chinese named entity recognition. [[paper](https://link.springer.com/article/10.1007/s10462-024-10891-3)] [[code](https://github.com/wangye0523/The-interactive-fusion-of-characters-and-lexical-information-for-Chinese-named-entity-recognition)]

- **2024.08:** One paper was accepted by Neural Computing and Applications. SMOT reduces cross-modal distribution gaps through self-supervised modal optimization for image captioning. [[paper](https://link.springer.com/article/10.1007/s00521-024-10211-4)]

- **2024.01:** One paper was accepted by IEEE Transactions on Consumer Electronics. KDDGAN enables explicit and independent manipulation of facial attributes through knowledge-guided feature disentanglement. [[paper](https://ieeexplore.ieee.org/document/10374272)]

- **2023.11:** Our paper was selected as a Best Paper Candidate at IEEE ISPCE-ASIA 2023. [[conference](https://dl2link.com/ISPCE-AS2023/index.html)]

- **2023.05:** Interviewed by *People's Education* (《人民教育》). [[link](https://news.cqnews.net/1/detail/1109608325812756480/web/content_1109608325812756480.html)]

- **2023.03:** Interviewed by *Chongqing Daily* about ChatGPT. [[article](https://www.cqrb.cn/topics/2022xwhkt/hy/)] [[video](https://v.douyin.com/i8Nre2Cx/)]

</details>

# Publications

## Journal Papers

<span id="J12"></span>**[J12]** **Ye Wang**, Pan Sun, Xuyang Zhou, Lifeng Shen, Jiaxu Leng, Guoyin Wang, and Hong Yu*. **Hierarchical Causal Learning for Face Age Synthesis.** *IEEE Transactions on Image Processing (TIP)*, 2026. [[paper](https://ieeexplore.ieee.org/document/11511429)] [[code](https://github.com/SE-hash/HCFace)]

<span id="J11"></span>**[J11]** Guangyong He, Li Liu*, Youmin Zhang, **Ye Wang**, Qun Liu, and Guoyin Wang. **Enhancing Graph Neural Network Explainers Using a Distribution Shift Consistency-Guided Generator.** *IEEE Transactions on Knowledge and Data Engineering (TKDE)*, 2026. [[paper](https://ieeexplore.ieee.org/document/11627428)] [[code](https://github.com/hegy1024/EnDist)]

<span id="J10"></span>**[J10]** **Ye Wang**, Zixuan Wu, Lifeng Shen, Jiang Xie, Xiaoling Wang, Hong Yu*, and Guoyin Wang. **Mastering the Minority: An Uncertainty-Guided Multi-Expert Framework for Challenging-Tailed Sequence Learning.** *IEEE Transactions on Audio, Speech, and Language Processing (TASLP)*, 2026. [[paper](https://ieeexplore.ieee.org/abstract/document/11447416/)] [[code](https://github.com/CQUPTWZX/Multi-experts)]

<span id="J9"></span>**[J9]** **Ye Wang**, Jiancheng Zhou, Qun Liu*, Feng Hu, and Guoyin Wang. **Visual Evidence-Aware for Object Hallucinations Rectification in LLM-Based Video Captioning.** *IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)*, 2026. [[paper](https://ieeexplore.ieee.org/document/11177574)] [[code](https://github.com/no-zjc/VEaCap)]

<span id="J8"></span>**[J8]** **Ye Wang**, Qingyan Wang, Hong Yu, Jiang Xie, Feng Hu, Xiaoling Wang, and Dajiang Lei*. **GCFA: Generative Class Feature Fusion with Agent Attention for Medical Text Classification.** *Information Fusion*, 2026. [[paper](https://www.sciencedirect.com/science/article/abs/pii/S1566253525007110)] [[code](https://github.com/WQYwqy123456/GCFA-123)]

<span id="J7"></span>**[J7]** **Ye Wang**, Xinyang Li, Hong Yu, Feng Hu, Guoyin Wang*, and Dajiang Lei*. **Continuous Entity Reasoning for Multi-Turn Medical Dialogue Generation.** *IEEE Transactions on Consumer Electronics*, 2025. [[paper](https://ieeexplore.ieee.org/document/11123515)] [[code](https://github.com/xinyang183/CRMED)]

<span id="J6"></span>**[J6]** **Ye Wang**, Qi Wei, Hong Yu, Guoyin Wang, Chunmeng Shi, and Dajiang Lei*. **Cross-Interaction of Chinese Character Structures and Boundary Features for Improving Clinical Named Entity Recognition.** *IEEE Journal of Biomedical and Health Informatics (J-BHI)*, 2025. [[paper](https://ieeexplore.ieee.org/document/11112630/authors)] [[code](https://github.com/jl7650/CCS)]

<span id="J5"></span>**[J5]** Xuyang Zhou, **Ye Wang***, Fei Tao, Hong Yu, and Qun Liu. **Hierarchical Chat-Based Strategies with MLLMs for Spatio-Temporal Action Detection.** *Information Processing & Management*, 2025. [[paper](https://doi.org/10.1016/j.ipm.2025.104094)] [[code](https://github.com/LeopoldSimmons/HCBS)]

<span id="J4"></span>**[J4]** **Ye Wang**, Wei Zhang, Ke Liu*, Wei Wu, Feng Hu, Hong Yu, and Guoyin Wang. **Dynamic Emotion-Dependent Network with Relational Subgraph Interaction for Multimodal Emotion Recognition.** *IEEE Transactions on Affective Computing*, 2025. [[paper](https://ieeexplore.ieee.org/document/10680310)] [[code](https://github.com/ZhangW1212)]

<span id="J3"></span>**[J3]** **Ye Wang**, Zheng Wang, Hong Yu, Guoyin Wang*, and Dajiang Lei*. **The Interactive Fusion of Characters and Lexical Information for Chinese Named Entity Recognition.** *Artificial Intelligence Review*, 2024. [[paper](https://link.springer.com/article/10.1007/s10462-024-10891-3)] [[code](https://github.com/wangye0523/The-interactive-fusion-of-characters-and-lexical-information-for-Chinese-named-entity-recognition)]

<span id="J2"></span>**[J2]** **Ye Wang**, Qianmengke Zhao, Qun Liu*, Guoyin Wang, Hong Yu, Li Liu, and Jiaxu Leng. **KDDGAN: Knowledge-Guided Explicit Feature Disentanglement for Facial Attribute Editing.** *IEEE Transactions on Consumer Electronics*, 2024. [[paper](https://ieeexplore.ieee.org/document/10374272)]

<span id="J1"></span>**[J1]** **Ye Wang**, Xinxiang Zhang, Mi Lu, Han Wang, and Yoonsuck Choe. **Attention Augmentation with Multi-Residual in Bidirectional LSTM.** *Neurocomputing*, 2020.

## Conference Papers

<span id="C7"></span>**[C7]** **Ye Wang**, Maocai Dai, Jiang Xie, Xiuli Bi, Fei Tao, Xiao Li, and Hong Yu. **When Attributes Disagree: Gradient Conflict in Image Aesthetic Assessment.** *International Conference on Machine Learning (ICML)*, 2026. **Spotlight, Top 2.2%.** [[paper](https://openreview.net/pdf?id=GrIs035ec3)] [[code](https://github.com/Dahat364/AGREE)]

<span id="C6"></span>**[C6]** Tingting Lei, Yifan Zhu, Runxi Zhang, Feng Hu, Hong Yu, and **Ye Wang**. **NLG-Gen: Natural Language-Guided Generation of Long-Tail Critical Scenarios for Autonomous Driving.** *International Conference on Neural Computing for Advanced Applications (NCAA)*, 2026. **Best Student Paper Award.** [[conference](https://aaci.org.hk/ncaa2026/)]

<span id="C5"></span>**[C5]** Wenbo Wu, Qingyi Si, Xiurui Pan, **Ye Wang**, and Jie Zhang. **LouisKV: Efficient KV Cache Retrieval for Long Input-Output Sequences.** *International Conference on Learning Representations (ICLR)*, 2026. [[paper](https://openreview.net/forum?id=6RJ8fZwm4P)]

<span id="C4"></span>**[C4]** Yan Xian, Hong Yu, **Ye Wang**, and Guoyin Wang. **A Novel Class Incremental Learning Method via Multi-Granularity Balance Inspired by Human Granular Cognition Mechanism.** *International Conference on Brain Informatics*, 2024. **Best Conference Paper.** [[paper](https://rdcu.be/edXQi)]

<span id="C3"></span>**[C3]** Xinqiang Jiang, Yingnan Geng, Yinzhou Xiong, Fei Tao, and **Ye Wang**. **A Privacy-Aware Framework for Assessing and Recommending Short Video Advertisement.** *IEEE International Symposium on Product Compliance Engineering - Asia (ISPCE-ASIA)*, 2023. **Best Paper Candidate.** [[conference](https://dl2link.com/ISPCE-AS2023/index.html)]

<span id="C2"></span>**[C2]** Jiaxu Leng and **Ye Wang**. **RCNet: Recurrent Collaboration Network Guided by Facial Priors for Face Super-Resolution.** *IEEE International Conference on Multimedia and Expo (ICME)*, 2022.

<span id="C1"></span>**[C1]** **Ye Wang**, Han Wang, Xinxiang Zhang, Theodora Chaspari, Yoonsuck Choe, and Mi Lu. **An Attention-Aware Bidirectional Multi-Residual Recurrent Neural Network: A Study on Short-Term Text Classification.** *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*, 2019.

For a complete and up-to-date publication list, please visit [Google Scholar](https://scholar.google.com/citations?user=UNxKb0cAAAAJ&hl=en), [DBLP](https://dblp.org/pid/44/6292-6.html), or [CV](https://wangye0523.github.io/Ye_Wang_CV.pdf).

# Teaching

## Teaching Honors

- **2025:** Course Leader, *Data Structures for International Students*, designated as a Chongqing Municipal First-Class Undergraduate Course.
- **2024:** Award for Outstanding Contribution to International Student Education in Chongqing.
- **2023:** Outstanding Advisor, National Finals of the RoboCom Robot Developer Competition.

## Courses at CQUPT

- **Natural Language Processing**, Fall 2024 and Fall 2025.
- **AI Literacy and Practice: From Fundamentals to DeepSeek Applications**, Spring 2025 and Fall 2025.
- **Algorithm Analysis and Design for International Students**, Fall 2025.
- **Data Structures for International Students**, Spring 2023 and Spring 2025.
- **Fundamentals of Data Mining**, Spring 2022 and Fall 2024.
- **Machine Learning Models and Algorithms**, Fall 2022.
- **Principles of Artificial Intelligence**, Fall 2020.
- **Data Mining**, Fall 2022.
- **Big Data Analytics and Mining**, Fall 2023 and Fall 2024.

## Teaching Experience at Texas A&M University

- **Teaching Assistant, ECEN 651: Microprogrammed Control of Digital Systems**, Fall 2014 and Spring 2015.
- **Teaching Assistant, ECEN 350: Computer Architecture**, Spring 2015, Fall 2017, Fall 2018, and Spring 2019.
- **Teaching Assistant, ECEN 214: Electrical Circuit Theory**, Spring 2016.

# Research Team

## Ph.D. Students

- [Xuyang Zhou](https://leopoldsimmons.github.io/) — direct-entry Ph.D. student; multimodal football understanding and reasoning ([J5](#J5)).
- [Zixuan Wu](https://github.com/CQUPTWZX) — uncertainty-aware learning and autonomous-driving reasoning ([J10](#J10)).

## M.S. Students

- [Maocai Dai](https://github.com/Dahat364) — image aesthetic assessment and human–AI preference alignment ([C7](#C7)).
- Hongbing Chen
- Jie Yang
- Haokun Ren
- Yahui Lei
- Siyi Liu
- Gezhang Cao
- Jingying Peng
- Jun Hu
- Hao You
- Tingting Lei — long-tail critical scenario generation for autonomous driving ([C6](#C6)).
- Jie Tang
- Jiayi Qiu
- Haiyan She
- Zhiyu Zhou
- Qingbin Su
- Mingyue Wang
- Jinhang Yao

## Undergraduate Students

- Xinzhe Wang
- Yi Huang
- Ruizhe Kang

# Alumni and Former Advisees

## Former M.S. Students

- **Xiaolin Zhou** (2026) — Project Manager, China Tower; research on multimodal sarcasm understanding.
- **[Pan Sun](https://github.com/SE-hash/HCFace)** (2026) — Big Data Engineer, Bambu Lab; research on causal modeling for face age synthesis ([J12](#J12)).
- **[Zixuan Wu](https://github.com/CQUPTWZX)** (2025) — Ph.D. student at CQUPT; research on uncertainty-aware sequence learning ([J10](#J10)).
- **[Wei Zhang](https://github.com/ZhangW1212)** (2025) — Ph.D. student at South China University of Technology; research on multimodal emotion understanding ([J4](#J4)).
- **[Yongliang Yang](https://asenniu.github.io/)** (2025) — Software Engineer, Tencent PCG.
- **[Xinyang Li](https://github.com/xinyang183/CRMED)** (2025) — Software Engineer, Changan Automobile; research on multi-turn medical dialogue generation ([J7](#J7)).
- **[Qingyan Wang](https://github.com/WQYwqy123456/GCFA-123)** (2025) — Algorithm Engineer, Zhihu; research on medical text classification ([J8](#J8)).
- **[Jiancheng Zhou](https://github.com/no-zjc/VEaCap)** (2025) — Software Engineer, Mashang Consumer Finance; research on hallucination rectification in video captioning ([J9](#J9)).
- **Daitianxia Li** (2024) — Lecturer, Chongqing City Management College; research on self-supervised and multi-granularity image captioning.
- **[Qi Wei](https://github.com/jl7650/CCS)** (2024) — IT Consulting Engineer, Guangdong Telecom Planning and Design Institute; research on clinical named entity recognition ([J6](#J6)).
- **Zheng Wang** (2024) — Software Engineer, Enmotech; research on character- and lexical-level Chinese named entity recognition ([J3](#J3)).
- **Jingbo Liao** (2023) — Software Engineer, Alibaba; research on interpretable and diverse open-domain dialogue generation.
- **Qianmengke Zhao** (2023) — Software Engineer, Chongqing Rural Commercial Bank; research on knowledge-guided facial attribute editing ([J2](#J2)).
- **Wenkang Lu** (2023) — Algorithm Engineer, Changan Technology.

## Former Undergraduate Advisees

- **Jie Wei** (2026) — M.S. student at City University of Hong Kong.
- **Wenqi Dong** (2026) — M.S. student at the University of Hong Kong.
- **[Xuyang Zhou](https://leopoldsimmons.github.io/)** (2025) — direct-entry Ph.D. student at CQUPT; research on spatio-temporal action understanding ([J5](#J5)).
- **Zhuoyi Yu** (2025) — M.S. student at the University of Electronic Science and Technology of China.
- **Tingting Lei** (2025) — M.S. student at CQUPT; research on long-tail critical scenario generation ([C6](#C6)).
- **[Guanmeng Xian](https://gmxian.github.io/)** (2024) — M.S. student at Sichuan University.
- **[Maocai Dai](https://github.com/Dahat364)** (2024) — M.S. student at CQUPT; research on conflict-aware image aesthetic assessment ([C7](#C7)).
- **[Qi Cheng](https://www.linkedin.com/in/qi-cheng-4365a9249/)** (2023) — M.S. student at the University of Michigan, Ann Arbor.
- **Dongyu Xie** (2023) — M.S. student at the University of Electronic Science and Technology of China.
- **Xinyi Gao** (2023) — M.S. student at the University of Rochester.

## Selected Student Awards

- **2025:** National Third Prize, 19th Challenge Cup National College Students' Extracurricular Academic Science and Technology Contest.
- **2025:** CQUPT Outstanding Undergraduate Thesis Awards.
- **2024:** National Third Prize, RoboCom Robot Developer Competition.
- **2024:** Outstanding Undergraduate Thesis of Chongqing.
- **2024:** National Undergraduate Innovation and Entrepreneurship Training Program, rated Outstanding upon completion.
- **2023:** Second Prize, Mathematical Contest in Modeling.
- **2023:** CQUPT Outstanding Undergraduate Thesis Award.
- **2023:** National First Prize, Math China Mathematical Modeling Competition.
- **2023:** National Second Prize, China College Students' Service Outsourcing Innovation and Entrepreneurship Competition.

# Collaborators

- [Guoyin Wang](https://faculty.cqupt.edu.cn/wanggy/zh_CN/index.htm), Chongqing University of Posts and Telecommunications, China.
- [Hong Yu](https://faculty.cqupt.edu.cn/yuhong/zh_CN/index.htm), Chongqing University of Posts and Telecommunications, China.
- [Qun Liu](https://faculty.cqupt.edu.cn/liuqun/zh_CN/index.htm), Chongqing University of Posts and Telecommunications, China.
- [Li Liu](https://scholar.google.com/citations?user=uoNJ6goAAAAJ&hl=zh-CN), Chongqing University of Posts and Telecommunications, China.
- [Jiaxu Leng](https://scholar.google.com/citations?user=KpX-CCcAAAAJ&hl=zh-CN), Chongqing University of Posts and Telecommunications, China.
- [William K. Cheung](https://scholar.google.com/citations?user=e42JkYIAAAAJ&hl=zh-CN), Hong Kong Baptist University, Hong Kong SAR, China.
- [Lifeng Shen](https://www.lshenae.cn/), Hong Kong University of Science and Technology, Hong Kong SAR, China.
- [Mi Lu](https://scholar.google.com/citations?user=crjEvpQAAAAJ&hl=en), Texas A&M University, United States.
- [Yoonsuck Choe](https://scholar.google.com/citations?user=nFb_T4wAAAAJ&hl=en), Texas A&M University, United States.
- [Han Wang](https://scholar.google.com/citations?user=8MS58WkAAAAJ&hl=en), Samsung Research America, United States.
- [Fei Tao](https://scholar.google.com/citations?hl=zh-CN&user=KhWMky4AAAAJ), Amazon, United States.
- [Xinxiang Zhang](https://scholar.google.com/citations?user=OcCQAs4AAAAJ&hl=zh-CN), Southern Methodist University, United States.
- [Xiao Li](https://scholar.google.com/citations?user=y9iRoggAAAAJ&hl=en), University of Oxford, United Kingdom.

# Academic Service

## Editorial Service

- **Young Editorial Board Member**, *CAAI Transactions on Intelligent Systems*.

## Conference Organization

- **Session Chair**, Mesoscopic Cognitive Machine Learning Workshop, International Joint Conference on Rough Sets (IJCRS), 2026.
- **Competition Chair**, International Conference on Neural Computing for Advanced Applications (NCAA), 2023–2026.
- **Web Chair**, IEEE International Conference on Medical Artificial Intelligence (MedAI), 2024.

## Conference Reviewer and Program Committee

- **International Conference on Machine Learning (ICML):** 2026.
- **AAAI Conference on Artificial Intelligence (AAAI):** 2026.
- **Conference on Language Modeling (COLM):** 2025, 2026.
- **ACM International Conference on Multimedia (ACM MM):** 2026.
- **ACL Rolling Review**: 2025-2026.
- **European Conference on Artificial Intelligence (ECAI):** 2025.
- **International Joint Conference on Artificial Intelligence:** 2025.

## Journal Reviewer
- *IEEE Transactions on Image Processing (TIP)*
- *IEEE Transactions on Audio, Speech, and Language Processing (TASLP)*
- *IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)*
- *IEEE Transactions on Knowledge and Data Engineering (TKDE)*
- *IEEE Transactions on Multimedia (TMM)*

## Professional Society Service

- **Committee Member**, CAAI Technical Committee on Granular Computing and Knowledge Discovery.
- **Corresponding Member**, CAAI Technical Committee on Artificial Intelligence Foundations.

# Invited Talks, Lectures, and Media

## Invited Talks and Lectures

- **2025:** *Visual Intelligence through Multi-Granularity Cognitive Computing*, CCF@U (No. 1323), Sichuan University, Chengdu. [[link](https://www.ccf.org.cn/Chapters/Student_Chapters/SCU/hyhdzxdt/2025-10-30/850684.shtml)]
- **2023:** *Generative Modeling through Latent-Space Disentanglement*, Doctoral Forum, Yan'an University. [[link](https://yau.edu.cn/info/1122/67356.htm)]
- **2023:** Summer Training Program on Machine Learning, National Center for Applied Mathematics, Chongqing. [[link](https://cqcam.cqnu.edu.cn/info/2018/3631.htm)]
- **2023:** *Generative AI in Education: Opportunities and Challenges*, Faculty Salon, Chongqing Nankai Secondary School. [[link](https://mp.weixin.qq.com/s/DF7obFf5G6xy2vjqfyu7qg)]

## Media Interviews

- **2023:** Interviewed by *People's Education* (《人民教育》). [[link](https://news.cqnews.net/1/detail/1109608325812756480/web/content_1109608325812756480.html)]
- **2023:** *ChatGPT Is Here: Should We Be Anxious?*, interview with *Chongqing Daily*. [[article](https://www.cqrb.cn/topics/2022xwhkt/hy/)] [[video](https://v.douyin.com/i8Nre2Cx/)]
