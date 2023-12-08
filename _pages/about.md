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

I am a Ph.D. student at the University of Chinese Academy of Sciences (UCAS) and Institute of Automation, Chinese Academy of Sciences (CASIA), supervised by Prof. <a href="https://scholar.google.com/citations?user=781jbHMAAAAJ&hl=en&oi=ao"> Jianhua Tao </a>.
My research interests lie in affective computing and deep learning, with a specific focus on multimodal learning and self-supervised learning. I have published papers at the top international AI journals and conferences, such as IEEE Trans. on Affective Computing, ACM MM, and ICASSP. 
I am also the winner of several international competitions in affective computing, such as MuSe and MEGC.
<a href='https://scholar.google.com/citations?user=7qo_cTcAAAAJ&hl=en&oi=ao'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fsunlicai%2Fsunlicai.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

Feel free to reach out if you’re interested in my work and want to explore potential collaborations.

# 🔥 News
- *2023.07*: &nbsp;🎉🎉 MAE-DFER is accepted by ACM MM 2023. 
- *2023.04*: &nbsp;🎉🎉 EMT-DLFR is accepted by TAC. 


# 📝 Publications 

\* Equal contribution, \# Corresponding author
 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/research/MAE-DFER.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MAE-DFER: Efficient Masked Autoencoder for Self-supervised Dynamic Facial Expression Recognition](https://arxiv.org/abs/2307.02227)

**Licai Sun**, Zheng Lian, Bin Liu, Jianhua Tao

**ACM MM 2023**, <a href="https://github.com/sunlicai/MAE-DFER"> Code </a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- MAE-DFER presents an early attempt to leverage *large-scale self-supervised pretraining* for dynamic facial expression recognition (DFER) and demonstrate great success on *six* popular DFER datasets.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TAC</div><img src='images/research/EMT-DLFR_Architecture.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Efficient Multimodal Transformer with Dual-Level Feature Restoration for Robust Multimodal Sentiment Analysis](https://arxiv.org/abs/2208.07589)

**Licai Sun**, Zheng Lian, Bin Liu, Jianhua Tao

**IEEE Trans. on Affective Computing**, <a href="https://github.com/sunlicai/EMT-DLFR"> Code </a>
- EMT-DLFR aims to address the model *inefficiency* in multimodal fusion and *vulnerability* to missing modality features to achieve efficient and  robust multimodal sentiment analysis.

</div>
</div>


- [Multimodal Cross- and Self-Attention Network for Speech Emotion Recognition](https://ieeexplore.ieee.org/abstract/document/9414654), **Licai Sun**, Bin Liu, Jianhua Tao, Zheng Lian, **ICASSP 2021**

- [Multimodal Temporal Attention in Sentiment Analysis](https://dl.acm.org/doi/abs/10.1145/3551876.3554811), Yu He\*, **Licai Sun**\*, Zheng Lian, Bin Liu, Jianhua Tao, Meng Wang, Yuan Cheng, **MuSe 2022**

- [Multimodal emotion recognition and sentiment analysis via attention enhanced recurrent model](https://dl.acm.org/doi/abs/10.1145/3475957.3484456), **Licai Sun**\*, Mingyu Xu\*, Zheng Lian, Bin Liu, Jianhua Tao, Meng Wang, Yuan Cheng, **MuSe 2021**

- [Multi-modal continuous dimensional emotion recognition using recurrent neural network and self-attention mechanism](https://dl.acm.org/doi/abs/10.1145/3423327.3423672), **Licai Sun**\*, Zheng Lian\*, Bin Liu, Jianhua Tao, Mingyue Niu, **MuSe 2020**

# 🎖 Honors and Awards
- *2023.10*: &nbsp;🎉🎉 [Winner](https://megc2023.github.io/challenge.html) of Micro-Expression and Marco-Expression Spotting Task at MEGC 2023 in ACM MM 2023.
- *2022.10*: &nbsp;🎉🎉 [The MuSe-Stress 2022 Multimodal Sentiment Analysis Challenge Prize](https://sites.google.com/view/muse2022/challenge/winners) at MuSe 2022 in ACM MM 2022. 
- *2021.10*: &nbsp;🎉🎉 [The MuSe-Wilder 2021 Multimodal Sentiment Analysis Challenge Prize](https://sites.google.com/view/muse-2021/challenge/winners) at MuSe 2021 in ACM MM 2021. 
- *2021.10*: &nbsp;🎉🎉 [The MuSe-Sent 2021 Multimodal Sentiment Analysis Challenge Prize](https://sites.google.com/view/muse-2021/challenge/winners) at MuSe 2021 in ACM MM 2021.
- *2021.10*: &nbsp;🎉🎉 [The MuSe-Physio 2021 Multimodal Sentiment Analysis Challenge Prize](https://sites.google.com/view/muse-2021/challenge/winners) at MuSe 2021 in ACM MM 2021. 
- *2020.10*: &nbsp;🎉🎉 [The 2020 Multimodal Sentiment in-the-Wild Challenge Prize](https://sites.google.com/view/muse2020/challenge/baselines-winner) at MuSe 2020 in ACM MM 2020.

<!--
- *2022.10*: &nbsp;🎉🎉 [Winner](https://sites.google.com/view/muse2022/challenge/winners) of MuSe-Stress sub-challenge at MuSe 2022 in ACM MM 2022. 
- *2021.10*: &nbsp;🎉🎉 [Winners](https://sites.google.com/view/muse-2021/challenge/winners) of MuSe-Wilder & MuSe-Sent & MuSe-Physio sub-challenges at MuSe 2021 in ACM MM 2021. 
- *2020.10*: &nbsp;🎉🎉 [Winner](https://sites.google.com/view/muse2020/challenge/baselines-winner) of MuSe-Wild sub-challenge at MuSe 2020 in ACM MM 2020.
-->

# 📖 Educations
- *2019.09 - now*, Ph.D. in Computer Application Technology, University of Chinese Academy Sciences \& Institute of Automation, Chinese Academy of Sciences, Beijing, China. 

- *2016.09 - 2019.06*, M.Sc. in Computer Technology, University of Chinese Academy Sciences, Beijing, China. 

- *2012.09 - 2016.06*, B.Eng. in Electronic and Information Technology, Beijing Forestry University, Beijing, China. 



