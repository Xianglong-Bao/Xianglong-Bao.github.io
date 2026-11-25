---
permalink: /
title: ""
excerpt: ""
description: "Xianglong (Shannon) Bao is a PhD researcher at Griffith University working on brain-computer interfaces, EEG, biomedical time series and medical AI."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I'm currently a PhD researcher at **Griffith University** (Brisbane, QLD, Australia).
My research interests are in **brain-computer interfaces** and **medical AI**,
with a focus on physiological signals such as EEG, ECG, and EMG, and on
**biomedical time series** more broadly.

I graduated from **Tianjin University** (Tianjin, China) in 2025. I worked as a
Research Scientist Intern at the **Ping An Technology U.S. Research Institute (PAII)**
(Palo Alto, CA, USA), where I focused on AI4Health.
Previously I worked on neuro-symbolic AI, specifically ontology reasoning and the
decidability and complexity of logics.

<div class="contact-note">
I'm always happy to chat about research, explore potential collaborations, or just connect.
Feel free to reach out at <a href="mailto:xianglong.bao@griffithuni.edu.au">xianglong.bao@griffithuni.edu.au</a> or <a href="images/wechat-qr.png">WeChat</a>.
</div>

# 🔥 News
- *2026.11*: &nbsp;🗒️ Serving as a Program Committee member for the [AAAI 2027 Medical World Models Workshop](https://med-wm.github.io/aaai27-mwm/), Montréal, Canada. [![](https://img.shields.io/badge/CORE-A*-e74c3c)](https://portal.core.edu.au/conf-ranks/?search=AAAI&by=acronym&source=ICORE2026) ![](https://img.shields.io/badge/CCF-A-e74c3c)
- *2026.11*: &nbsp;🏆 Our team won **1st place** (3,711 participants) in the EEG Sleep Onset track of the [NeurIPS 2026 EEG/EMG Foundation Challenge](https://neural-interfaces26.github.io/index.html). Thanks to my teammates!
- *2026.11*: &nbsp;🎉 [iEEG Can Help EEG: Improving Clinical Scalp EEG Analysis through Intracranial Priors](https://arxiv.org/abs/2611.20435) is accepted at **KDD 2027**. [![](https://img.shields.io/badge/CORE-A*-e74c3c)](https://portal.core.edu.au/conf-ranks/?search=KDD&by=acronym&source=ICORE2026) ![](https://img.shields.io/badge/CCF-A-e74c3c)
- *2026.11*: &nbsp;🎉 [Denoised but Not Improved: What EEG Denoising Does to a Downstream Task](https://arxiv.org/abs/2611.29256) is accepted at the **IEEE Symposium on CI in Health and Medicine**. ![](https://img.shields.io/badge/CAA-B-e8821e)
- *2026.10*: &nbsp;🎉 [TT-SAX: A Two-Track Time Series Symbolization for Natural Language Shape Querying](https://arxiv.org/abs/2610.30593) is accepted at **ADC 2026**. [![](https://img.shields.io/badge/CORE-B-e8821e)](https://portal.core.edu.au/conf-ranks/?search=ADC&by=acronym&source=ICORE2026)
- *2026.06*: &nbsp;🎉 [BIP: Bi-Level Information Transfer and Completion Prompting for Visual Recognition with Missing Modalities](https://doi.org/10.1007/978-3-032-37010-5_16) is accepted at **ECCV 2026**. [![](https://img.shields.io/badge/CORE-A*-e74c3c)](https://portal.core.edu.au/conf-ranks/?search=ECCV&by=acronym&source=ICORE2026)

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2027</div><video src='assets/videos/rebrain-promo-720p.mp4' poster='images/paper/rebrain-kdd2027.png' playsinline controls preload='metadata' width="100%" style="border-radius:6px;">ReBrain promo video</video></div></div>
<div class='paper-box-text' markdown="1">

[iEEG Can Help EEG: Improving Clinical Scalp EEG Analysis through Intracranial Priors](https://arxiv.org/abs/2611.20435)

<span style="color:#d6336c">**Xianglong Bao**</span>, Yi Ding, Zengxiang Li, Nan Liu, Kewen Wang, Zhe Wang, Ming Jin

**KDD 2027** [![](https://img.shields.io/badge/CORE-A*-e74c3c)](https://portal.core.edu.au/conf-ranks/?search=KDD&by=acronym&source=ICORE2026) ![](https://img.shields.io/badge/CCF-A-e74c3c) \| [\[code\]](https://github.com/Xianglong-Bao/ReBrain)

<a href="assets/videos/rebrain-promo-720p.mp4"><img src="https://img.shields.io/badge/ReBrain-Promo%20Video-e74c3c?logo=youtube&logoColor=white" alt="Promo Video"></a>

- ReBrain fits a signal-to-signal model on intracranial EEG alone and freezes it as a plug-and-play prior that re-expresses scalp EEG, improving downstream models across hospitals with no pairing or fine-tuning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE CIHM 2027</div><img src='images/paper/denoise-cihm2027.svg' alt="EEG denoising audit" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Denoised but Not Improved: What EEG Denoising Does to a Downstream Task](https://arxiv.org/abs/2611.29256)

<span style="color:#d6336c">**Xianglong Bao**</span>, Zhe Wang, Kewen Wang, Ming Jin

**IEEE Symposium on CI in Health and Medicine 2027** ![](https://img.shields.io/badge/CAA-B-e8821e)

- Five standard EEG denoising methods all fail to improve a fixed seizure-detection pipeline; what actually helps is shrinking within-class scatter on task-relevant features, not matching a clean waveform.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/paper/worldmodels-arxiv2026.png' alt="Biosignal world models" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Rethinking World Models for Biosignals](https://arxiv.org/abs/2610.17510)

<span style="color:#d6336c">**Xianglong Bao**</span>, Bosong Huang, Xiaoda Wang, Keqi Han, Carl Yang, Ming Jin, Shirui Pan

*arXiv*, 2026

- Identifies three physiological bottlenecks for biosignal world models (temporal latency, system openness, endogenous dynamics) and proposes an Intervention-Effect Validation Checklist.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ADC 2026</div><img src='images/paper/ttsax-adc2026.png' alt="TT-SAX" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TT-SAX: A Two-Track Time Series Symbolization for Natural Language Shape Querying](https://arxiv.org/abs/2610.30593)

Zhao Tan, <span style="color:#d6336c">**Xianglong Bao**</span>, Zhipeng Xi, Ming Jin

**ADC 2026** [![](https://img.shields.io/badge/CORE-B-e8821e)](https://portal.core.edu.au/conf-ranks/?search=ADC&by=acronym&source=ICORE2026)

- Adds a trend track to SAX, graded to match the adjectives people use in queries, and beats six classical symbolizations on natural-language shape queries across six LLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026</div><img src='images/paper/bip-eccv2026.webp' alt="BIP" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BIP: Bi-Level Information Transfer and Completion Prompting for Visual Recognition with Missing Modalities](https://doi.org/10.1007/978-3-032-37010-5_16)

Haoran Fan, Xu Han, <span style="color:#d6336c">**Xianglong Bao**</span>, Zheng Gao, Qi Fan, Yang Song, Jiaojiao Jiang

**ECCV 2026** [![](https://img.shields.io/badge/CORE-A*-e74c3c)](https://portal.core.edu.au/conf-ranks/?search=ECCV&by=acronym&source=ICORE2026)

- Completes the missing modality at the prompt level instead of reconstructing features, with a hypernetwork that adapts prompts to each missing-modality case.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PAKDD 2025 Oral</div><img src='images/paper/temprule-pakdd2025.png' alt="TempRuLe" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Explainable Temporal Knowledge Graph Reasoning via Expressive Logic Rules](https://doi.org/10.1007/978-981-96-8170-9_14)

<span style="color:#d6336c">**Xianglong Bao**</span>, Kewen Wang, Zhe Wang, Hong Wu, Jiangtao Zuo, Xiaowang Zhang, Zhiyong Feng, Hutong Wu

**PAKDD 2025 (Oral)** [![](https://img.shields.io/badge/CORE-B-e8821e)](https://portal.core.edu.au/conf-ranks/?search=PAKDD&by=acronym&source=ICORE2026) \| [\[code\]](https://github.com/Xianglong-Bao/TempRuLe)

- A purely symbolic method that learns expressive temporal rules from both recent and distant events, giving faithful, human-readable explanations.
</div>
</div>

# 💼 Experience
**Ping An Technology U.S. Research Institute (PAII)**, Palo Alto, CA, USA
- Research Scientist Intern (focused on AI4Health)

# 🏆 Honors and Awards
- *2026*: **1st place** (3,711 participants), EEG Sleep Onset track, [NeurIPS 2026 EEG/EMG Foundation Challenge](https://neural-interfaces26.github.io/index.html).
- *2023*: 6th place (452 teams, finalist), Inductive Knowledge Graph Relation Reasoning Competition, CCKS 2023.

# 📚 Teaching
- **Teaching Assistant** (**Acting Lecturer in the final weeks · [Letter of Appreciation](files/letter-of-appreciation.pdf)**), 7907ICT IT and Cyber Security Governance, Policy, Ethics and Law.

# 📋 Academic Services

**🗒️ Program Committee Member**

- [AAAI 2027 Medical World Models Workshop](https://med-wm.github.io/aaai27-mwm/) — Montréal, Canada

**💬 Conference Reviewer**

- [NeurIPS 2026 Foundation Models for Temporal Systems Workshop](https://fmts-workshop.github.io/) — Sydney, Australia

- [IEEE SSCI 2027](https://attend.ieee.org/ssci-2027/) — IEEE Symposium Series on Computational Intelligence, Gold Coast, Australia

- [IEEE Healthcom 2026](https://healthcom2026.ieee-healthcom.org/) — IEEE Int'l Conference on E-health Networking, Application & Services, New York, USA

- [IEEE/ACM CHASE 2026](https://conferences.computer.org/chase2026/) — IEEE/ACM Conference on Connected Health: Applications, Systems and Engineering Technologies, Pittsburgh, USA

- [MLHC 2026](https://www.mlforhc.org/) — Machine Learning for Healthcare Conference, Baltimore, USA

**📄 Journal Reviewer**

- [Artificial Intelligence](https://www.sciencedirect.com/journal/artificial-intelligence)

- [Neurocomputing](https://www.sciencedirect.com/journal/neurocomputing)

- [Pattern Recognition Letters](https://www.sciencedirect.com/journal/pattern-recognition-letters)

- [Frontiers of Computer Science](https://link.springer.com/journal/11704)

- [Journal of King Saud University – Computer and Information Sciences](https://ccis.ksu.edu.sa/en/jksuci)

# 🎷 Beyond Research
I'm a saxophonist 🎷 and a triathlete 🏊🚴🏃. Both are mostly breath control and
endurance. So, apparently, is research.

I also enjoy playing Hearthstone and Warhammer.

<div class="life-photos">
  <img src="images/life/saxophone.jpg" alt="Xianglong with a saxophone">
  <img src="images/life/triathlon.jpg" alt="Xianglong at a race">
  <img src="images/life/kayak.jpg" alt="Kayaking at dusk">
</div>
