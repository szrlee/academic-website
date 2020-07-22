---
title: "Divergence-Augmented Policy Optimization"
date: 2019-12-01
publishDate: 2020-07-21T23:34:42.027296Z
authors: ["Qing Wang", "Yingru Li", "Jiechao Xiong", "Tong Zhang"]
publication_types: ["1"]
abstract: "In deep reinforcement learning, policy optimization methods need to deal with
issues such as function approximation and the reuse of off-policy data. Standard
policy gradient methods do not handle off-policy data well, leading to premature
convergence and instability. This paper introduces a method to stabilize policy
optimization when off-policy data are reused. The idea is to include a Bregman
divergence between the behavior policy that generates the data and the current
policy to ensure small and safe policy updates with off-policy data. The Bregman
divergence is calculated between the state distributions of two policies, instead of
only on the action probabilities, leading to a divergence augmentation formulation.
Empirical experiments on Atari games show that in the data-scarce scenario where
the reuse of off-policy data becomes necessary, our method can achieve better
performance than other state-of-the-art deep reinforcement learning algorithms."
featured: true
publication: "*Advances in Neural Information Processing Systems*"
links:
  - icon_pack: fab
    icon: github-square
    name: Code
    url: 'https://github.com/lns/dapo'
  - name: Poster
    url: 'poster-dapo.pdf'
  - con_pack: fab
    icon: zhihu
    name: Chinese Blog
    url: ''
---

