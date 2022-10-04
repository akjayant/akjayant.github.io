---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


  
##  Model-based Safe Deep Reinforcement Learning via a Constrained Proximal Policy Optimization Algorithm
### Neural Information Processing Systems (NeurIPS), New Orleans, LA, USA 2022
#### Authors : Ashish Kumar Jayant, Shalabh Bhatnagar

During initial iterations of training in most Reinforcement Learning (RL) algorithms, agents perform a significant number of random exploratory steps, which in the real world limit the practicality of these algorithms as these can lead to potentially dangerous behavior. Hence safe exploration is a critical issue in applying RL algorithms in the real world. This problem has been recently well studied under the Constrained Markov Decision Process (CMDP) Framework, where in addition to single-stage rewards, state transitions receive single-stage costs or penalties as well. The prescribed  cost functions are responsible for mapping undesirable behavior at any given time-step to a scalar value. Then we aim to find a feasible policy that maximizes reward returns while constraining the cost returns to be below a prescribed threshold during training as well as deployment.

We propose an On-policy Model-based Safe Deep RL algorithm in which we learn the transition dynamics of the environment in an online manner as well as find a feasible optimal policy using Lagrangian Relaxation-based Proximal Policy Optimization. We use an ensemble of neural networks with different initializations to tackle epistemic and aleatoric uncertainty issues faced during environment model learning.  We compare our approach with relevant model-free and model-based approaches in Constrained RL using the  challenging Safe Reinforcement Learning benchmark - the Open AI Safety Gym.  
We demonstrate that our algorithm is more sample efficient and results in lower  cumulative hazard violations as compared to constrained model-free approaches. Further, our approach shows better reward performance than other constrained model-based approach in the literature.
[Paper link](https://drive.google.com/file/d/1DekSPJSaHMOn1ukmwx7By4fRJ3emUcU7/view)


