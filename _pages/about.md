---
permalink: /
title: "Wentao Dong's Page"
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

I'm Wentao Dong (董文韬), a Ph.D. candidate in Computer Science at City University of Hong Kong, advised by [Prof. Cong Wang](https://www.cs.cityu.edu.hk/~congwang/).
My research focuses on making secure computation—including multi-party computation, oblivious RAM, and related techniques—more efficient, strengthening privacy, and turning adversarial resilience into reality.
Recently, I have been exploring secure infrastructure for trustworthy LLM/AI ecosystems.

Outside academia, I lead [XCrypt](\about), a secure computation startup project seed-funded by HK Tech 300 and the HKSTP Ideation Program, delivering practical privacy-preserving solutions rooted in cryptographic principles.

<!-- <div class="accordion">

  <div class="accordion-item">
    <div class="accordion-header">Secure Computation Systems</div>
    <div class="accordion-content">

      <div class="paper">
        <span class="highlight">TEE-assisted Secure Computation:</span> 
        Verifiable MPC Preprocessing (<b>TIFS'25</b>: Verifiable Silent Preprocessing, <b>CCS'23 Poster</b>: Lightweight TEE-assisted MPC); 
        Secure RAM Architectures (<b>USENIX Sec'25</b>: H₂O₂RAM - High-Performance Oblivious RAM)
      </div>

      <div class="paper">
        <span class="highlight">Anonymous Communication Systems:</span> 
        Accountable Broadcast (<b>NDSS'25</b>: Ring of Gyges); 
        Metadata-Private Queries (<b>ICDCS'24</b>: HiddenTor); 
        Decentralized Messaging (<b>arXiv'25</b>: Metadata-Private Messaging without Coordination)
      </div>

      <div class="paper">
        <span class="highlight">Privacy-Preserving Data Analytics:</span> 
        <b>VLDB'26</b>: Communication-Efficient Multi-Party Shuffle DP
      </div>

      <div class="paper">
        <span class="highlight">Privacy-Preserving Machine Learning (PPML):</span> 
        <b>WISE'24</b>: VizardFL - Private Participation in FL
      </div>

    </div>
  </div>

</div> -->


<!-- # Research Overview:
```c++
Secure Computation Systems
├── TEE-assisted Secure Computation
│   ├── Verifiable MPC Preprocessing
│   │    ├── TIFS'25: Verifiable Silent Preprocessing
│   │    └── CCS'23 Poster: Lightweight TEE-assisted MPC
│   └── Secure RAM Architectures
│        └── USENIX Sec'25: H₂O₂RAM - High-Performance Oblivious RAM
│
├── Anonymous Communication Systems
│   ├── Accountable Broadcast
│   │    └── NDSS'25: Ring of Gyges
│   ├── Metadata-Private Queries
│   │    └── ICDCS'24: HiddenTor
│   └── Decentralized Messaging
│        └── arXiv'25: Metadata-Private Messaging without Coordination
│
├── Privacy-Preserving Data Analytics
│    └── VLDB'26: Communication-Efficient Multi-Party Shuffle DP
│
└── Privacy-Preserving Machine Learning (PPML)
     └── WISE'24: VizardFL - Private Participation in FL
``` -->

<!-- # News
- *2025.03*: &nbsp;🎉 Our paper "Do Not Skip over the Offline: Verifiable Silent Preprocessing from Small Security Hardware" was accepted by IEEE TIFS'25! 

- *2025.02*: &nbsp;🎉 Our paper "H2O2RAM: A High-Performance Hierarchical Doubly Oblivious RAM" was accepted by USENIX Security'25! 

- *2024.10*: &nbsp;🎉 Our paper "Ring of Gyges: Accountable Anonymous Broadcast via Secret-Shared Shuffle!" was accepted by NDSS'25! 

- *2024.09*: &nbsp;🎉 Our paper "Ring of Gyges: Accountable Anonymous Broadcast via Secret-Shared Shuffle!" was accepted by NDSS'25! -->

<span class='anchor' id='-publications'></span>
# Selected Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

### Conference Papers

- "[_H2O2RAM: A High-Performance Hierarchical Doubly Oblivious RAM_](https://www.usenix.org/conference/usenixsecurity25/presentation/zheng),"
Leqian Zheng, Zheng Zhang, **Wentao Dong**, Yao Zhang, Ye Wu, and Cong Wang,
USENIX Security 2025.

- "[_Ring of Gyges: Accountable Anonymous Broadcast via Secret-Shared Shuffle_](https://www.ndss-symposium.org/ndss-paper/ring-of-gyges-accountable-anonymous-broadcast-via-secret-shared-shuffle/),"
**Wentao Dong**, Peipei Jiang, Huayi Duan, Cong Wang, Lingchen Zhao, and Qian Wang, ISOC NDSS 2025.

- "[_HiddenTor: Toward a User-Centric and Private Query System for Tor BridgeDB_](https://ieeexplore.ieee.org/document/10630991),"
Yichen Zang, Chengjun Cai, **Wentao Dong**, Lei Xu, and Cong Wang,
IEEE ICDCS 2024.

- "[_VizardFL: Enabling Private Participation in Federated Learning Systems_](https://link.springer.com/chapter/10.1007/978-981-96-0567-5_18),"
Yichen Zang, Chengjun Cai, **Wentao Dong**, and Cong Wang,
WISE 2024.

- "[_Towards Lightweight TEE-Assisted MPC_](https://dl.acm.org/doi/10.1145/3576915.3624398),"
**Wentao Dong** and Cong Wang,
ACM CCS 2023 (Poster).

### Journal Papers

- "[_Do Not Skip over the Offline: Verifiable Silent Preprocessing from Small Security Hardware_](https://ieeexplore.ieee.org/document/10938283),"
**Wentao Dong**, Lei Xu, Leqian Zheng, Huayi Duan, Cong Wang, and Qian Wang,IEEE TIFS 2025.

### Preprints

- "[_Communication-Efficient and Secure Multi-Party Shuffle Differential Privacy_](/about),"
**Wentao Dong**, Yang Cao, Cong Wang, and Wei-Bin Lee,
arXiv Preprint (2025).

- "[_Metadata-private Messaging without Coordination_](https://arxiv.org/abs/2504.19566),"
Peipei Jiang, Yihao Wu, Lei Xu, **Wentao Dong**, Peiyuan Chen, Yulong Ming,
Cong Wang, Xiaohua Jia, and Qian Wang, arXiv Preprint (2025).

<!-- <span class='anchor' id='-projects'></span>
# Projects
- [SCION](https://scion-architecture.net/) (Scalability, Control, and Isolation on Next-generation Networks) Project, Hong Kong Node — Coordination Team Member.
- [XCrypt](\about) Project, HKSTP & HK Tech 300 Seed-Funded Project — PIC. -->

<!-- - [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<span class='anchor' id='-experiences'></span>
# Experiences

### Educations
- *2021.03 - now*, City University of Hong Kong, PhD in Computer Science. 
- *2014.09 - 2018.07*, Shanghai Jiao Tong University, BEng in Computer Science and Technology. 

### Work Experiences
- *2020.09 - 2021.03*, City University of Hong Kong, Research Assistant. 
- *2020.01 - 2020.08*, Sangfor Technologies Inc., Software Engineer.
- *2018.07 - 2019.12*, Intel Asia-Pacific R&D Center, R&D Engineer.

<span class='anchor' id='-teaching-and-services'></span>
# Teaching and Services

### Teaching Assistant
- *2021*, TA for CS3504 IT Professional Placement (Undergraduate).
- *2022*, TA for CS3402 Database Systems (Undergraduate).
- *2023,2024,2025*, TA for CS2311 Computer Programming (Undergraduate).
  
### Community Services
- Reviewer for IEEE IoTJ, TSC.
- External Reviewer for IEEE TDSC, USENIX Security, ACM AsiaCCS, IEEE ICDCS.
 
<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->