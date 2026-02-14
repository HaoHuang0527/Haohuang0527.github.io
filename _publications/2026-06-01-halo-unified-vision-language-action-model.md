---
title: "HALO: A Unified Vision-Language-Action Model for Embodied Multimodal Chain-of-Thought Reasoning"
collection: publications
category: manuscripts  # 因论文处于Under Review，填manuscripts；若录用后可改为conferences
permalink: /publication/2026-06-01-halo-unified-vision-language-action-model
excerpt: 'Abstract Vision–Language–Action (VLA) models have shown strong performance in robotic manipulation, but often struggle in long-horizon or out-of-distribution scenarios due to the lack of explicit mechanisms for multimodal reasoning and anticipating how the world will evolve under action. Recent works introduce textual chain-of-thought or visual subgoal prediction within VLA models to reason, but still fail to offer a unified human-like reasoning framework for joint textual reasoning, visual foresight, and action prediction. To this end, we propose HALO, a unified VLA model that enables embodied multimodal chain-of-thought (EM-CoT) reasoning through a sequential process of textual task reasoning, visual subgoal prediction for fine-grained guidance, and EM-CoT-augmented action prediction. We instantiate HALO with a Mixture-of-Transformers (MoT) architecture that decouples semantic reasoning, visual foresight, and action prediction into specialized experts while allowing seamless cross-expert collaboration. To enable HALO learning at scale, we introduce an automated pipeline to synthesize EM-CoT training data along with a carefully crafted training recipe. Extensive experiments demonstrate that: (1) HALO achieves superior performance in both simulated and real-world environments, surpassing baseline policy $\pi_0$ by 34.1% on RoboTwin benchmark; (2) all proposed components of the training recipe and EM-CoT design help improve task success rate; and (3) HALO exhibits strong generalization capabilities under aggressive unseen environmental randomization with our proposed EM-CoT reasoning.'
date: 2026-06-01  # ICML 2026 预估时间，可根据实际提交/评审时间调整
venue: 'Under Review at ICML 2026'
paperurl: ''  # 若有论文预印本链接，填此处（如arXiv地址）；无则留空
citation: 'Quanxin Shou, Fangqi Zhu, Shuang Chen, Puxin Yan, Zhengyang Yan, Yikun Miao, Xiaoyi Pang, Zicong Hong, Ruikai Shi, <strong>Huang, Hao</strong>, Jie Zhang, & Song Guo. (2026). "HALO: A Unified Vision-Language-Action Model for Embodied Multimodal Chain-of-Thought Reasoning." <i>Under Review at ICML 2026</i>.'
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
