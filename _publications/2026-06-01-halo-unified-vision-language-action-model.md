---
title: "HALO: A Unified Vision-Language-Action Model for Embodied Multimodal Chain-of-Thought Reasoning"
collection: publications
category: manuscripts  # 因论文处于Under Review，填manuscripts；若录用后可改为conferences
permalink: /publication/2026-06-01-halo-unified-vision-language-action-model
excerpt: 'We proposed HALO, a unified Vision-Language-Action (VLA) model enabling embodied multimodal chain-of-thought (EM-CoT) reasoning via sequential textual task decomposition, visual subgoal prediction, and action generation.'
date: 2026-06-01  # ICML 2026 预估时间，可根据实际提交/评审时间调整
venue: 'Under Review at ICML 2026'
paperurl: ''  # 若有论文预印本链接，填此处（如arXiv地址）；无则留空
citation: 'Quanxin Shou, Fangqi Zhu, Shuang Chen, Puxin Yan, Zhengyang Yan, Yikun Miao, Xiaoyi Pang, Zicong Hong, Ruikai Shi, <strong>Huang, Hao.</strong>, Jie Zhang, & Song Guo. (2026). "HALO: A Unified Vision-Language-Action Model for Embodied Multimodal Chain-of-Thought Reasoning." <i>Under Review at ICML 2026</i>.'
---

### Abstract & Key Contributions
We proposed HALO, a unified Vision-Language-Action (VLA) model enabling embodied multimodal chain-of-thought (EM-CoT) reasoning via sequential textual task decomposition, visual subgoal prediction, and action generation.
- We designed a Mixture-of-Transformers (MoT) architecture to decouple semantic reasoning, visual foresight, and action prediction while enabling cross-expert collaboration.
- We introduced an automated pipeline for synthesizing EM-CoT training data and a tailored training recipe for scalable learning.
- We achieved superior performance in simulated and real-world settings, outperforming baseline π₀ by 34.1% on the RoboTwin benchmark; demonstrated strong generalization under aggressive unseen environmental randomization.

{% if page.paperurl %}
[Download paper here]({{ page.paperurl }}){:target="_blank"}
{% endif %}

### Recommended Citation
{{ page.citation }}
