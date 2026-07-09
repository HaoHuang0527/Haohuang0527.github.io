---
title: "HALO: A Unified Vision-Language-Action Model for Embodied Multimodal Chain-of-Thought Reasoning"
collection: publications
category: conference
permalink: /publication/2026-06-01-halo-unified-vision-language-action-model
excerpt: 'We propose HALO, a unified vision-language-action model with Embodied Multimodal Chain-of-Thought reasoning for robotic embodied tasks, achieving state-of-the-art performance on RoboTwin 2.0 benchmark.'
date: 2026-06-09
venue: 'International Conference on Machine Learning (ICML 2026), Poster Presentation'
paperurl: 'https://arxiv.org/abs/2602.21157'
citation: 'Quanxin Shou, Fangqi Zhu, Shuang Chen, Puxin Yan, Zhengyang Yan, Yikun Miao, Xiaoyi Pang, Zicong Hong, Ruikai Shi, Hao Huang, Jie Zhang, Song Guo. (2026). "HALO: A Unified Vision-Language-Action Model for Embodied Multimodal Chain-of-Thought Reasoning." <i>International Conference on Machine Learning (ICML 2026)</i>. Poster Presentation.'
---
- Co-developed **HALO**, a deliberative VLA model incorporating a Mixture-of-Transformers (MoT) architecture with dedicated Action Prediction Experts for multi-modal embodied reasoning.
- Designed the low-level execution pipeline utilizing flow-matching/diffusion processes to condition-generate continuous action chunks ($K = 16 / 50$ steps of velocity, position, and gripper commands).
- Pioneered **Embodied Multimodal Chain-of-Thought (EM-CoT)**, enabling the model to sequence text reasoning and visual subgoal predictions before mapping to grounded execution, drastically mitigating reactive cascading errors.
- Evaluated on the RoboTwin 2.0 benchmark (50+ tasks): Achieved **80.5% average success rate** in Easy settings, outperforming the baseline π₀ by +34.1% and +10.1% respectively.
- Demonstrated strong zero-shot OOD generalization across unseen environments and novel objects (e.g., visual distractors, lighting/textural randomization) via real-world deployment on a Mobile ALOHA bi-arm platform.
---
