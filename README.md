# Cartpole-DQN

![dqn image](https://user-images.githubusercontent.com/116836999/211227460-d4c40809-05dc-45ff-9be8-0c0265f70928.png)

Q learning can be used to solve tasks that do not have a large state space and number of actions e.g. a Gridworld environment where there are only 4 actions and about 25 states, hence the computation is not so tedious

But when dealing with continous environments have a large state space and actions e.g. a self driving car then it is not practical to use Q learning to solve the problem because it can be computationally inefficient.

This is where deep reinforcement learning comes into play

DQN or Deep Q netwroks use 2 neural networks, namely target network and prediction network to solve a task to come up with the best actions to solve the environment
