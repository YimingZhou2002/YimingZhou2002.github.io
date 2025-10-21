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

# 🧑‍💼 About Me

Hi,I'm **Yiming Zhou**,I'm currently working as a Ph.D. student at the School of Software, Tsinghua University, majoring in Software Engineering. My research interests lie in computer network systems, computer vision, and artificial intelligence. I received my Bachelor’s degree in Computer Science from the University of Electronic Science and Technology of China (UESTC).

Currently, I am working under the supervision of Professor Zhenhua Li on topics related to computer networks, operating systems, and cloud computing. I am actively involved in the National Natural Science Foundation of China (NSFC) Project No. 62332012, Distributed Microkernel Operating Systems and Key Technologies, and my recent work also focuses on accelerating large language model (LLM) training and inference.

During my undergraduate studies, I ranked first among 137 students with a GPA of 4.00/4.00, and received multiple honors, including the Xiaomi Scholarship and the Eleventh Science and Technology Progress Scholarship. I was also awarded National Second Prizes in the Electronic Design Competition and the Embedded Chip and System Design Competition.

Previously, I worked as a Research Intern at the Future Media Research Center, UESTC, under the supervision of Professor Xing Xu, where I explored topics in computer vision and artificial intelligence, particularly focusing on industrial anomaly detection and pattern recognition. Our proposed model, VQ-Flow, achieved higher performance than the previously released DiAD model (AAAI 2024).

Beyond research, I am also actively involved in student affairs and leadership. I served as the Party Secretary of the Second Party Branch at Yingcai Honors College and participated in an exchange program at the Massachusetts Institute of Technology (MIT) during my undergraduate studies. I have achieved strong English proficiency as well, with an IELTS score of 7.5, a TOEFL score of 105, and a CET-6 score of 640.

**Feel free to reach out to me via email at yiming_zhou2002@163.com.** I am always eager to connect and explore new opportunities for collaboration and growth.
<!--
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 I have joined Prof. Zhenhua Li at School of Software, Tsinghua University. 


# 📚 Publications & Projects

## Publications

- **VQ-Flow: Taming Normalizing Flows for Multi-Class Anomaly Detection** *(October 2023 - March 2024)*
  - VQ-Flow constructs a unified framework for multi-class anomaly detection, applying flow models for the first time in this field. It consists of a multi-layer feature extractor, multi-layer flow models, and a series of feature codebooks. By employing quantization and fitting feature codebooks to mixed Gaussian distributions, VQ-Flow enhances the model's ability to reconstruct multi-class features.
  - Achieved superior performance on the MVTec AD dataset and the VisA dataset compared to the current state-of-the-art model (DiAD AAAI2024 by Tencent Lab). 
  - Responsible for building the feature extractor, implementing the model, and conducting related experiments.

## Projects

- **Smart Guidance Helmet** *(March 2023 - August 2023)*
  - National Second Prize, National University Embedded Chip and System Design Competition.
  - Utilized the OpenMV embedded system with MicroPython runtime environment and various peripherals to provide diverse navigation and obstacle avoidance services for the visually impaired.
  - Developed obstacle avoidance and pathfinding functionalities using depth estimation models (MiDaS) and text-to-speech capabilities through OCR text recognition.
  - Responsible for system design, construction, and programming.
- **Distributed Microkernel Operating Systems & Key technologies** *(October 2024 - June 2026)*
  - Nation Science Foundation of China Project, under grant NSFC 62332012.
  - Develop secure and efficient Microkernel System.
- **Inductance-Capacitance Measurement Device** *(June 2023 - August 2023)*
  - National Second Prize, National University Electronic Design Competition.
  - Designed a set of measurement devices for capacitance and inductance based on bridge method and LC series network resonance method.
  - Achieved accurate and wide-ranging measurement of capacitance and inductance.
  - Responsible for system design, circuit construction, and report writing.
- **Infrared Gesture Recognition System Based on Artificial Intelligence** *(September 2022 - September 2023)*
  - Led a university innovation and entrepreneurship project.
  - Constructed an infrared receiver array and processed the collected infrared gesture features using LSTM, VGG, and other neural networks to obtain gesture category information.
  - Successfully completed and approved by the university.
  - Responsible for building the receiver array, deploying driving algorithms, and initial research and construction of neural networks.

<!--
# 📝 Publications & Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->

# 🏆 Honors and Awards
- **2025**
  - Outstanding university graduates, Department of Education, Sichuan Province
  - Outstanding university graduates, UESTC
  - Outstanding party member, Yingcai Honors College

- **2023**
  - National Second Prize, National University Electronic Design Competition
  - National Second Prize, National Embedded Chip and System Design Competition
  - Eleventh Technology Progress Scholarship
  - Third Prize, National College English Competition
  - First Prize (School Level), Outstanding Student Scholarship

- **2022**
  - Xiaomi Scholarship
  - Second Prize (Provincial Level), National Software and Information Technology Professionals Competition (Lanqiao Cup)
  - First Prize (School Level), Outstanding Student Scholarship

# 📖 Educations
- *2021.09 - 2025.06*, Bachelor of Computer Science and Technology, Yingcai Honors College, University of Electronic Science and Technology of China, Chengdu, China.
- *2025.09 - 2030.06 (expected)*, PhD of Software Engineering, School of Software, Tsinghua University, Beijing, China.

# 💬 Public Services
- *2024.06-2025.06*, Party Secretary, Second Party branch, in responsible for organizational matters.
  
# 💻 Internships
- *2022.05 - 2024.06*, Future Media Research Center, University of Electronic Science and Technology of China, Chengdu, China. Supervised by Professor Xing Xu.


# 📞 Contact
- **Email**: yiming_zhou2002@163.com  
- **Phone**: (+86)18633065878
- **QQ**: 768263769
- **Wechat**: search for my phone number

