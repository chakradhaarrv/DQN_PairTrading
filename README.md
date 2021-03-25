# DQN_PairTrading

Algorithmic Trading of Stock Pairs using Deep Reinforcement Learning.

Two stocks (preferrably in the same sector/industry) are used in this Deep Q network model for simpilicty.

We have a five day moving average period whose value is used to determine whether to perform trade actions such and buying and selling.
Rewards are based on how each action affects our portfolio value.

Note that the actions are chosen solely to maximize the expected return, i.e., blindly maximizing profit without taking risk into account.
