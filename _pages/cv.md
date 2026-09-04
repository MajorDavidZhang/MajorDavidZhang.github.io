---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV (PDF)](/files/Jihai_Zhang_CV.pdf)

Education
======

* Ph.D. in Computer Science and Engineering, The Chinese University of Hong Kong, 2024-2028 (expected)
* M.S. in Computer Science, National University of Singapore, 2021-2024
* B.S. in Computer Science, Shanghai Jiao Tong University, 2017-2021 (Graduated with Honors)


Research Interests
======

* Multimodal Large Language Models
* Unified Vision-Language Modeling
* World Models and Action Models


Research Experience
======

**Skywork AI - Research Intern**
*May 2026 - Present*

* Led the memory module design for Matrix Game 3.5, including dynamic object filtering and object-token conditioning for long-horizon scene and protagonist consistency.
* Developed a video-action Mixture-of-Transformers architecture with autoregressive causal masking for interactive policy execution.
* Leading Matrix Game Next, a neural rendering system for real-time game visual enhancement while preserving gameplay-relevant structure and motion.

**Tencent - Research Intern**
*July 2025 - January 2026*

* Developed a controllable game video generation framework that separates semantic layout prediction from pixel-level rendering.
* Designed a global memory bank to maintain persistent world state and long-term spatiotemporal consistency.

**Microsoft - Research Intern**
*October 2024 - June 2025*

* Studied cross-task generalization between understanding and generation in unified VLMs, identifying visual-space alignment as a key factor in knowledge transfer.


Publications
======

  <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Academic Service
======

**Conference refereeing:**
- NeurIPS 2024
- NeurIPS 2025
- ARR May 2025
- ICLR 2026
