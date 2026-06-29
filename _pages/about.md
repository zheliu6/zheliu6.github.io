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

I am an Associate Researcher at the Institute of Software Chinese Academy of Sciences, University of Chinese Academy of Sciences, China. I obtained my PhD from University of Chinese Academy of Sciences (UCAS), China. I received the ACM Student Research Competition (SRC) 2023 Grand Finals Winners, 1st Place, Graduate Category, in 2023. (The first doctoral student in Chinese Mainland to win the honor.) My research focuses on Software Engineering, Mobile Testing, Deep Learning and Human-Computer Interaction. Specifically, I apply AI and light-weight program analysis technology in the following directions:

AI(LLM)-assisted automated mobile app development including requirement elicitation app GUI testing [ICSE'23a, ICSE'23b, ICSE'24a, ICSE'24b, FSE'25], usability [ASE'20, FSE'21, TSE'22, ASE'22], and bug replay [ICSE'23, ICSE'24].

Human machine collaborative testing including testing guide for testers [CHI'24, CHI'22, ICSE'22].

AI-empowered mining software repository including issue report mining [ESEM'20, ESEM'21].


My research interest includes Software Engineering and Human Machine Interaction. I have published 22 papers at the top international Software Engineering and Human Machine Interaction conferences/journal (CCF-A) with total <a href='https://scholar.google.com/citations?user=D27QoFMAAAAJ'>google scholar citations <strong><span id='total_cit'>2181</span></strong></a>.

# 🔥 News
- *2026.03*: &nbsp;🎉🎉 A full research paper is accepted at Proceedings of the ACM International Conference on the Foundations of Software Engineering (FSE'25).
- *2025.11*: &nbsp;🎉🎉 I received the "Distinguished Reviewer Award" in ASE 2025.
- *2025.09*: &nbsp;🎉🎉 A full research paper is accepted at IEEE Transactions on Software Engineering (TSE'25).
- *2025.08*: &nbsp;🎉🎉 A full research paper is accepted at Proceedings of the 40th IEEE/ACM International Conference on Automated Software Engineering (ASE'25).
- *2025.05*: &nbsp;🎉🎉 A full research paper is accepted at Proceedings of the 48th IEEE/ACM International Conference on Software Engineering (ICSE'26).
- *2025.01*: &nbsp;🎉🎉 A full research paper is accepted at Proceedings of the 2025 ACM International Conference on the Foundations of Software Engineering (FSE'25).
- *2024.09*: &nbsp;🎉🎉 I received the "Doctoral Dissertation Incentive Program of the Software Engineering Professional Committee of the CCF".
- *2024.08*: &nbsp;🎉🎉 I received the "Excellent Doctoral Dissertation of Chinese Academy of Sciences in 2024".
- *2024.05*: &nbsp;🎉🎉 The paper received the "Best　Paper　Honourable　Mention" in CHI'24.
- *2024.01*: &nbsp;🎉🎉 A full research paper is accepted at Proceedings of the 2024 CHI Conference on Human Factors in Computing Systems (CHI'24).
- *2023.10*: &nbsp;🎉🎉 Three full research papers are accepted at International Conference on Software Engineering (ICSE'24).
- *2023.05*: &nbsp;🎉🎉 I received the ACM Student Research Competition (SRC) 2023 **Grand Finals Winners**, ***1st Place***, Graduate Category. (The first doctoral student in Chinese Mainland to win the honor.)
- *2023.05*: &nbsp;🎉🎉 I received the "President of Chinese Chinese Academy of Sciences the Prize Scholarship"(中国科学院院长优秀奖).
- *2022.11*: &nbsp;🎉🎉 Three full research papers are accepted at International Conference on Software Engineering (ICSE'23).
- *2022.05*: &nbsp;🎉🎉 I received the ACM Student Research Competition (SRC) at ICSE 2022, ***1st Place***, Graduate Category. 
- *2020.09*: &nbsp;🎉🎉 I received the ACM Student Research Competition (SRC) at ASE 2020, ***1st Place***, Graduate Category.  

# 📝 Publications 
1. [FSE 2026] **From Suspicious Signals to Crashes: Guiding Bug-driven GUI Testing via Code-inspired Tracing**  
   The ACM International Conference on the Foundations of Software Engineering (CCF-A)  
   Mengzhuo Chen, ***Zhe Liu(co-first author)***, Chunyang Chen, Junjie Wang, Boyu Wu, Yuekai Huang, Jun Hu, Qing Wang
1. [TSE 2025] **Seeing is Believing: Vision-driven Non-crash Functional Bug Detection for Mobile Apps**  
   IEEE Transactions on Software Engineering (CCF-A)  
   ***Zhe Liu***, Cheng Li, Chunyang Chen, Junjie Wang, Mengzhuo Chen, Boyu Wu, Yawen Wang, Jun Hu, Qing Wang
1. [AAAI 2026] **Many Minds, One Path: LLM-Augmented Consensus Decision for Distributed Control in Multi-Agent Collaborative Stable Scenarios**  
   The Fortieth AAAI Conference on Artificial Intelligence (CCF-A)  
   Zhuohao Yu, ***Zhe Liu(co-first author)***, Tao Ren, Chenxue Wang, Junjie Wang, Qing Wang
1. [ASE 2025] **Beyond Static GUI Agent: Evolving LLM-based GUI Testing via Dynamic Memory**  
   IEEE/ACM International Conference on Automated Software Engineering (CCF-A)  
   Mengzhuo Chen, ***Zhe Liu(co-first author)***, Chunyang Chen, Junjie Wang, Yangguang Xue, Boyu Wu, Yuekai Huang, Libin Wu, Qing Wang
1. [ICSE 2026] **Think Outside the Box: Automating Inter-App Functionality Testing via Memory Implanting and Reasoning**  
   IEEE/ACM International Conference on Software Engineering (CCF-A)  
   Mengzhuo Chen, ***Zhe Liu(co-first author)***, Chunyang Chen, Junjie Wang, Yangguang Xue, Boyu Wu, Libin Wu, Qing Wang
1. [FSE 2025] **Standing on the Shoulders of Giants: Bug-Aware Automated GUI Testing via Retrieval Augmentation**  
   ACM International Conference on the Foundations of Software Engineering (CCF-A)  
   Mengzhuo Chen, ***Zhe Liu(co-first author)***, Chunyang Chen, Junjie Wang, Boyu Wu, Jun Hu, Qing Wang
1. [TSE 2025] **One Sentence Can Kill the Bug: Auto-replay Mobile App Crashes from One-sentence Overviews**  
   IEEE Transactions on Software Engineering (CCF-A)  
   Yuchao Huang, Junjie Wang, **Zhe Liu**, Mingyang Li, Song Wang, Chunyang Chen, Yuanzhe Hu, Qing Wang
1. [TOSEM 2024] **Deep API Sequence Generation via Golden Solution Samples and API Seeds**  
   ACM Transactions on Software Engineering and Methodology (CCF-A)  
   Yuekai Huang, Junjie Wang, Song Wang, Moshi Wei, Lin Shi, ***Zhe Liu***, Qing Wang
1. [TSE 2024] **Software Testing with Large Language Models: Survey, Landscape, and Vision**  
   IEEE Transactions on Software Engineering (CCF-A)  
   Junjie Wang, Yuchao Huang, Chunyang Chen, ***Zhe Liu***, Song Wang, Qing Wang
1. [CHI 2024] 🏆 **Unblind Text Inputs: Predicting Hint-text of Text Input in Mobile Apps via LLM**    
   2024 CHI Conference on Human Factors in Computing Systems (CCF-A)  
   ***Zhe Liu***, Chunyang Chen, Junjie Wang, Mengzhuo Chen, Boyu Wu, Yuekai Huang, Jun Hu, Qing Wang
1. [ICSE 2024] **Make LLM a Testing Expert: Bringing Human-like Interaction to Mobile GUI Testing via Functionality-aware Decisions**
   IEEE/ACM 46th International Conference on Software Engineering (CCF-A)  
   ***Zhe Liu***, Chunyang Chen, Junjie Wang, Mengzhuo Chen, Boyu Wu, Xing Che, Dandan Wang, Qing Wang
1. [ICSE 2024] **Testing the Limits: Unusual Text Inputs Generation for Mobile App Crash Detection with Large Language Model**  
   IEEE/ACM 46th International Conference on Software Engineering (CCF-A)  
   ***Zhe Liu***, Chunyang Chen, Junjie Wang, Mengzhuo Chen, Boyu Wu, Zhilin Tian, Yuekai Huang, Jun Hu, Qing Wang
1. [ICSE 2024] **CrashTranslator: Automatically Reproducing Mobile Application Crashes Directly from Stack Trace**  
   IEEE/ACM 46th International Conference on Software Engineering (CCF-A)  
   Yuchao Huang, Junjie Wang, ***Zhe Liu***, Yawen Wang, Song Wang, Chunyang Chen, Yuanzhe Hu, Qing Wang  
1. [ICSE 2023] **Fill in the blank: Context-aware automated text input generation for mobile gui testing**  
   IEEE/ACM 45th International Conference on Software Engineering (CCF-A)  
   ***Zhe Liu***, Chunyang Chen, Junjie Wang, Xing Che, Yuekai Huang, Jun Hu, Qing Wang
1. [ICSE 2023] **Ex pede Herculem: Augmenting Activity Transition Graph for Apps via Graph Convolution Network**  
   IEEE/ACM 45th International Conference on Software Engineering (CCF-A)  
   ***Zhe Liu***, Chunyang Chen, Junjie Wang, Yuhui Su, Yuekai Huang, Jun Hu, Qing Wang
1. [ICSE 2023] **Context-aware Bug Reproduction for Mobile Apps**  
   IEEE/ACM 45th International Conference on Software Engineering (CCF-A)  
   Yuchao Huang, Junjie Wang, ***Zhe Liu***, Song Wang, Chunyang Chen, Mingyang Li, Qing Wang
1. [ICSE-Demo 2022] **NaviDroid: A tool for Guiding Manual Android Testing via Hint Moves**  
   IEEE/ACM 44th International Conference on Software Engineering - Demo (CCF-A)  
   Zhe Liu, Chunyang Chen, Junjie Wang, Yuhui Su, Qing Wang  
1. [ASE 2022] **The Metamorphosis: Automatic Detection of Scaling Issues for Mobile Apps**  
   IEEE/ACM 37th International Conference on Automated Software Engineering (CCF-A)  
   Yuhui Su, Chunyang Chen, Junjie Wang, ***Zhe Liu***, Dandan Wang, Shoubin Li, Qing Wang
1. [CHI 2022] **Guided Bug Crush: Assist Manual GUI Testing of Android Apps via Hint Moves**  
   2022 CHI Conference on Human Factors in Computing Systems (CCF-A)  
   ***Zhe Liu***, Chunyang Chen, Junjie Wang, Yuekai Huang, Jun Hu, Qing Wang
1. [TSE 2022] **Nighthawk: Fully Automated Localizing UI Display Issues via Visual Understanding**  
   IEEE Transactions on Software Engineering (CCF-A)  
   ***Zhe Liu***, Chunyang Chen, Junjie Wang, Yuekai Huang, Jun Hu, Qing Wang
1. [FSE-Demo 2020] **OwlEyes-online: A Fully Automated Platform for Detecting and Localizing UI Display Issues**  
   29th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering (CCF-A)  
   Yuhui Su\*, ***Zhe Liu\****, Chunyang Chen, Junjie Wang, Yuekai Huang, Jun Hu, Qing Wang
1. [ASE 2020] **Owl Eyes: Spotting UI Display Issues via Visual Understanding**  
   IEEE/ACM 35th International Conference on Automated Software Engineering (CCF-A)  
   ***Zhe Liu***, Chunyang Chen, Junjie Wang, Yuekai Huang, Jun Hu, Qing Wang
1. [软件学报 2020] **移动应用程序中用户界面显示缺陷检测的经验研究**  
   Journal of Software (软件学报)  
   ***Zhe Liu***, Chunyang Chen, Junjie Wang, Xing Che, Yuhui Su, Qing Wang
1. [ESEM 2021] **Characterizing and Predicting Good First Issues**  
   ACM/IEEE 15th International Symposium on Empirical Software Engineering and Measurement (CCF-B)  
   Yuekai Huang, Junjie Wang, Song Wang, ***Zhe Liu***, Dandan Wang, Qing Wang
1. [ESEM 2020] **Quest for The Golden Approach: An Experimental Evaluation of Duplicate Crowdtesting Reports Detection**  
   ACM/IEEE 14th International Symposium on Empirical Software Engineering and Measurement (CCF-B)  
   Yuekai Huang, Junjie Wang, Song Wang, ***Zhe Liu***, Yuanzhe Hu, Qing Wang


# 🎖 Honors and Awards
1. *2025*: 🎖 Distinguished Reviewer Award in ASE‘25
2. *2024*: 🎖 ACM Best　Paper　Honourable　Mention in CHI’24
3. *2024*: 🎖 CCF-软件工程专业委员会优秀博士论文激励计划
4. *2024*: 🎖 中国科学院优秀博士论文
5. *2023*: 🏆 The ACM Student Research Competition (SRC) 2023 **Grand Finals Winners**, ***1st Place***, Graduate Category.
6. *2023*: 🎖 中国科学院院长优秀奖
7. *2023*: 🎖 北京市优秀毕业生
8. *2023*: 🎖 北京市三好学生
9. *2023*: 🎖 中国科学院大学优秀毕业生
10. *2023*: 🎖 中国科学院大学优秀学生干部
11. *2023*: 🎖 中国科学院大学优秀共青团员
12. *2022*: 🏆 The ACM Student Research Competition (SRC) at ICSE 2022, ***1st Place***, Graduate Category.
13. *2022*: 🎖 中国科学院大学三好学生标兵
14. *2022*: 🎖 中国科学院大学优秀学生干部
15. *2022*: 🎖 中国科学院软件研究所学术年会优秀海报奖
16. *2021*: 🎖 博士研究生国家奖学金
17. *2021*: 🎖 中国科学院大学三好学生标兵
18. *2021*: 🎖 中国科学院大学优秀学生干部
19. *2021*: 🎖 中国科学院软件研究所学术年会优秀海报奖
20. *2020*: 🏆 The ACM Student Research Competition (SRC) at ASE 2020, ***1st Place***, Graduate Category.
21. *2020*: 🎖 硕士研究生国家奖学金
22. *2020*: 🎖 中国科学院大学三好学生

# 📃 Educations
- *2018.09 - 2023.06*, PHD, University of Chinese Academy of Sciences. 
- *2014.09 - 2018.06*, Undergraduate, Sichuan University.
- *2011.09 - 2014.06*, High-school, Zhengzhou Foreign Language School.

# 📖 Educations
- *2018.09 - 2023.06*, PHD, University of Chinese Academy of Sciences. 
- *2014.09 - 2018.06*, Undergraduate, Sichuan University.
- *2011.09 - 2014.06*, High-school, Zhengzhou Foreign Language School.

# 🗄 Projects
- *2019 - 2022*, National Key Research and Development Program of China
- *2021 - 2024*, National Natural Science Foundation of China Grant
- *2023 - 2027*, National Natural Science Foundation of China Grant
- *2023 - 2024*, Populus Innovation Research Funding

# 📷 Interests
## 🖼 Personal photography
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">喀纳斯湖</div><img src='images/kanasi-a.png' alt="sym" width="70%"></div></div><div class='paper-box-image'><div><div class="badge">喀纳斯卧龙湾</div><img src='images/kanasi-b.png' alt="sym" width="70%"></div></div><div class='paper-box-image'><div><div class="badge">喀拉峻大草原</div><img src='images/kalajun.png' alt="sym" width="70%"></div></div><div class='paper-box-image'><div><div class="badge">慕田峪长城</div><img src='images/mutianyu.png' alt="sym" width="70%"></div></div><div class='paper-box-image'><div><div class="badge">五彩滩</div><img src='images/wucaitan.png' alt="sym" width="70%"></div></div><div class='paper-box-image'><div><div class="badge">七彩丹霞</div><img src='images/danxia.png' alt="sym" width="70%"></div></div><div class='paper-box-image'><div><div class="badge">长白山天池</div><img src='images/changbaishan.png' alt="sym" width="70%"></div></div>
<div class='paper-box-image'><div><div class="badge">茶卡盐湖</div><img src='images/chaka.png' alt="sym" width="70%"></div></div>
</div>

# 🗺 Visitors
<p align="left"><script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=700&t=tt&d=ESc1V1AObl8jPnR3gUeBjEmEFdqy12qTEJjxeSu1b84'></script></p>
