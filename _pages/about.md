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

I am currently an associate professor (pre-tenure track) at the School of Computer Science, Nanjing University of Posts and Telecommunications (NJUPT). I got my Ph.D degree in March 2025 from the School of Information Engineering, Yangzhou University, China. I was very fortunate to work under the supervision of Prof. [Xiaobing Sun](https://risame.github.io/sun/) and Prof. [Wei Liu](https://xxgcxy.yzu.edu.cn/info/1020/4051.htm). From October 2023 to September 2024, I was a visiting student of Prof. [David Lo](http://www.mysmu.edu/faculty/davidlo/) at Singapore Management University. I am open to collaboration and communication. If you want to share awesome ideas, feel free to contact me.

# 📚 Research Interest
I have published over 20 papers <a href='https://scholar.google.com/citations?user=c-vPF2gAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FSicongCao%2Fsicongcao.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international SE/Security conferences (e.g., ICSE, ASE, S&P, USENIX Sec) and journals (e.g., TOSEM, TDSC, CSUR). Currently, I focus on the following research topics:
- Software Security: Vulnerability Detection (ICSE'24, ASE'24), Localization (ICSE'22, TOSEM'24), Classification (JOS'25, TII'24), Assessment (TSC'25), and Repair (TOSEM'25, ICSE'26)
- OSS Security: Malicious Package Detection (SEC'25), Security Patch Management
- Web Security: Web Application Fuzzing, Taint Analysis (S&P'23)
- LLM Security: Jailbreaking, LLM Framework Vulnerability Detection


# 🔥 News
- <span style="color:#B00C00">[*2025.10*]</span> &nbsp;🎉 One paper is accepted by **ICSE 2026**! Congras to Zhenlei!
- <span style="color:#B00C00">[*2025.09*]</span> &nbsp;🎉 One paper is accepted by **TSC**! Congras to Zhenlei!
- <span style="color:#B00C00">[*2025.07*]</span> &nbsp;🎉 One paper is accepted by **CSUR**!
- <span style="color:#B00C00">[*2025.07*]</span> &nbsp;🎉 One paper is accepted by **TDSC**! Congras to Mingxuan!
- <span style="color:#B00C00">[*2025.06*]</span> &nbsp;🎉 One paper is accepted by **SEKE 2025**! Congras to Wenya!
- <span style="color:#B00C00">[*2025.06*]</span> &nbsp;🎉 One paper is accepted by **USENIX Security 2025**! Congras to Xingan!


# 📝 Selected Publications
💌 <span style="color:#ff00fc">refers to the corresponding author</span>  
<span style="color:blue">Representative papers:</span> <span style="color:#B00C00">13</span> <span style="color:blue">CCF-A papers,</span> <span style="color:#B00C00">3</span> <span style="color:blue">JCR-Q1 papers</span>
## Conference
- `ICSE'26` **Well Begun is Half Done: Location-Aware and Trace-Guided Iterative Automated Vulnerability Repair**. <a class="media" href="" target="_blank"><img src="./images/pdf.png" style="width: 4em;"></a>   
  Zhenlei Ye, Xiaobing Sun, <span style="color:blue">Sicong Cao</span>💌, Lili Bo, and Bin Li.  
  In *Proceedings of the 48th IEEE/ACM International Conference on Software Engineering (ICSE)*, April, 2026. (<span style="color:#B00C00">CCF-A</span>)   
- `USENIX Sec'25` **MalGuard: Towards Real-Time, Accurate, and Actionable Detection of Malicious Packages in PyPI Ecosystem**. <a class="media" href="./publications/USENIX25/USENIX25-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  Xingan Gao, Xiaobing Sun, <span style="color:blue">Sicong Cao</span>💌, Kaifeng Huang, Di Wu, Xiaolei Liu, Xingwei Lin, and Yang Xiang.  
  In *Proceedings of the 34th USENIX Security Symposium (USENIX Sec)*, August, 2025. (<span style="color:#B00C00">CCF-A</span>)   
- `ASE'24` **Snopy: Bridging Sample Denoising with Causal Graph Learning for Effective Vulnerability Detection**. <a class="media" href="./publications/ASE24/ASE24-Papera.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Xiaoxue Wu, David Lo, Lili Bo, Bin Li, Xiaolei Liu, Xingwei Lin, and Wei Liu.  
  In *Proceedings of the 39th ACM/IEEE International Conference on Automated Software Engineering (ASE)*, October, 2024. (<span style="color:#B00C00">CCF-A</span>)   
- `ASE'24` **1+1>2: Integrating Deep Code Behaviors with Metadata Features for Malicious PyPI Package Detection**. <a class="media" href="./publications/ASE24/ASE24-Paperb.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  Xiaobing Sun, Xingan Gao, <span style="color:blue">Sicong Cao</span>💌, Lili Bo, Xiaoxue Wu, and Kaifeng Huang.  
  In *Proceedings of the 39th ACM/IEEE International Conference on Automated Software Engineering (ASE)*, October, 2024. (<span style="color:#B00C00">CCF-A</span>)   
- `ICSE'24` **Coca: Improving and Explaining Graph Neural Network-Based Vulnerability Detection Systems**. <a class="media" href="./publications/ICSE24/ICSE24-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Xiaoxue Wu, David Lo, Lili Bo, Bin Li, and Wei Liu.  
  In *Proceedings of the 46th IEEE/ACM International Conference on Software Engineering (ICSE)*, April, 2024. (<span style="color:#B00C00">CCF-A</span>)   
  <!-- [<span class="pdf">Paper</span>](/publications/ICSE24/ICSE24-Paper.pdf)
  [<span class="slide">Slides</span>](/publications/ICSE24/ICSE24-Slides.pdf)
  [<span class="video">Video</span>](https://www.youtube.com/watch?v=PlFAMJtvTmg)    -->
- `S&P'23` **ODDFUZZ: Discovering Java Deserialization Vulnerabilities via Structure-Aware Directed Greybox Fuzzing**. <a class="media" href="./publications/S&P23/SP23-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  <span style="color:blue">Sicong Cao</span>, Biao He, Xiaobing Sun, Yu Ouyang, Chao Zhang, Xiaoxue Wu, Ting Su, Lili Bo, Bin Li, Chuanlei Ma, Jiajia Li, and Tao Wei.  
  In *Proceedings of the 44th IEEE Symposium on Security and Privacy (S&P)*, May, 2023. (<span style="color:#B00C00">CCF-A</span>)   
  Presented at **BlackHat USA 2023** [[Talk Abstract](https://www.blackhat.com/us-23/briefings/schedule/#oddfuzz-hunting-java-deserialization-gadget-chains-via-structure-aware-directed-greybox-fuzzing-31367)]  
  <!-- [<span class="pdf">Paper</span>](/publications/S&P23/SP23-Paper.pdf)
  [<span class="slide">Slides</span>](/publications/S&P23/SP23-Slides.pdf)
  [<span class="video">Video</span>](https://www.youtube.com/watch?v=6Nu5sAl0NeY)    -->
- `ICSE'23` **Improving Java Deserialization Gadget Chain Mining via Overriding-Guided Object Generation**. <a class="media" href="./publications/ICSE23/ICSE23-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Xiaoxue Wu, Lili Bo, Bin Li, Rongxin Wu, Wei Liu, Biao He, Yu Ouyang, and Jiajia Li.  
  In *Proceedings of the 45th IEEE/ACM International Conference on Software Engineering (ICSE)*, May, 2023. (<span style="color:#B00C00">CCF-A</span>)   
  <!-- [<span class="pdf">Paper</span>](/publications/ICSE23/ICSE23-Paper.pdf)
  [<span class="slide">Slides</span>](/publications/ICSE23/ICSE23-Slides.pdf)    -->
- `ICSE'22` **MVD: Memory-Related Vulnerability Detection Based on Flow-Sensitive Graph Neural Networks**. <a class="media" href="./publications/ICSE22/ICSE22-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Lili Bo, Rongxin Wu, Bin Li, and Chuanqi Tao.  
  In *Proceedings of the 44th IEEE/ACM International Conference on Software Engineering (ICSE)*, May, 2022. (<span style="color:#B00C00">CCF-A</span>)    
  <!-- [<span class="pdf">Paper</span>](/publications/ICSE22/ICSE22-Paper.pdf)
  [<span class="slide">Slides</span>](/publications/ICSE22/ICSE22-Slides.pdf)
  [<span class="video">Video</span>](https://www.youtube.com/watch?v=NS1ZTfOPnDk&t=1085s)    -->

## Journal
- `TSC'25` **KG4VA: Constructing Vulnerability Knowledge Graph for Software Vulnerability Assessment**. <a class="media" href="" target="_blank"><img src="./images/pdf.png"></a>   
  Zhenlei Ye, Xiaobing Sun, Lili Bo, <span style="color:blue">Sicong Cao</span>, Xiaoxue Ren, Lianyong Qi, and Jiale Zhang.  
  In *IEEE Transactions on Service Computing*, 2025. (__IF2025: 5.8__, <span style="color:#B00C00">CCF-A</span>)  
- `CSUR'25` **A Systematic Literature Review on Explainability for Machine/Deep Learning-based Software Engineering Research**. <a class="media" href="./publications/CSUR25/CSUR25-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Ratnadira Widyasari, David Lo, Xiaoxue Wu, Lili Bo, Jiale Zhang, Bin Li, Wei Liu, Di Wu,
  and Yixin Chen.  
  In *ACM Computing Surveys*, 2025. (__IF2025: 28__, <span style="color:#B00C00">JCR-Q1</span>)   
- `TDSC'25` **HgtJIT: Just-in-Time Vulnerability Detection based on Heterogeneous Graph Transformer**. <a class="media" href="./publications/TDSC25/TDSC25-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  Xiaobing Sun, Mingxuan Zhou, <span style="color:blue">Sicong Cao</span>💌, Xiaoxue Wu, Lili Bo, Di Wu, Bin Li, and Yang Xiang.  
  In *IEEE Transactions on Dependable and Secure Computing*, 2025. (__IF2025: 7.5__, <span style="color:#B00C00">CCF-A</span>)    
- `软件学报'25` **基于结构感知图神经网络的多类别漏洞检测方法**. <a class="media" href="./publications/JOS25/JOS25-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  <span style="color:blue">曹思聪</span>, 孙小兵, 薄莉莉, 吴潇雪, 李斌, 陈厅, 罗夏朴, 张涛, 刘维.  
  In *软件学报*, 2025. (<span style="color:#B00C00">中文CCF-A</span>)  
- `TOSEM'25` **Large Language Model for Vulnerability Detection and Repair: Literature Review and the Road Ahead**. <a class="media" href="./publications/TOSEM25/TOSEM25-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  Xin Zhou, <span style="color:blue">Sicong Cao</span>💌, Xiaobing Sun, and David Lo.  
  In *ACM Transactions on Software Engineering and Methodology*, 2024. (__IF2024: 6.6__, <span style="color:#B00C00">CCF-A</span>)  
- `TII'24` **Hierarchy-Aware Representation Learning for Industrial IoT Vulnerability Classification**. <a class="media" href="./publications/TII24/TII24-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Xinye Yang, Xiaoxue Wu, Wei Liu, and Bin Li.  
  In *IEEE Transactions on Industrial Informatics*, 2024. (__IF2024: 11.7__, <span style="color:#B00C00">JCR-Q1</span>)  
- `IoTJ'24` **EXVul: Towards Effective and Explainable Vulnerability Detection for IoT Devices**. <a class="media" href="./publications/IOT24/IOT24-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Wei Liu, Di Wu, Jiale Zhang, Yan Li, Tom H. Luan, and Longxiang Gao.  
  In *IEEE Internet of Things Journal*, 2024. (__IF2023: 10.6__, <span style="color:#B00C00">JCR-Q1</span>)  
- `TOSEM'24` **Learning to Detect Memory-Related Vulnerabilities**. <a class="media" href="./publications/TOSEM24/TOSEM24-Paper.pdf" target="_blank"><img src="./images/pdf.png"></a>   
  <span style="color:blue">Sicong Cao</span>, Xiaobing Sun, Lili Bo, Rongxin Wu, Bin Li, Xiaoxue Wu, Chuanqi Tao, Tao Zhang, and Wei Liu.  
  In *ACM Transactions on Software Engineering and Methodology*, 2024. (__IF2023: 4.4__, <span style="color:#B00C00">CCF-A</span>)    


# 🎖 Honors and Awards
- *2025.06*: Outstanding Graduate, Yangzhou University
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
- ``CSUR`` [ACM Computing Surveys](https://dl.acm.org/journal/csur)

## Conference Activities
- Reviewer, CVPR 2026
- PC Member, EASE 2026 AI Models / Data Track
- Shadow PC, ICSE 2026
- PC Member, APSEC 2025 ERA Track
- PC Member, EuroS&P 2025
- Junior PC, MSR 2025
- Shadow PC, ICSE 2025
- PC Member, ASE 2024 Industry Track
- Registration Chair, FSE 2024

# 💻 Internships
- *2022.04 - 2022.06*, [Ant Group, Security FG Group](https://www.antgroup.com/), China.
