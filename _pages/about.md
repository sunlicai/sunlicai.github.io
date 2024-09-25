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

I am a postdoctoral researcher, collaborating with Prof. <a href="https://people.ucas.edu.cn/~taojianhua?language=en"> Guoying Zhao </a>, at <a href="https://www.oulu.fi/cmvs"> Center for Machine Vision and Signal Analysis (CMVS) </a>, University of Oulu, Finland. Prior to that, I received my PhD degree at the Institute of Automation, Chinese Academy of Sciences (CASIA) and University of Chinese Academy of Sciences (UCAS), supervised by Prof. <a href="https://people.ucas.edu.cn/~taojianhua?language=en"> Jianhua Tao </a>.
My research interest lies in the intersection of affective computing and deep learning, with a specific focus on multimodal learning and self-supervised learning. I have published several papers at the top international AI journals and conferences, such as Information Fusion, IEEE Trans. on Affective Computing, ACM MM, and ICASSP. 
I am also the winner of several international competitions in affective computing, such as MuSe and MEGC.
<a href='https://scholar.google.com/citations?user=7qo_cTcAAAAJ&hl=en&oi=ao'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fsunlicai%2Fsunlicai.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

Feel free to reach out if you’re interested in my work and want to explore potential collaborations.


# 📜 Research Area
<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td style="border: none;"> <font color="#0b5394"> Computer Vision </font>: <BR>&nbsp;&nbsp; Facial Expression Recognition; Micro-Expression Recognition; Audio-Visual Emotion Recognition; Multimodal Large Language Model </td>
    <td style="border: none;"> <font color="#0b5394"> Speech Signal Processing </font>: <BR>&nbsp;&nbsp; Speech Emotion Recognition </td>
  </tr>
  <tr style="border: none;">
    <td style="border: none;"> <font color="#0b5394"> Natural Language Processing </font>: <BR>&nbsp;&nbsp; Multimodal Sentiment Analysis; Emotion Recognition in Conversation; Large Language Model </td>
    <td style="border: none;"> <font color="#0b5394"> Self-supervised Learning </font>: <BR>&nbsp;&nbsp; Contrastive Learning; Masked Data Modeling </td>
  </tr>
</table>


# 🔥 News
- *2024.07*: &nbsp;🎉🎉 [SVFAP](https://arxiv.org/abs//2401.00416) is accepted by IEEE Trans. on Affective Computing.
- *2024.07*: &nbsp;🎉🎉 [EMT-DLFR](https://arxiv.org/abs/2208.07589) is selected as an [ESI Highly Cited Paper](https://www.webofscience.com/wos/woscc/full-record/WOS:001178971100010).
- *2024.03*: &nbsp;🎉🎉 [HiCMAE](https://arxiv.org/abs/2401.05698) and [GPT-4v with Emotion](https://arxiv.org/abs/2312.04293) are accepted by Information Fusion. 
- *2023.07*: &nbsp;🎉🎉 [MAE-DFER](https://arxiv.org/abs/2307.02227) is accepted by ACM MM 2023. 
- *2023.04*: &nbsp;🎉🎉 [EMT-DLFR](https://arxiv.org/abs/2208.07589) is accepted by IEEE Trans. on Affective Computing. 


# 📝 Publications 

\# Equal contribution, \* Corresponding author

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TAC 2024</div><img src='images/research/SVFAP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[SVFAP: Self-supervised Video Facial Affect Perceiver](https://arxiv.org/abs/2401.00416)

**Licai Sun**, Zheng Lian\#, Kexin Wang, Yu He, Mingyu Xu, Haiyang Sun, Bin Liu\#, Jianhua Tao\#

**IEEE Trans. on Affective Computing, 2024** \| [![](https://img.shields.io/github/stars/sunlicai/SVFAP?style=social&label=Code+Stars)](https://github.com/sunlicai/SVFAP)
- SVFAP seeks *large-scale self-supervised pre-training* for video facial affect analysis and achieves superior performance on *nine* datasets spanning three different tasks.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INFFUS 2024</div><img src='images/research/HiCMAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HiCMAE: Hierarchical Contrastive Masked Autoencoder for Self-Supervised Audio-Visual Emotion Recognition](https://arxiv.org/abs/2401.05698)

**Licai Sun**, Zheng Lian, Bin Liu\#, Jianhua Tao\#

**Information Fusion, 2024** \| [![](https://img.shields.io/github/stars/sunlicai/HiCMAE?style=social&label=Code+Stars)](https://github.com/sunlicai/HiCMAE)
- HiCMAE introduces a novel hierarchical contrastive masked autoencoder for self-supervised audio-visual emotion recognition (AVER) and achieves SOTA performance on *nine* popular AVER datasets.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INFFUS 2024</div><img src='images/research/GPT4V_Emotion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GPT-4V with Emotion: A Zero-shot Benchmark for Generalized Emotion Recognition](https://arxiv.org/abs/2312.04293)

Zheng Lian, **Licai Sun**, Haiyang Sun, Kang Chen, Zhuofan Wen, Hao Gu, Bin Liu\#, Jianhua Tao\#

**Information Fusion, 2024** \| [![](https://img.shields.io/github/stars/zeroQiaoba/gpt4v-emotion?style=social&label=Code+Stars)](https://github.com/zeroQiaoba/gpt4v-emotion)
- This paper quantitatively evaluates the emotional intelligence of GPT-4V on 21 benchmark datasets covering 6 emotion recognition tasks.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/research/MAE-DFER.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MAE-DFER: Efficient Masked Autoencoder for Self-supervised Dynamic Facial Expression Recognition](https://arxiv.org/abs/2307.02227)

**Licai Sun**, Zheng Lian, Bin Liu, Jianhua Tao

**ACM MM 2023** \| [![](https://img.shields.io/github/stars/sunlicai/MAE-DFER?style=social&label=Code+Stars)](https://github.com/sunlicai/MAE-DFER)<br>
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/mae-dfer-efficient-masked-autoencoder-for/dynamic-facial-expression-recognition-on-dfew)](https://paperswithcode.com/sota/dynamic-facial-expression-recognition-on-dfew?p=mae-dfer-efficient-masked-autoencoder-for)<br>
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/mae-dfer-efficient-masked-autoencoder-for/dynamic-facial-expression-recognition-on)](https://paperswithcode.com/sota/dynamic-facial-expression-recognition-on?p=mae-dfer-efficient-masked-autoencoder-for)<br>
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/mae-dfer-efficient-masked-autoencoder-for/dynamic-facial-expression-recognition-on-mafw)](https://paperswithcode.com/sota/dynamic-facial-expression-recognition-on-mafw?p=mae-dfer-efficient-masked-autoencoder-for)<br>
- MAE-DFER presents an early attempt to leverage *large-scale self-supervised pre-training* for dynamic facial expression recognition (DFER) and demonstrates great success on *six* popular DFER datasets.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TAC 2023</div><img src='images/research/EMT-DLFR_Architecture.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Efficient Multimodal Transformer with Dual-Level Feature Restoration for Robust Multimodal Sentiment Analysis](https://arxiv.org/abs/2208.07589)

**Licai Sun**, Zheng Lian, Bin Liu\#, Jianhua Tao\#

**IEEE Trans. on Affective Computing, 2023** \| [![](https://img.shields.io/github/stars/sunlicai/EMT-DLFR?style=social&label=Code+Stars)](https://github.com/sunlicai/EMT-DLFR)
- EMT-DLFR aims to address the *inefficiency* in fusing unaligned multimodal sequences and the *vulnerability* to missing data in real-world scenarios to achieve efficient and robust multimodal sentiment analysis.

</div>
</div>



  
- [Explainable Multimodal Emotion Reasoning](https://arxiv.org/abs/2306.15401), Zheng Lian, **Licai Sun**, Mingyu Xu, Haiyang Sun, Ke Xu, Zhuofan Wen, Shun Chen, Bin Liu, Jianhua Tao, arXiv 2023 \| [![](https://img.shields.io/github/stars/zeroQiaoba/AffectGPT?style=social&label=Code+Stars)](https://github.com/zeroQiaoba/AffectGPT)

- [Mer 2023: Multi-label learning, modality robustness, and semi-supervised learning](https://arxiv.org/abs/2304.08981), Zheng Lian, Haiyang Sun, **Licai Sun**, Kang Chen, Mngyu Xu, Kexin Wang, Ke Xu, Yu He, Ying Li, Jinming Zhao, Ye Liu, Bin Liu, Jiangyan Yi, Meng Wang, Erik Cambria, Guoying Zhao, Björn W Schuller, Jianhua Tao, **ACM MM 2023** \| [![](https://img.shields.io/github/stars/zeroQiaoba/MER2023-Baseline?style=social&label=Code+Stars)](https://github.com/zeroQiaoba/MER2023-Baseline)
  
- [GCNet: graph completion network for incomplete multimodal learning in conversation](https://ieeexplore.ieee.org/abstract/document/10008078), Zheng Lian, Lan Chen, **Licai Sun**, Bin Liu\#, Jianhua Tao\#, **TPAMI 2023**  \| [![](https://img.shields.io/github/stars/zeroQiaoba/GCNet?style=social&label=Code+Stars)](https://github.com/zeroQiaoba/GCNet)

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
- *2019.09 - 2024.06*, Ph.D. in Computer Applied Technology, Institute of Automation, Chinese Academy of Sciences and University of Chinese Academy Sciences, Beijing, China. 

- *2016.09 - 2019.06*, M.Sc. in Computer Technology, University of Chinese Academy Sciences, Beijing, China. 

- *2012.09 - 2016.06*, B.Eng. in Electronic and Information Technology, Beijing Forestry University, Beijing, China. 

# 💬 Professional Services
- Journal Reviewer: IEEE Trans. on Affective Computing, Speech Communication, Engineering Applications of Artificial Intelligence.
- Conference Reviewer: ACM MM (2024, 2023), ICASSP (2022), InterSpeech (2020).
- Program Committee: MER2023@ACM MM 2023 Grand Challenge and MRAC2023@ACM MM 2023 Workshop.



