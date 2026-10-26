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
* Real-Time Neural Rendering


Research Experience
======

**Skywork AI - Research Intern**
*May 2026 - Present*

* Led the development of [Matrix-Game 4.0](https://matrix-game-v4-0.github.io/page/), combining executable game engines with autoregressive neural rendering for playable game worlds. The released system enables 480p, 60 FPS gameplay on a single RTX 5090 with 112 ms key-press-to-display latency.
* Led the memory module design for [Matrix-Game 3.5](https://matrix-game-v3-5.github.io/), including dynamic object filtering and object-token conditioning for long-horizon scene and protagonist consistency.
* Developed a video-action Mixture-of-Transformers architecture with autoregressive causal masking for interactive policy execution.

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
