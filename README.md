# Papers of RLHF

This is a collection of papers in Reinforcement Learning with Human Feedback (RLHF) that I found important. I summarized the papers I collected and made my comments. I understand there are always some important papers I have missed, and I will constantly update to my best efforts.

**Contact** : [Ke Sun](https://sites.google.com/view/kesun), ksun6@ualberta.ca

## 2024

* [Reinforcement Learning from Human Feedback with Active Queries](https://arxiv.org/pdf/2402.09401.pdf) **(Arxiv)**
> This paper formulates RLHF as a contextual dueling bandit problem and incorporates active learning in PPO and DPO with detailed regret bounds/query complexity. It achieves similar performance, making half of queries from human preference.



## 2023

* [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290) **(NeurIPS 2023)**
> To address the hard optimization issues in PPO-based RLHF in LLM, DPO simplifies the RL objective function by reparameterization/change variable (cancel the explicit reward function), leading to a simple binary cross-entropy supervised learning loss. They also provide some theoretical interpretation of DPO, and experiments demonstrate that DPO outperforms PPO-based RLHF.


## 2022 and Before

* [Fine-Tuning Language Models from Human Preferences](https://arxiv.org/pdf/1909.08593.pdf) **(arxiv 2020)**
> This paper proposes the PPO-based RLHF in the context of LLM.

* [Deep Reinforcement Learning from Human Preferences](https://arxiv.org/pdf/1706.03741.pdf) **(NIPS 2017)**
> The first successful RLHF paper from DeepMind and OpenAI **within the RL field**, where human feedbacks are collected to train a reward model (Bradley-Terry) via a binary cross entropy loss. Experiments are conducted on both Mujoco and Atari games with A2C and TRPO associated with a bunch of human feedbacks, without observing the true reward model. The implementation is based on TensorFlow.


## Reference

https://github.com/opendilab/awesome-RLHF
