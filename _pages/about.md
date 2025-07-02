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

I am Kanzhi Cheng (程瞰之), a PhD student (2021.9 - ) in the <a href='http://nlp.nju.edu.cn/homepage/'>NLP Group</a> at Nanjing University, advised by <a href='https://cs.nju.edu.cn/chenjiajun/'>Dr. Jiajun Chen</a> & <a href='https://cs.nju.edu.cn/zhangjb/'>Dr. Jianbing Zhang</a>. Previously, I worked as a research intern at Shanghai AI Lab, Tsinghua AIR, and Microsoft Research. I am deeply grateful for the opportunity to work with and learn from <a href='https://lividwo.github.io/zywu.github.io/'>Dr. Zhiyong Wu</a> , <a href='https://zhouh.github.io/'>Dr. Hao Zhou</a>, and <a href='https://qianhuiwu.github.io/'>Dr. Qianhui Wu</a>.

Currently, I am broadly interested in multimodal intelligence, with a focus on:
- **(Multimodal) Autonomous Agents**: particularly GUI agents capable of acting in the digital world to automate complex tasks (<a href='https://github.com/njucckevin/SeeClick/'>SeeClick</a>, <a href='https://osatlas.github.io/'>OS-Atlas</a>, <a href='https://qiushisun.github.io/OS-Genesis-Home/'>OS-Genesis</a>, <a href='https://microsoft.github.io/GUI-Actor/'>GUI-Actor</a>).
- **Large Vision-Language Models**: building multimodal systems that can understand image/video, generate text (<a href='https://caparena.github.io/'>CapArena</a>), and perform reasoning (<a href='https://github.com/njucckevin/MM-Self-Improve'>MM-Self-Improve</a>).

I expect to graduate in 2026. Please feel free to reach out!

# 🔥 News
- *2025.07*: &nbsp;🏖️🏖️ See you at Vienna 🇦🇹! 
- *2025.06*: &nbsp;🤖🤖 We release <a href='https://microsoft.github.io/GUI-Actor/'>GUI-Actor</a> to advance visual grounding for GUI Agents. 
- *2025.05*: &nbsp;🎉🎉 Four papers are accepeted by ACL 2025. 

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 (Main)</div><img src='images/seeclick.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents](https://arxiv.org/abs/2401.10935) \\
**Kanzhi Cheng**, Qiushi Sun, Yougang Chu, Fangzhi Xu, Yantao Li, Jianbing Zhang, Zhiyong Wu

[**Code**](https://github.com/njucckevin/SeeClick) &nbsp;
[**Models&Data**](https://huggingface.co/cckevinn/SeeClick) &nbsp;
[<img src='./images/Logo_of_Twitter.svg.png' style='width: 1.35em;'>](https://x.com/njucckevin/status/1751633110620655851) &nbsp;
[![](https://img.shields.io/github/stars/njucckevin/SeeClick?style=social&label=Code+Stars)](https://github.com/njucckevin/SeeClick)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/guiactor.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[GUI-Actor: Coordinate-Free Visual Grounding for GUI Agents](https://arxiv.org/abs/2506.03143) \\
Qianhui Wu\*, **Kanzhi Cheng**\*, Rui Yang\*, Chaoyun Zhang, Jianwei Yang, Huiqiang Jiang, Jian Mu, Baolin Peng, Bo Qiao, Reuben Tan, Si Qin, Lars Liden, Qingwei Lin, Huan Zhang, Tong Zhang, Jianbing Zhang, Dongmei Zhang, Jianfeng Gao

[**Code**](https://github.com/microsoft/GUI-Actor) &nbsp;
[**Project Page**](https://microsoft.github.io/GUI-Actor/) &nbsp;
[**Models&Data**](https://huggingface.co/microsoft/GUI-Actor-7B-Qwen2-VL) &nbsp;
[<img src='./images/Logo_of_Twitter.svg.png' style='width: 1.35em;'>](https://x.com/njucckevin/status/1930577241244860462) &nbsp;
[![](https://img.shields.io/github/stars/microsoft/GUI-Actor?style=social&label=Code+Stars)](https://github.com/microsoft/GUI-Actor)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 (Main)</div><img src='images/osgenesis.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[OS-Genesis: Automating GUI Agent Trajectory Construction via Reverse Task Synthesis](https://arxiv.org/abs/2412.19723) \\
Qiushi Sun\*, **Kanzhi Cheng**\*, Zichen Ding\*, Chuanyang Jin\*, Yian Wang, Fangzhi Xu, Zhenyu Wu, Chengyou Jia, Liheng Chen, Zhoumianze Liu, Ben Kao, Guohao Li, Junxian He, Yu Qiao, Zhiyong Wu

[**Code**](https://github.com/OS-Copilot/OS-Genesis) &nbsp;
[**Project Page**](https://qiushisun.github.io/OS-Genesis-Home/) &nbsp;
[**Models&Data**](https://huggingface.co/collections/OS-Copilot/os-genesis-6768d4b6fffc431dbf624c2d) &nbsp;
[<img src='./images/Logo_of_Twitter.svg.png' style='width: 1.35em;'>](https://x.com/qiushi_sun/status/1874807124515344599) &nbsp;
[![](https://img.shields.io/github/stars/OS-Copilot/OS-Genesis?style=social&label=Code+Stars)](https://github.com/OS-Copilot/OS-Genesis)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2025 (Main)</div><img src='images/r3v.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[Vision-Language Models Can Self-Improve Reasoning via Reflection](https://arxiv.org/abs/2411.00855) \\
**Kanzhi Cheng**\*, Yantao Li\*, Fangzhi Xu, Jianbing Zhang, Hao Zhou, Yang Liu

[**Code**](https://github.com/njucckevin/MM-Self-Improve) &nbsp;
[<img src='./images/Logo_of_Twitter.svg.png' style='width: 1.35em;'>](https://x.com/njucckevin/status/1859130826832957857) &nbsp;
[![](https://img.shields.io/github/stars/njucckevin/MM-Self-Improve?style=social&label=Code+Stars)](https://github.com/njucckevin/MM-Self-Improve)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 (Findings)</div><img src='images/caparena.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[CapArena: Benchmarking and Analyzing Detailed Image Captioning in the LLM Era](https://arxiv.org/abs/2503.12329) \\
**Kanzhi Cheng**\*, Wenpo Song\*, Jiaxin Fan\*, Zheng Ma, Qiushi Sun, Fangzhi Xu, Chenyang Yan, Nuo Chen, Jianbing Zhang, Jiajun Chen

[**Code**](https://github.com/njucckevin/CapArena) &nbsp;
[**Project Page**](https://caparena.github.io/) &nbsp;
[<img src='./images/Logo_of_Twitter.svg.png' style='width: 1.35em;'>](https://x.com/njucckevin/status/1902547937051467956) &nbsp;
[![](https://img.shields.io/github/stars/njucckevin/CapArena?style=social&label=Code+Stars)](https://github.com/njucckevin/CapArena)

</div>
</div>

- `ACMMM 2023` [Beyond Generic: Enhancing Image Captioning with Real-World Knowledge using Vision-Language Pre-Training Model](https://arxiv.org/abs/2308.01126) <br>
**Kanzhi Cheng**, Wenpo Song, Zheng Ma, Wenhao Zhu, Zixuan Zhu, Jianbing Zhang

- `NLPCC 2022` [ADS-Cap: A Framework for Accurate and Diverse Stylized Captioning with Unpaired Stylistic Corpora](https://arxiv.org/abs/2308.01143) <br>
**Kanzhi Cheng**, Zheng Ma, Shi Zong, Jianbing Zhang, Xinyu Dai, Jiajun Chen

- `WCUA@ICML 2025` [ScienceBoard: Evaluating Multimodal Autonomous Agents in Realistic Scientific Workflows](https://arxiv.org/abs/2505.19897) [![](https://img.shields.io/github/stars/OS-Copilot/ScienceBoard?style=social&label=Code+Stars)](https://github.com/OS-Copilot/ScienceBoard) <br>
Qiushi Sun, Zhoumianze Liu, Chang Ma, Zichen Ding, Fangzhi Xu, Zhangyue Yin, Haiteng Zhao, Zhenyu Wu, **Kanzhi Cheng**, Zhaoyang Liu, Jianing Wang, Qintong Li, Xiangru Tang, Tianbao Xie, Xiachong Feng, Xiang Li, Ben Kao, Wenhai Wang, Biqing Qi, Lingpeng Kong, Zhiyong Wu

- `ACL 2025 (Main)` [Genius: A Generalizable and Purely Unsupervised Self-Training Framework For Advanced Reasoning](https://arxiv.org/abs/2504.08672) [![](https://img.shields.io/github/stars/xufangzhi/Genius?style=social&label=Code+Stars)](https://github.com/xufangzhi/Genius) <br>
Fangzhi Xu, Hang Yan, Chang Ma, Haiteng Zhao, Qiushi Sun, **Kanzhi Cheng**, Junxian He, Jun Liu, Zhiyong Wu

- `ACL 2025 (Main)` [Interative Evolution: A Neural-symbolic Self-Training Framework for Large Language Models](http://arxiv.org/abs/2406.11736) [![](https://img.shields.io/github/stars/xufangzhi/ENVISIONS?style=social&label=Code+Stars)](https://github.com/xufangzhi/ENVISIONS) <br>
Fangzhi Xu, Qiushi Sun, **Kanzhi Cheng**, Jun Liu, Yu Qiao, Zhiyong Wu

- `ICLR 2025 (Spotlight)` [OS-ATLAS: A Foundation Action Model For Generalist GUI Agents](https://arxiv.org/abs/2410.23218) [![](https://img.shields.io/github/stars/OS-Copilot/OS-Atlas?style=social&label=Code+Stars)](https://github.com/OS-Copilot/OS-Atlas) <br>
Zhiyong Wu, Zhenyu Wu, Fangzhi Xu, Yian Wang, Qiushi Sun, Chengyou Jia, **Kanzhi Cheng**, Zichen Ding, Liheng Chen, Paul Pu Liang, Yu Qiao

- `Preprint` [A Survey of Neural Code Intelligence: Paradigms, Advances and Beyond](https://arxiv.org/abs/2403.14734) [![](https://img.shields.io/github/stars/QiushiSun/NCISurvey?style=social&label=Code+Stars)](https://github.com/QiushiSun/NCISurvey) <br>
Qiushi Sun, Zhirui Chen, Fangzhi Xu, Chang Ma, **Kanzhi Cheng**, Zhangyue Yin, Jianing Wang, Chengcheng Han, Renyu Zhu, Shuai Yuan, Pengcheng Yin, Qipeng Guo, Xipeng Qiu, Xiaoli Li, Fei Yuan, Lingpeng Kong, Xiang Li, Zhiyong Wu

# 🎖 Honors and Awards
- *2025.05* Excellent Graduate Student, Nanjing University
- *2024.10* First-Class Graduate Talent Scholarship, Nanjing University
- *2023.10* Outstanding Graduate Award, Nanjing University
- *2021.06* Outstanding Graduation Project, Nanjing University
- *2019.10* Guanghua Scholarship (1%), Nanjing University

# 📖 Educations
- *2021.09 - 2026 (now)*, Ph.D. Student at the Department of Computer Science and Technology, Nanjing University.
- *2017.09 - 2021.06*, B.E. at the School of Management and Engineering, Nanjing University. 

# 💻 Internships
- *2025.04 - 2025.06*, Microsoft Research.
- *2024.08 - 2025.01*, Tsinghua AIR, China.
- *2023.08 - 2024.04*, Shanghai Artificial Intelligence Laboratory, China.

# ⚽️ Personal Interests

I am an amateur football player, primarily playing as an attacking midfielder.As a player, I’ve been fortunate to receive the following honors:
- Member of the Nanjing University official football team
- 🏆 Champion of the 2022–2023 Nanjing University Caigen Cup, awarded Final MVP
- 🏆 Champion of the 2018–2019 Nanjing University FA Cup
I am also a fan of Arsenal Football Club.

<div style="display: flex; gap: 10px; justify-content: center; align-items: flex-start; flex-wrap: wrap;">

  <div style="flex: 1; max-width: 20%; aspect-ratio: 2305/3902; overflow: hidden; border-radius: 10px;">
    <img src="images/football2.png" alt="football1" style="width: 100%; height: 100%; object-fit: cover;">
  </div>

  <div style="flex: 1; max-width: 40%; aspect-ratio: 1230/1075; overflow: hidden; border-radius: 10px;">
    <img src="images/football1.png" alt="football2" style="width: 100%; height: 100%; object-fit: cover;">
  </div>

  <div style="flex: 1; max-width: 40%; aspect-ratio: 1323/1070; overflow: hidden; border-radius: 10px;">
    <img src="images/football3.png" alt="football3" style="width: 100%; height: 100%; object-fit: cover;">
  </div>

</div>
