---
permalink: /
title: ""
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

My research interest includes Software Engineering (SE) and Deep Learning (DL). I have published 10 papers <a href='https://scholar.google.com/citations?user=c-vPF2gAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FSicongCao%2Fsicongcao.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international SE/Security conferences (e.g., ICSE*3, S&P) and journals (e.g., TOSEM, IST).


# 🔥 News
- *2023.12*: &nbsp;🎉 One paper is accepted by the **Technical track of ICSE 2024**!
- *2023.11*: &nbsp;🎉 I win the National Scholarship and Principal Special Scholarship!
- *2023.09*: &nbsp;🎉 One paper is accepted by **TOSEM**!
- *2023.08*: &nbsp;🏆 Our paper wins the <span style="color:red">Best Paper Award</span> at **BlockSyS 2023**!
- *2023.07*: &nbsp;🎉 I win the **Chinese China Scholarship Council (CSC)** funding to work as a visiting PhD of **Prof. David Lo**!
- *2023.03*: &nbsp;🎉 One paper is accepted by the **Main track of IEEE S&P 2023**!
- *2022.12*: &nbsp;🎉 One paper is accepted by the **Technical track of ICSE 2023**!
- *2021.12*: &nbsp;🎉 One paper is accepted by the **Technical track of ICSE 2022**!

# 📝 Publications
## Conference (* is the corresponding author)
- `ICSE'24` **Coca: Improving and Explaining Graph Neural Network-Based Vulnerability Detection Systems**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Xiaoxue Wu, David Lo, Lili Bo, Bin Li, and Wei Liu.  
  In *Proceedings of the 46th IEEE/ACM International Conference on Software Engineering (ICSE)*, April, 2024.  
  [[Paper](https://sicongcao.github.io/publications/ICSE24/ICSE24-Paper.pdf)]
  [[Slides](https://sicongcao.github.io/publications/ICSE24/ICSE24-Slides.pdf)]
  [[Code](https://github.com/CocaVul/Coca)]
  [[DOI](https://arxiv.org/abs/2401.14886)]
- `BlockSys'23` <span style="color:red">(Best Paper Award)</span> **The Best of Both Worlds: Integrating Semantic Features with Expert Features for Smart Contract Vulnerability Detection**.  
  Xingwei Lin, Mingxuan Zhou, <span style="color:blue">Sicong Cao</span>*, Jiashui Wang, and Xiaobing Sun.  
  In *Proceedings of the 5th International Conference on Blockchain and Trustworthy Systems (BlockSys)*, August, 2023.  
  [[Paper](https://sicongcao.github.io/publications/BlockSyS23/BlockSyS23-Paper.pdf)]
  [[Slides](https://sicongcao.github.io/publications/BlockSyS23/BlockSys23-Slides.pdf)]
  [[DOI](https://link.springer.com/chapter/10.1007/978-981-99-8104-5_2)]
- `S&P'23` **ODDFUZZ: Discovering Java Deserialization Vulnerabilities via Structure-Aware Directed Greybox Fuzzing**.  
  <span style="color:blue">Sicong Cao</span>, Biao He, Xiaobing Sun, Yu Ouyang, Chao Zhang, Xiaoxue Wu, Ting Su, Lili Bo, Bin Li, Chuanlei Ma, Jiajia Li, and Tao Wei.  
  In *Proceedings of the 44th IEEE Symposium on Security and Privacy (S&P)*, May, 2023.  
  [[Paper](https://sicongcao.github.io/publications/S&P23/SP23-Paper.pdf)]
  [[Slides](https://sicongcao.github.io/publications/S&P23/SP23-Slides.pdf)]
  [[Code](https://github.com/ODDFuzz/ODDFuzz)]
  [[DOI](https://ieeexplore.ieee.org/document/10179377)]
- `ICSE'23` **Improving Java Deserialization Gadget Chain Mining via Overriding-Guided Object Generation**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Xiaoxue Wu, Lili Bo, Bin Li, Rongxin Wu, Wei Liu, Biao He, Yu Ouyang, and Jiajia Li.  
  In *Proceedings of the 45th IEEE/ACM International Conference on Software Engineering (ICSE)*, May, 2023.  
  [[Paper](https://sicongcao.github.io/publications/ICSE23/ICSE23-Paper.pdf)]
  [[Slides](https://sicongcao.github.io/publications/ICSE23/ICSE23-Slides.pdf)]
  [[Code](https://github.com/GCMiner/GCMiner)]
  [[DOI](https://ieeexplore.ieee.org/document/10172888)]
- `ICSE'22` **MVD: Memory-Related Vulnerability Detection Based on Flow-Sensitive Graph Neural Networks**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Lili Bo, Rongxin Wu, Bin Li, and Chuanqi Tao.  
  In *Proceedings of the 44th IEEE/ACM International Conference on Software Engineering (ICSE)*, May, 2022.  
  [[Paper](https://sicongcao.github.io/publications/ICSE22/ICSE22-Paper.pdf)]
  [[Slides](https://sicongcao.github.io/publications/ICSE22/ICSE22-Slides.pdf)]
  [[Code](https://github.com/MVDetection/MVD)]
  [[DOI](https://dl.acm.org/doi/10.1145/3510003.3510219)]
- `QRS'21` **GrasP: Graph-to-Sequence Learning for Automated Program Repair**.  
  Ben Tang, Bin Li, Lili Bo, Xiaoxue Wu, <span style="color:blue">Sicong Cao</span>, and Xiaobing Sun.  
  In *Proceedings of the 21th IEEE International Conference on Software Quality, Reliability, and Security (QRS)*, December, 2021.  
  [[Paper](https://sicongcao.github.io/publications/QRS21/QRS21-Paper.pdf)]
  [[DOI](https://ieeexplore.ieee.org/document/9724652/)]

## Journal
- `TOSEM'24` **Learning to Detect Memory-Related Vulnerabilities**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Lili Bo, Rongxin Wu, Bin Li, Xiaoxue Wu, Chuanqi Tao, Tao Zhang, and Wei Liu.  
  In *ACM Transactions on Software Engineering and Methodology*, 2024.  
  [[Paper](https://sicongcao.github.io/publications/TOSEM24/TOSEM24-Paper.pdf)]
  [[Code](https://github.com/SicongCao/MemoryVul)]
  [[DOI](https://dl.acm.org/doi/abs/10.1145/3624744)]
- `EMSE'22` **SPVF: Security Property Assisted Vulnerability Fixing via Attention-Based Models**.  
  Zhou Zhou, Lili Bo, Xiaoxue Wu, Xiaobing Sun, Tao Zhang, Bin Li, Jiale Zhang, and <span style="color:blue">Sicong Cao</span>.  
  In *Empirical Software Engineering*, 2022.  
  [[Paper](https://sicongcao.github.io/publications/EMSE22/EMSE22-Paper.pdf)]
  [[DOI](https://link.springer.com/article/10.1007/s10664-022-10216-4)]
- `JSEP'21` **A Comprehensive Study on Security Bug Characteristics**.  
  Ying Wei, Xiaobing Sun, Lili Bo, <span style="color:blue">Sicong Cao</span>, Xin Xia, and Bin Li.  
  In *Journal of Software: Evolution and Process*, 2021.  
  [[Paper](https://sicongcao.github.io/publications/JSEP21/JSEP21-Paper.pdf)]
  [[DOI](https://onlinelibrary.wiley.com/doi/10.1002/smr.2376)]
- `IST'21` **Learning to Detect Memory-Related Vulnerabilities**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Lili Bo, Ying Wei, and Bin Li.  
  In *Journal of Information and Software Technology*, 2024.  
  [[Paper](https://sicongcao.github.io/publications/IST21/IST21-Paper.pdf)]
  [[Code](https://github.com/SicongCao/BGNN4VD)]
  [[DOI](https://www.sciencedirect.com/science/article/abs/pii/S0950584921000586?via%3Dihub)]

# 🎖 Honors and Awards
- *2024.02*: ACM SIGSOFT CAPS Travel Funds, ICSE 2024
- *2023.11*: Principal Special Scholarship (1/15)
- *2023.11*: National Scholarship
- *2023.08*: BlockSys Best Paper Award
- *2023.06*: 1st Place (Freestyle/A) of The 8th C4-Network Technology Challenge 🏆
- *2022.11*: Distinguished Doctoral Symposium, CCF ChinaSoft 2022 (1/13)
- *2020.11*: Prototype Research Tool Award 2nd Place (Fixed topic) in CCF ChinaSoft 2020
  
# 📖 Educations
- *2023.09 - 2024.08*, Visiting Ph.D student, Singapore Management University, Singapore.
- *2019.06 - Present*, Ph.D candidate, Yangzhou University, Yangzhou.
- *2015.09 - 2019.06*, Undergraduate, Nanjing Institute of Technology, Nanjing.

# 📚 Reviewer
- ``CCF-A`` [IEEE Transactions on Software Engineering](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=32)
- ``CCF-A`` [ACM Transactions on Software Engineering and Methodology](https://dl.acm.org/journal/tosem)
- ``CCF-B`` [Automated Software Engineering](https://link.springer.com/journal/10515)
- ``CCF-B`` [Empirical Software Engineering](https://link.springer.com/journal/10664)

# 💻 Internships
- *2022.04 - 2022.06*, [Ant Group, Security FG Group](https://www.antgroup.com/), China.
