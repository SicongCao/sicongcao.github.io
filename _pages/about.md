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

I got my Ph.D degree in March 2025 from the School of Information Engineering, Yangzhou University, China. I was very fortunate to work under the supervision of Prof. [Xiaobing Sun](https://risame.github.io/sun/) and Prof. [Wei Liu](https://xxgcxy.yzu.edu.cn/info/1020/4051.htm). From October 2023 to September 2024, I was a visiting student of Prof. [David Lo](http://www.mysmu.edu/faculty/davidlo/) at Singapore Management University. I am open to collaboration and communication. If you want to share awesome ideas, feel free to contact me.

My research interest includes Software Engineering (SE) and Deep Learning (DL). I have published over 10 papers <a href='https://scholar.google.com/citations?user=c-vPF2gAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fgithub.com%2FSicongCao%2Fsicongcao.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international SE/Security conferences (e.g., ICSE, ASE, S&P) and journals (e.g., TOSEM, TII).


# 🔥 News
- <span style="color:red">[*2024.12*]</span> &nbsp;🎉 One paper is accepted by **软件学报**!
- <span style="color:red">[*2024.11*]</span> &nbsp;🎉 One paper is accepted by **TOSEM**!
- <span style="color:red">[*2024.10*]</span> &nbsp;🎉 Invited to serve as a program committee member of **EuroS&P 2025**!
- <span style="color:red">[*2024.09*]</span> &nbsp;🎉 Invited to serve as a Junior PC of **MSR 2025**!
- <span style="color:red">[*2024.08*]</span> &nbsp;🎉 Two paper are accepted by the **Research track of ASE 2024**!
- <span style="color:red">[*2024.07*]</span> &nbsp;🎉 Invited to serve as a shadow PC of **ICSE 2025**!
- <span style="color:red">[*2024.06*]</span> &nbsp;🎉 Invited to serve as a program committee member of **Industry Track of ASE 2024**!
- <span style="color:red">[*2024.05*]</span> &nbsp;🎉 One paper is accepted by **IEEE TII**!
- <span style="color:red">[*2024.04*]</span> &nbsp;🎉 Invited to serve as the registration chair of **FSE 2024**!
- <span style="color:red">[*2024.03*]</span> &nbsp;🎉 One paper is accepted by **IEEE IoTJ**!

# 📝 Selected Publications
<span style="color:blue">Representative papers:</span> <span style="color:red">9</span> <span style="color:blue">CCF-A papers,</span> <span style="color:red">2</span> <span style="color:blue">JCR-Q1 papers</span>
## Conference
- `ASE'24` **Snopy: Bridging Sample Denoising with Causal Graph Learning for Effective Vulnerability Detection**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Xiaoxue Wu, David Lo, Lili Bo, Bin Li, Xiaolei Liu, Xingwei Lin, and Wei Liu.  
  In *Proceedings of the 39th ACM/IEEE International Conference on Automated Software Engineering (ASE)*, October, 2024.  (<span style="color:red">CCF-A</span>)   
  [[Paper](https://sicongcao.github.io/publications/ASE24/ASE24-Papera.pdf)]
  [[DOI](https://dl.acm.org/doi/10.1145/3691620.3695057)]
- `ASE'24` **1+1>2: Integrating Deep Code Behaviors with Metadata Features for Malicious PyPI Package Detection**.  
  Xiaobing Sun, Xingan Gao, <span style="color:blue">Sicong Cao</span>, Lili Bo, Xiaoxue Wu, and Kaifeng Huang.  
  In *Proceedings of the 39th ACM/IEEE International Conference on Automated Software Engineering (ASE)*, October, 2024.  (<span style="color:red">CCF-A</span>)   
  [[Paper](https://sicongcao.github.io/publications/ASE24/ASE24-Paperb.pdf)]
  [[DOI](https://dl.acm.org/doi/10.1145/3691620.3695493)]
- `ICSE'24` **Coca: Improving and Explaining Graph Neural Network-Based Vulnerability Detection Systems**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Xiaoxue Wu, David Lo, Lili Bo, Bin Li, and Wei Liu.  
  In *Proceedings of the 46th IEEE/ACM International Conference on Software Engineering (ICSE)*, April, 2024.  (<span style="color:red">CCF-A</span>)   
  [[Paper](https://sicongcao.github.io/publications/ICSE24/ICSE24-Paper.pdf)]
  [[Slides](https://sicongcao.github.io/publications/ICSE24/ICSE24-Slides.pdf)]
  [[Code](https://github.com/CocaVul/Coca)]
  [[Video](https://www.youtube.com/watch?v=PlFAMJtvTmg)]
  [[DOI](https://dl.acm.org/doi/10.1145/3597503.3639168)]
- `S&P'23` **ODDFUZZ: Discovering Java Deserialization Vulnerabilities via Structure-Aware Directed Greybox Fuzzing**.  
  <span style="color:blue">Sicong Cao</span>, Biao He, Xiaobing Sun, Yu Ouyang, Chao Zhang, Xiaoxue Wu, Ting Su, Lili Bo, Bin Li, Chuanlei Ma, Jiajia Li, and Tao Wei.  
  In *Proceedings of the 44th IEEE Symposium on Security and Privacy (S&P)*, May, 2023. (<span style="color:red">CCF-A</span>)  
  [[Paper](https://sicongcao.github.io/publications/S&P23/SP23-Paper.pdf)]
  [[Slides](https://sicongcao.github.io/publications/S&P23/SP23-Slides.pdf)]
  [[Code](https://github.com/ODDFuzz/ODDFuzz)]
  [[Video](https://www.youtube.com/watch?v=6Nu5sAl0NeY)]
  [[DOI](https://ieeexplore.ieee.org/document/10179377)]
- `ICSE'23` **Improving Java Deserialization Gadget Chain Mining via Overriding-Guided Object Generation**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Xiaoxue Wu, Lili Bo, Bin Li, Rongxin Wu, Wei Liu, Biao He, Yu Ouyang, and Jiajia Li.  
  In *Proceedings of the 45th IEEE/ACM International Conference on Software Engineering (ICSE)*, May, 2023. (<span style="color:red">CCF-A</span>)    
  [[Paper](https://sicongcao.github.io/publications/ICSE23/ICSE23-Paper.pdf)]
  [[Slides](https://sicongcao.github.io/publications/ICSE23/ICSE23-Slides.pdf)]
  [[Code](https://github.com/GCMiner/GCMiner)]
  [[DOI](https://ieeexplore.ieee.org/document/10172888)]
- `ICSE'22` **MVD: Memory-Related Vulnerability Detection Based on Flow-Sensitive Graph Neural Networks**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Lili Bo, Rongxin Wu, Bin Li, and Chuanqi Tao.  
  In *Proceedings of the 44th IEEE/ACM International Conference on Software Engineering (ICSE)*, May, 2022. (<span style="color:red">CCF-A</span>)    
  [[Paper](https://sicongcao.github.io/publications/ICSE22/ICSE22-Paper.pdf)]
  [[Slides](https://sicongcao.github.io/publications/ICSE22/ICSE22-Slides.pdf)]
  [[Code](https://github.com/MVDetection/MVD)]
  [[Video](https://www.youtube.com/watch?v=NS1ZTfOPnDk&t=1085s)]
  [[DOI](https://dl.acm.org/doi/10.1145/3510003.3510219)]

## Journal
- `软件学报'25` **基于结构感知图神经网络的多类别漏洞检测方法**.  
  <span style="color:blue">曹思聪</span>, 孙小兵, 薄莉莉, 吴潇雪, 李斌, 陈厅, 罗夏朴, 张涛, 刘维.  
  In *软件学报*, 2025. (<span style="color:red">中文CCF-A</span>)  
  [[Paper](https://sicongcao.github.io/publications/JOS25/JOS25-Paper.pdf)]
  [[DOI](https://www.jos.org.cn/jos/article/abstract/7375)]
- `TOSEM'25` **Large Language Model for Vulnerability Detection and Repair: Literature Review and the Road Ahead**.  
  Xin Zhou, <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, and David Lo.  
  In *ACM Transactions on Software Engineering and Methodology*, 2024. (__IF2024: 6.6__, <span style="color:red">CCF-A</span>)  
  [[Paper](https://sicongcao.github.io/publications/TOSEM25/TOSEM25-Paper.pdf)]
  [[DOI](https://dl.acm.org/doi/10.1145/3708522)]
- `TII'24` **Hierarchy-Aware Representation Learning for Industrial IoT Vulnerability Classification**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Xinye Yang, Xiaoxue Wu, Wei Liu, and Bin Li.  
  In *IEEE Transactions on Industrial Informatics*, 2024. (__IF2024: 11.7__, <span style="color:red">JCR-Q1</span>)  
  [[Paper](https://sicongcao.github.io/publications/TII24/TII24-Paper.pdf)]
  [[DOI](https://ieeexplore.ieee.org/document/10574217)]
- `IoTJ'24` **EXVul: Towards Effective and Explainable Vulnerability Detection for IoT Devices**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Wei Liu, Di Wu, Jiale Zhang, Yan Li, Tom H. Luan, and Longxiang Gao.  
  In *IEEE Internet of Things Journal*, 2024. (__IF2023: 10.6__, <span style="color:red">JCR-Q1</span>)  
  [[Paper](https://sicongcao.github.io/publications/IOT24/IOTJ24-Paper.pdf)]
  [[DOI](https://ieeexplore.ieee.org/document/10479158)]
- `TOSEM'24` **Learning to Detect Memory-Related Vulnerabilities**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Lili Bo, Rongxin Wu, Bin Li, Xiaoxue Wu, Chuanqi Tao, Tao Zhang, and Wei Liu.  
  In *ACM Transactions on Software Engineering and Methodology*, 2024. (__IF2023: 4.4__, <span style="color:red">CCF-A</span>)    
  [[Paper](https://sicongcao.github.io/publications/TOSEM24/TOSEM24-Paper.pdf)]
  [[Code](https://github.com/SicongCao/MemoryVul)]
  [[DOI](https://dl.acm.org/doi/abs/10.1145/3624744)]
- `IST'21` **BGNN4VD: Constructing Bidirectional Graph Neural-Network for Vulnerability Detection**.  
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Lili Bo, Ying Wei, and Bin Li.  
  In *Information and Software Technology*, 2021.  
  [[Paper](https://sicongcao.github.io/publications/IST21/IST21-Paper.pdf)]
  [[Code](https://github.com/SicongCao/BGNN4VD)]
  [[DOI](https://www.sciencedirect.com/science/article/abs/pii/S0950584921000586?via%3Dihub)]

# 🎖 Honors and Awards
- *2024.11*: Principal Special Scholarship (1/15)
- *2024.11*: National Scholarship
- *2024.09*: ACM SIGSOFT CAPS Travel Funds, ASE 2024
- *2024.09*: Grand Place (Freestyle/A-ST) of The 9th C4-Network Technology Challenge 🏆
- *2024.02*: ACM SIGSOFT CAPS Travel Funds, ICSE 2024
- *2023.11*: Principal Special Scholarship (1/15)
- *2023.11*: National Scholarship
- *2023.09*: 1st Place (Freestyle/A) of The 8th C4-Network Technology Challenge 🏆
- *2023.08*: BlockSys Best Paper Award
- *2023.07*: China Scholarship Council (CSC) Scholarship
- *2022.11*: Distinguished Doctoral Symposium, CCF ChinaSoft 2022 (1/13)
- *2020.11*: Prototype Research Tool Award 2nd Place (Fixed topic) in CCF ChinaSoft 2020
  
# 📖 Educations
- *2023.10 - 2024.10*, Visiting Ph.D student, Singapore Management University, Singapore.
- *2019.06 - 2025.03*, Ph.D, Yangzhou University, Yangzhou.
- *2015.09 - 2019.06*, Undergraduate, Nanjing Institute of Technology, Nanjing.

# 👨‍💻 Services
## Journal Reviewing
- ``TSE`` [IEEE Transactions on Software Engineering](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=32)
- ``TOSEM`` [ACM Transactions on Software Engineering and Methodology](https://dl.acm.org/journal/tosem)
- ``TDSC`` [IEEE Transactions on Dependable and Secure Computing](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8858)
- ``TIFS`` [IEEE Transactions on Information Forensics and Security](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)
- ``ASEJ`` [Automated Software Engineering](https://link.springer.com/journal/10515)
- ``EMSE`` [Empirical Software Engineering](https://link.springer.com/journal/10664)
- ``JSEP`` [Journal of Software: Evolution and Process](https://onlinelibrary.wiley.com/journal/20477481)
- ``CACM`` [Communications of the ACM](https://dl.acm.org/magazine/cacm)

## Conference Activities
- PC Member, EuroS&P 2025
- Junior PC, MSR 2025
- Shadow PC, ICSE 2025
- PC Member, ASE 2024
- Registration Chair, FSE 2024

# 💻 Internships
- *2022.04 - 2022.06*, [Ant Group, Security FG Group](https://www.antgroup.com/), China.
