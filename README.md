# Example Dueling DQN implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_dueling_dqn_example/blob/master/dueling_dqn_tutorial.ipynb) of dueling deep q-network (Dueling DQN) with ReLAx.

Dueling DQN actor was trained on Seaquest-v0 Atari Gym environment for 3m env-steps. 

__!Note:__ For demonstration purposes training was run only for 3m steps. In papers, DQN and its augmentations are trained for 200m steps, which may require several days of learning. That is why performance is lower than reported in papers.

The graph of average return vs environment step is shown below (logs done every 50k steps):

![dueling_dqn_training](https://github.com/nslyubaykin/relax_dueling_dqn_example/blob/master/dueling_dqn_training.png)

The distribution of estimated Q-values vs data Q-values is shown below:

![dueling_dqn_q_func](https://github.com/nslyubaykin/relax_dueling_dqn_example/blob/master/dueling_dqn_q_func.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187169863-a3c79c01-52ee-49f9-9ded-6f0c6637c0ab.mp4
