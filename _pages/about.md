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

I am Kanzhi Cheng (程瞰之), a PhD student (2021.9 - ) in the <a href='http://nlp.nju.edu.cn/homepage/'>NLP Group</a> at Nanjing University, advised by <a href='https://cs.nju.edu.cn/chenjiajun/'>Dr. Jiajun Chen</a> & <a href='https://cs.nju.edu.cn/zhangjb/'>Dr. Jianbing Zhang</a>. Previously, I worked as a research intern at Shanghai AI Lab and Microsoft Research. I am deeply grateful for the opportunity to work with and learn from <a href='https://lividwo.github.io/zywu.github.io/'>Dr. Zhiyong Wu</a> and <a href='https://qianhuiwu.github.io/'>Dr. Qianhui Wu</a>.

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


- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
