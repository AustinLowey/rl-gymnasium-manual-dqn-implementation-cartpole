# Deep Reinforcement Learning Using Gymnasium
Solving multiple classic control problems using DQN and Classical Q-Learning to practice the Python Gymnasium library/API.


### Problems Solved in the Accompanying Jupyter Notebooks

#### FrozenLake - Classical Q-Learning
https://gymnasium.farama.org/environments/toy_text/frozen_lake/
- Implemented Classical Q-Learning algorithm using numpy and a discrete observation space

#### CartPole - Classical Q-Learning with Discretization
https://gymnasium.farama.org/environments/classic_control/cart_pole/
- Implemented Classical Q-Learning algorithm using numpy and used discretization/bins to handle the continuous observation space
- The challenge is considered solved when the pole stays upright for over 195 time steps, 100 trials consecutively.
- Results: In 100 trials ran, num_wins=100 and num_fails=0 with average_steps=465.15.
