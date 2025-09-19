---
permalink: /
title: "Wentao's Page"
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

I'm Wentao DONG (董文韬, pronounced like "when-top-down"), a Postdoctoral Fellow at The Laboratory for AI-Powered Financial Technologies Limited (AIFT). I earned my Ph.D. degree in Computer Science from City University of Hong Kong under the supervision of Prof. Cong WANG. 

My research advances secure computation—covering MPC, oblivious algorithms, and adjacent primitives—toward higher efficiency, stronger privacy, and adversarial robustness. Recently, I have pursued upward extensions to the application layer (especially the secure AI/LLM infrastructure and private <span style="color:rgb(207, 205, 205);">Non-</span>KYC services for the stablecoin ecosystem) and downward extensions to the fundamental network/computation layer (architectures optimized/aligned for secure computation).

<!-- My research focuses on advancing secure computation—covering multi-party computation, oblivious algorithms, and related techniques—by improving efficiency, enhancing privacy, and achieving robust adversarial resilience. Recently, I have been exploring secure infrastructure for trustworthy LLM/AI ecosystems. -->

Beyond academia, I also work on several "research-to-impact" initiatives that aim to translate privacy and security research into deployable systems and industry collaborations.
<!-- I lead several ventures. _XCrypt@CityUHK_, a secure computation startup seed-funded by the HK Tech 300-HKSTP Ideation Joint Programs, focuses on building practical, privacy-preserving solutions grounded in cryptographic principles. Concurrently, I am also working on _NexaGuard Labs@HKUST-GZ_, which specializes in secure, auditable intelligent network routing services for the next-generation Internet. -->

# Research Interests

- **Secure Computation** (Multi-Party Computation, Oblivious RAM, Trusted Execution Environment, etc.)

- **Anonymous Communication** (Sender/Receiver Anonymity, Metadata Privacy, etc.)

- **Privacy-Preserving Analytics & ML** (Multi-Party Computation, Differential Privacy, Secure Inference/Training, etc.)

<!-- - **Secure AI/LLM Infrastructure** (LLM Toolchain Security, etc.) -->

<p style="margin: 0 0 2rem 0; font-size: 0.9em; color: #666; font-style: italic;">The figure below depicts how my research directions are interconnected and how they collectively drive research-to-impact.</p>

<div style="text-align: center;">
    <img src="images/myall.png" alt="Research Map" style="width: 100%; height: auto;">
</div>

<!-- # News
- *2025.03*: &nbsp;🎉 Our paper "Do Not Skip over the Offline: Verifiable Silent Preprocessing from Small Security Hardware" was accepted by IEEE TIFS'25! 

- *2025.02*: &nbsp;🎉 Our paper "H2O2RAM: A High-Performance Hierarchical Doubly Oblivious RAM" was accepted by USENIX Security'25! 

- *2024.10*: &nbsp;🎉 Our paper "Ring of Gyges: Accountable Anonymous Broadcast via Secret-Shared Shuffle!" was accepted by NDSS'25! 

- *2024.09*: &nbsp;🎉 Our paper "Ring of Gyges: Accountable Anonymous Broadcast via Secret-Shared Shuffle!" was accepted by NDSS'25! -->

<span class='anchor' id='-publications'></span>
# Selected Publications

### Journal Papers

- **Do Not Skip over the Offline: Verifiable Silent Preprocessing from Small Security Hardware**,<br>
<span style="font-size: 0.9em;">**Wentao Dong**, Lei Xu, Leqian Zheng, Huayi Duan, Cong Wang, and Qian Wang.</span><br>
<span style="font-size: 0.9em; font-style: italic;">IEEE Transactions on Information Forensics and Security, Vol. 20 (IEEE TIFS'25).</span><span style="font-size: 0.9em;"><a href="https://ieeexplore.ieee.org/document/10938283" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Paper]</a></span>


### Conference Papers

- **Doppio: Communication-Efficient and Secure Multi-Party Shuffle Differential Privacy**,<br>
<span style="font-size: 0.9em;">**Wentao Dong**, Yang Cao, Cong Wang, and Wei-Bin Lee.</span><br>
<span style="font-size: 0.9em; font-style: italic;">The 52nd International Conference on Very Large Data Bases (VLDB'26).</span><span style="font-size: 0.9em;"><a href="/about" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link-gray">[To appear]</a><a href="https://github.com/dongdongdoge/mpsdp.git" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link-gray">[Code]</a></span>

- **H$_2$O$_2$RAM: A High-Performance Hierarchical Doubly Oblivious RAM**,<br>
<span style="font-size: 0.9em;">Leqian Zheng, Zheng Zhang, **Wentao Dong**, Yao Zhang, Ye Wu, and Cong Wang.</span><br>
<span style="font-size: 0.9em; font-style: italic;">The 34th USENIX Security Symposium (USENIX Security'25).</span><span style="font-size: 0.9em;"><a href="https://www.usenix.org/conference/usenixsecurity25/presentation/zheng" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Paper]</a><a href="https://github.com/55199789/ORAM.git" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Code]</a><a href="/others/H2O2RAM_Poster.pdf" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Poster]</a><a href="/others/H2O2RAM_Slides.pdf" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Slides]</a></span>

- **Ring of Gyges: Accountable Anonymous Broadcast via Secret-Shared Shuffle**,<br>
<span style="font-size: 0.9em;">**Wentao Dong**, Peipei Jiang, Huayi Duan, Cong Wang, Lingchen Zhao, and Qian Wang.</span><br>
<span style="font-size: 0.9em; font-style: italic;">The 32nd Network and Distributed System Security Symposium (NDSS'25).</span><span style="font-size: 0.9em;"><a href="https://www.ndss-symposium.org/ndss-paper/ring-of-gyges-accountable-anonymous-broadcast-via-secret-shared-shuffle/" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Paper]</a><a href="/others/NDSS25_Demo_compressed.mp4" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Demo]</a><a href="/others/NDSS25_Poster.pdf" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Poster]</a><a href="/others/NDSS25_Slides.pdf" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Slides]</a></span>

- **HiddenTor: Toward a User-Centric and Private Query System for Tor BridgeDB**,<br>
<span style="font-size: 0.9em;">Yichen Zang, Chengjun Cai, **Wentao Dong**, Lei Xu, and Cong Wang.</span><br>
<span style="font-size: 0.9em; font-style: italic;">The 44th IEEE International Conference on Distributed Computing Systems (IEEE ICDCS'24).</span><span style="font-size: 0.9em;"><a href="https://ieeexplore.ieee.org/document/10630991" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Paper]</a></span>

- **VizardFL: Enabling Private Participation in Federated Learning Systems**,<br>
<span style="font-size: 0.9em;">Yichen Zang, Chengjun Cai, **Wentao Dong**, and Cong Wang.</span><br>
<span style="font-size: 0.9em; font-style: italic;">The 25th International Conference on Web Information Systems Engineering (WISE'24).</span><span style="font-size: 0.9em;"><a href="https://link.springer.com/chapter/10.1007/978-981-96-0567-5_18" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Paper]</a></span>

- **Poster: Towards Lightweight TEE-Assisted MPC**,<br>
<span style="font-size: 0.9em;">**Wentao Dong** and Cong Wang.</span><br>
<span style="font-size: 0.9em; font-style: italic;">The 30th ACM SIGSAC Conference on Computer and Communications Security (ACM CCS'23).</span><span style="font-size: 0.9em;"><a href="https://dl.acm.org/doi/10.1145/3576915.3624398" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Paper]</a><a href="/others/CCS23_Poster.pdf" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Poster]</a></span>

### Preprints

<!-- - **Communication-Efficient and Secure Multi-Party Shuffle Differential Privacy**, <span style="float:right;"><a href="/about" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
<span style="font-size: 0.9em;">**Wentao Dong**, Yang Cao, Cong Wang, and Wei-Bin Lee.</span><br>
<span style="font-size: 0.9em; font-style: italic;">arXiv Preprint (2025).</span>

*The 52nd International Conference on Very Large Data Bases (VLDB'26).* -->

<!-- - **Fast TEE-Shielded Inference for On-Device Model Protection**, <span style="float:right;"><a href="/about" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
Zikai Mao, Lingchen Zhao, Lei Xu, **Wentao Dong**, Shenyi Zhang, Cong Wang, and Qian Wang.<br>
*arXiv Preprint (2025).*
*The 32nd ACM SIGSAC Conference on Computer and Communications Security (ACM CCS'25).*  -->

- **Metadata-private Messaging without Coordination**,<br>
<span style="font-size: 0.9em;">Peipei Jiang, Yihao Wu, Lei Xu, **Wentao Dong**, Peiyuan Chen, Yulong Ming,
Cong Wang, Xiaohua Jia, and Qian Wang.</span><br>
<span style="font-size: 0.9em; font-style: italic;">arXiv Preprint (2025).</span><span style="font-size: 0.9em;"><a href="https://arxiv.org/abs/2504.19566" target="_blank" rel="noopener" aria-label="external link" title="Open link" class="paper-link">[Paper]</a></span>

<span class='anchor' id='-experiences'></span>
# Experiences

### Educations
- *2021.03 - 2025.07*, City University of Hong Kong, Ph.D. in Computer Science. 
- *2014.09 - 2018.07*, Shanghai Jiao Tong University, B.Eng. in Computer Science and Technology. 

### Work Experiences
- *2020.09 - 2021.03*, City University of Hong Kong, Research Assistant. 
- *2020.01 - 2020.08*, Sangfor Technologies Inc., Software Engineer.
- *2018.07 - 2019.12*, Intel Asia-Pacific R&D Center, R&D Engineer.
- *2018.02 - 2019.06*, Intel Asia-Pacific R&D Center, Software Engineer Intern.
- *2017.06 - 2017.09*, Lab of Cryptology and Computer Security (LoCCS), Shanghai Jiao Tong University, Research Intern.

<span class='anchor' id='-teaching-and-service'></span>
# Teaching and Services

### Teaching Assistant
- *2021*, TA for CS3504 IT Professional Placement (Undergraduate).
- *2022*, TA for CS3402 Database Systems (Undergraduate).
- *2023,2024*, TA for CS2311 Computer Programming (Undergraduate).
- *2025*, TA and course developer for CS2311 Computer Programming (Undergraduate).
  
### Community Service
- Serve as a reviewer for IEEE IoTJ, IEEE TSC.
- Serve as an external reviewer for IEEE S&P, USENIX Security, IEEE INFOCOM, IEEE TDSC, ACM MM, ESORICS, IEEE ICNP, ACM AsiaCCS, IEEE ICDCS, ICICS, WPES, etc.
- Serve as a student helper for IEEE ICDCS'23.