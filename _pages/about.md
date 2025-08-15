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

I'm Wentao DONG (董文韬, pronounced like "win top-down"), a Postdoctoral Fellow at The Laboratory for AI-Powered Financial Technologies Limited (AIFT). I earned my Ph.D. degree in Computer Science from City University of Hong Kong under the supervision of Prof. Cong Wang. 

My research focuses on advancing secure computation—covering multi-party computation, oblivious algorithms, and related techniques—by improving efficiency, enhancing privacy, and achieving robust adversarial resilience. Recently, I have been exploring secure infrastructure for trustworthy LLM/AI ecosystems.

Beyond academia, I lead [XCrypt](https://xxx), a secure computation startup seed-funded by HK Tech 300 and the HKSTP Ideation Programs, building practical privacy-preserving solutions grounded in cryptographic principles.

# Research Interests

<div style="margin: 2.5rem 0 1rem 0;">
    <h4 style="margin: 0 0 1rem 0; color: #2c3e50;">Research Areas</h4>
    <ul style="margin: 0 0 2rem 0; padding-left: 1.2rem;">
        <li style="margin-bottom: 0.5rem;"><strong>Secure Computation (Multi-Party Computation, Oblivious RAM, Trusted Execution Environment, etc.)</strong></li>
        <li style="margin-bottom: 0.5rem;"><strong>Anonymous Communication (Sender/Receiver Anonymity, Metadata Privacy, etc.) </strong></li>
        <li style="margin-bottom: 0.5rem;"><strong>Privacy-Preserving Analytics & ML (Multi-Party Computation, Differential Privacy, Secure Inference/Training, etc.)</strong></li>
        <li style="margin-bottom: 0.5rem;"><strong>Secure AI/LLM Infrastructure (LLM Toolchain Security, etc.)</strong></li>
    </ul>
    <p style="margin: 0 0 2rem 0; font-size: 0.9em; color: #666; font-style: italic;">The figure below simply illustrates the evolution and connections of all these research directions.</p>
    
    <div style="text-align: center;">
        <img src="images/my_maps.png" alt="Research Map" style="width: 90%; height: auto;">
    </div>
</div>

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

<!-- - **Doppio: Communication-Efficient and Secure Multi-Party Shuffle Differential Privacy**, <span style="float:right;"><a href="/about" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
**Wentao Dong**, Yang Cao, Cong Wang, and Wei-Bin Lee.<br>
*The 52nd International Conference on Very Large Data Bases (VLDB'26).*

- **Amulet: Fast TEE-Shielded Inference for On-Device Model Protection**, <span style="float:right;"><a href="/about" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
Zikai Mao, Lingchen Zhao, Lei Xu, **Wentao Dong**, Shenyi Zhang, Cong Wang, and Qian Wang.<br>
*The 32nd ACM SIGSAC Conference on Computer and Communications Security (ACM CCS'25).* -->

- **H$_2$O$_2$RAM: A High-Performance Hierarchical Doubly Oblivious RAM**, <span style="float:right;"><a href="https://www.usenix.org/conference/usenixsecurity25/presentation/zheng" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
Leqian Zheng, Zheng Zhang, **Wentao Dong**, Yao Zhang, Ye Wu, and Cong Wang.<br>
*The 34th USENIX Security Symposium (USENIX Security'25).*

- **Ring of Gyges: Accountable Anonymous Broadcast via Secret-Shared Shuffle**, <span style="float:right;"><a href="https://www.ndss-symposium.org/ndss-paper/ring-of-gyges-accountable-anonymous-broadcast-via-secret-shared-shuffle/" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
**Wentao Dong**, Peipei Jiang, Huayi Duan, Cong Wang, Lingchen Zhao, and Qian Wang.<br>
*The 32nd Network and Distributed System Security Symposium (ISOC NDSS'25).*

- **HiddenTor: Toward a User-Centric and Private Query System for Tor BridgeDB**, <span style="float:right;"><a href="https://ieeexplore.ieee.org/document/10630991" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
Yichen Zang, Chengjun Cai, **Wentao Dong**, Lei Xu, and Cong Wang.<br>
*The 44th IEEE International Conference on Distributed Computing Systems (IEEE ICDCS'24).*

- **VizardFL: Enabling Private Participation in Federated Learning Systems**, <span style="float:right;"><a href="https://link.springer.com/chapter/10.1007/978-981-96-0567-5_18" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
Yichen Zang, Chengjun Cai, **Wentao Dong**, and Cong Wang.<br>
*The 25th International Conference on Web Information Systems Engineering (WISE'24).*

- **Poster: Towards Lightweight TEE-Assisted MPC**, <span style="float:right;"><a href="https://dl.acm.org/doi/10.1145/3576915.3624398" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
**Wentao Dong** and Cong Wang.<br>
*The 30th ACM SIGSAC Conference on Computer and Communications Security (ACM CCS'23).*

### Journal Papers

- **Do Not Skip over the Offline: Verifiable Silent Preprocessing from Small Security Hardware**, <span style="float:right;"><a href="https://ieeexplore.ieee.org/document/10938283" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
**Wentao Dong**, Lei Xu, Leqian Zheng, Huayi Duan, Cong Wang, and Qian Wang.<br>
*IEEE Transactions on Information Forensics and Security, Vol. 20 (IEEE TIFS'25).*

### Preprints

- **Communication-Efficient and Secure Multi-Party Shuffle Differential Privacy**, <span style="float:right;"><a href="/about" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
**Wentao Dong**, Yang Cao, Cong Wang, and Wei-Bin Lee.<br>
*arXiv Preprint (2025).*

<!-- *The 52nd International Conference on Very Large Data Bases (VLDB'26).* -->

- **Fast TEE-Shielded Inference for On-Device Model Protection**, <span style="float:right;"><a href="/about" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
Zikai Mao, Lingchen Zhao, Lei Xu, **Wentao Dong**, Shenyi Zhang, Cong Wang, and Qian Wang.<br>
*arXiv Preprint (2025).*
<!-- *The 32nd ACM SIGSAC Conference on Computer and Communications Security (ACM CCS'25).*  -->

- **Metadata-private Messaging without Coordination**, <span style="float:right;"><a href="https://arxiv.org/abs/2504.19566" target="_blank" rel="noopener" aria-label="external link" title="Open link" style="color: #007acc; text-decoration: none; padding: 4px 8px; border-radius: 4px; transition: all 0.2s ease;"><i class="fas fa-external-link-alt" style="font-size: 14px;"></i></a></span><span style="display:block; clear:both;"></span>
Peipei Jiang, Yihao Wu, Lei Xu, **Wentao Dong**, Peiyuan Chen, Yulong Ming,
Cong Wang, Xiaohua Jia, and Qian Wang.<br>
*arXiv Preprint (2025).*

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