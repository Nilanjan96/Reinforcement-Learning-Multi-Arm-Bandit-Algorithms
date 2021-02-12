# Reinforcement-Learning-Multi-Arm-Bandit-Algorithms
Comparing several multi arm bandit algorithms to maximise the reward
Algorithms used:-
1) Epsilon Greedy with epsilon = [0,0.1,0.15,0.2,0.5]
2) Explore and Exploit
3) UCB with c = 1,2
4) Gradient Bandit Algorithm with baseline (alpha = 0.1, 0.4)
5) Gradient Bandit Algorithm without baseline (alpha = 0.1,0.4)
6) Epsilon Greedy decay
I use the same multi arm bandit situation for every algorithm. The reward at each timestep follows the means [−0.3, 0.0, 0.2, 0.3, 0.6] and variance 1. We plot the average reward for every algorithm, average regret per timestep, average number of times an arm was choosen upto time instant t,number of times the optimal arm was chosen at time t.
