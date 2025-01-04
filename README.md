# Deep Reinforcement Learning Using Gymnasium
Solving the CartPole classic control problem using 3 different approaches to practice the Python Gymnasium library/API.


### Problems Solved in the Accompanying Jupyter Notebooks

1) FrozenLake - Classical Q-Learning
2) CartPole - Classical Q-Learning with Discretization
3) CartPole - DQN Using a Manual Implementation
4) CartPole - DQN Using Keras-RL

#### 1) FrozenLake - Classical Q-Learning
- [Background on the FrozenLake problem](https://gymnasium.farama.org/environments/toy_text/frozen_lake/)
- Implemented Classical Q-Learning algorithm using numpy and a discrete observation space

#### 2) CartPole - Classical Q-Learning with Discretization
- [Background on the CartPole classic control problem](https://gymnasium.farama.org/environments/classic_control/cart_pole/)
- Implemented Classical Q-Learning algorithm using numpy and used discretization/bins to handle the continuous observation space
- The challenge is considered solved when the pole stays upright for over 195 time steps, 100 trials consecutively.
- Results: In 100 trials ran, num_wins=100 and num_fails=0 with average_steps=465.15.

#### 3) CartPole - DQN Using a Manual Implementation

#### 4) CartPole - DQN Using Keras-RL
