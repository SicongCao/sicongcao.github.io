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

I work at [Research in Software and Security (RiSS) Group](http://riss.yzu.edu.cn/) <img src='./images/Riss_LOGO.jpg' style='width: 3em;'> as a PhD candidate at Yangzhou University now, supervised by Prof. Xiaobing Sun. Our group and I are open to collaboration and communication. If you want to share awesome ideas, feel free to contact me.

My research interest includes Software Engineering (SE) and Deep Learning (DL). I have published 6 papers <a href='https://scholar.google.com/citations?user=c-vPF2gAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FSicongCao%2Fsicongcao.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international SE conferences (e.g., ICSE, QRS) and journals (e.g., IST, ESE).


# 🔥 News
- *2022.12*: &nbsp;🎉🎉 One paper is accepted by the **Technical track of ICSE 2023**!
- *2021.12*: &nbsp;🎉🎉 One paper is accepted by the **Technical track of ICSE 2022**!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2019</div><img src='images/fs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FastSpeech: Fast, Robust and Controllable Text to Speech](https://papers.nips.cc/paper/8580-fastspeech-fast-robust-and-controllable-text-to-speech.pdf) \\
**Yi Ren**, Yangjun Ruan, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu

[**Project**](https://speechresearch.github.io/fastspeech/) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- FastSpeech is the first fully parallel end-to-end speech synthesis model.
- **Academic Impact**: This work is included by many famous speech synthesis open-source projects, such as [ESPNet ![](https://img.shields.io/github/stars/espnet/espnet?style=social)](https://github.com/espnet/espnet). Our work are promoted by more than 20 media and forums, such as [机器之心](https://mp.weixin.qq.com/s/UkFadiUBy-Ymn-zhJ95JcQ)、[InfoQ](https://www.infoq.cn/article/tvy7hnin8bjvlm6g0myu).
- **Industry Impact**: FastSpeech has been deployed in [Microsoft Azure TTS service](https://techcommunity.microsoft.com/t5/azure-ai/neural-text-to-speech-extends-support-to-15-more-languages-with/ba-p/1505911) and supports 49 more languages with state-of-the-art AI quality. It was also shown as a text-to-speech system acceleration example in [NVIDIA GTC2020](https://resources.nvidia.com/events/GTC2020s21420).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2021</div><img src='images/fs2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FastSpeech 2: Fast and High-Quality End-to-End Text to Speech](https://arxiv.org/abs/2006.04558) \\
**Yi Ren**, Chenxu Hu, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu

[**Project**](https://speechresearch.github.io/fastspeech2/) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong>
  - This work is included by many famous speech synthesis open-source projects, such as [PaddlePaddle/Parakeet ![](https://img.shields.io/github/stars/PaddlePaddle/PaddleSpeech?style=social)](https://github.com/PaddlePaddle/PaddleSpeech), [ESPNet ![](https://img.shields.io/github/stars/espnet/espnet?style=social)](https://github.com/espnet/espnet) and [fairseq ![](https://img.shields.io/github/stars/pytorch/fairseq?style=social)](https://github.com/pytorch/fairseq).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/diffsinger.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DiffSinger: Singing Voice Synthesis via Shallow Diffusion Mechanism](https://arxiv.org/abs/2105.02446) \\
Jinglin Liu, Chengxi Li, **Yi Ren**, Feiyang Chen, Zhou Zhao

- Many [video demos](https://www.bilibili.com/video/BV1be411N7JA) created by the [DiffSinger community](https://github.com/openvpi) are released.
- DiffSinger was introduced in [a very popular video](https://www.bilibili.com/video/BV1uM411t7ZJ) (1600k+ views) on Bilibili!

- [**Project**](https://diffsinger.github.io/) \| [![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social&label=DiffSpeech Stars)](https://github.com/NATSpeech/NATSpeech) \| [![](https://img.shields.io/github/stars/MoonInTheRiver/DiffSinger?style=social&label=DiffSinger Stars)](https://github.com/MoonInTheRiver/DiffSinger) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/NATSpeech/DiffSpeech)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2021</div><img src='images/portaspeech.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PortaSpeech: Portable and High-Quality Generative Text-to-Speech](https://arxiv.org/abs/2109.15166) \\
**Yi Ren**, Jinglin Liu, Zhou Zhao

[**Project**](https://portaspeech.github.io/) \| [![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social&label=Code+Stars)](https://github.com/NATSpeech/NATSpeech) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/NATSpeech/PortaSpeech)
</div>
</div>

- ``ICSE 2023`` [Improving Java Deserialization Gadget Chain Mining via Overriding-Guided Object Generation](), **Sicong Cao**, Xiaobing Sun, Xiaoxue Wu, Lili Bo, Bin Li, Rongxin Wu, Wei Liu, Biao He, Yu Ouyang, Jiajia Li
- [SPVF: Security Property Assisted Vulnerability Fixing via Attention-Based Models](https://link.springer.com/article/10.1007/s10664-022-10216-4), Zhou Zhou, Lili Bo, Xiaoxue Wu, Xiaobing Sun, Tao Zhang, Bin Li, Jiale Zhang, **Sicong Cao**, **Empirical Software Engineering (2022)**
- [MVD: Memory-Related Vulnerability Detection Based on Flow-Sensitive Graph Neural Networks](https://dl.acm.org/doi/10.1145/3510003.3510219), **Sicong Cao**, Xiaobing Sun, Lili Bo, Rongxin Wu, Bin Li, Chuanqi Tao, **ICSE 2022**
- [GrasP: Graph-to-Sequence Learning for Automated Program Repair](https://ieeexplore.ieee.org/document/9724652/),	Ben Tang, Bin Li, Lili Bo, Xiaoxue Wu, **Sicong Cao**, Xiaobing Sun, **QRS 2021**
- [A Comprehensive Study on Security Bug Characteristics](https://onlinelibrary.wiley.com/doi/10.1002/smr.2376), Ying Wei, Xiaobing Sun, Lili Bo, **Sicong Cao**, Xin Xia, Bin Li, **Journal of Software: Evolution and Process (2021)**
- [BGNN4VD: Constructing Bidirectional Graph Neural-Network for Vulnerability Detection](https://www.sciencedirect.com/science/article/abs/pii/S0950584921000586?via%3Dihub), **Sicong Cao**, Xiaobing Sun, Lili Bo, Ying Wei, Bin Li, **Information and Software Technology (2021)**

# 🎖 Honors and Awards
- *2020.11* Software Research Achievement Prototype System Competition (2nd Prize), ChinaSoft 2020. 

# 📖 Educations
- *2019.06 - 2022.12 (now)*, PhD candidate, Yangzhou University, Yangzhou.
- *2015.09 - 2019.06*, Undergraduate, Nanjing Institute of Technology, Nanjing.

# 💬 Invited Talks
- *2022.11*, Data-Driven Software Vulnerability Detection (优秀博士生论坛), ChinaSoft 2022 (10 students in China each year).

# 💻 Internships
- *2022.04 - 2022.06*, [Ant Group, Security FG Group](https://www.antgroup.com/), China.
