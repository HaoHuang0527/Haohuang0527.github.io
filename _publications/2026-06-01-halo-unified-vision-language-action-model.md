---
**HALO: A Unified Vision-Language-Action Model for Embodied Multimodal Chain-of-Thought Reasoning**
Quanxin Shou, Fangqi Zhu, Shuang Chen, Puxin Yan, Zhengyang Yan, Yikun Miao, Xiaoyi Pang, Zicong Hong, Ruikai Shi, **Hao Huang**, Jie Zhang, Song Guo
[International Conference on Machine Learning (ICML 2026)](https://arxiv.org/abs/2602.21157), 2026. | Poster Presentation
1. Co-developed HALO, a deliberative VLA model incorporating a Mixture-of-Transformers (MoT) architecture with dedicated Action Prediction Experts for multi-modal embodied reasoning.
2. Designed the low-level execution pipeline utilizing flow-matching/diffusion processes to condition-generate continuous action chunks ($K=16 / 50$ steps of velocity, position, and gripper commands).
3. Pioneered Embodied Multimodal Chain-of-Thought (EM-CoT), enabling the model to sequence text reasoning and visual subgoal predictions before mapping to grounded execution, drastically mitigating reactive cascading errors.
4. Evaluated on the RoboTwin 2.0 benchmark (50+ tasks): Achieved 80.5% average success rate in Easy settings, outperforming the baseline π₀ by +34.1% and +10.1% respectively.
5. Demonstrated strong zero-shot OOD generalization across unseen environments and novel objects (e.g., visual distractors, lighting/textural randomization) via real-world deployment on a Mobile ALOHA bi-arm platform.

- We designed a Mixture-of-Transformers (MoT) architecture to decouple semantic reasoning, visual foresight, and action prediction while enabling cross-expert collaboration.
- We introduced an automated pipeline for synthesizing EM-CoT training data and a tailored training recipe for scalable learning.
- We achieved superior performance in simulated and real-world settings, outperforming baseline π₀ by 34.1% on the RoboTwin benchmark; demonstrated strong generalization under aggressive unseen environmental randomization.

{% if page.paperurl %}
[Download paper here]({{ page.paperurl }}){:target="_blank"}
{% endif %}

### Recommended Citation
{{ page.citation }}
