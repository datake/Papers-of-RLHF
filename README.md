# Papers of RLHF

This is a collection of papers in Reinforcement Learning with Human Feedback (RLHF) that I found important. I summarized the papers I collected and made my comments. I understand there are always some important papers I have missed, and I will constantly update to my best efforts.

**Contact** : [Ke Sun](https://sites.google.com/view/kesun), ksun6@ualberta.ca

## 2024

* [Reinforcement Learning from Human Feedback with Active Queries](https://arxiv.org/pdf/2402.09401.pdf) **(Arxiv)**
> This paper formulates RLHF as a contextual dueling bandit problem and incorporates active learning in PPO and DPO with detailed regret bounds/query complexity. It achieves similar performance, making half of queries from human preference.



## 2023

* [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290) 
>


## 2022 and Before

* [Deep Reinforcement Learning from Human Preferences](https://arxiv.org/pdf/1706.03741.pdf) **(NIPS 2017)**
> The first successful RLHF paper from DeepMind and OpenAI, where human feedbacks are collected to train a reward model (Bradley-Terry) via a binary cross entropy loss. Experiments are conducted on both Mujoco and Atari games with A2C and TRPO associated with a bunch of human feedbacks, without observing the true reward model. The implementation is based on TensorFlow.


## Reference

https://github.com/opendilab/awesome-RLHF
