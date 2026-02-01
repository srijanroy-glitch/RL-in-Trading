RL IN TRADING

** Week 1 — RL Fundamentals

Introduction to Reinforcement Learning

Explanation of states, actions, rewards

Basic Python setup and environment thinking NumPy, Pandas and matplotlib

** Week 2 — Environment Implementation

Downloading historical price data (e.g., using yfinance)

Defining the TradingEnv environment

Representing agent observations and actions

** Week 3 — Q-Learning Agent

Initializing the Q-table

Setting learning rate, discount factor, and exploration rate

Writing the training loop

Updating Q-values using the Bellman equation

** Week 4 — Final Project

Train the agent on real price data

Evaluate trained RL agent

Compare against a Buy-and-Hold baseline

Includes a complete working notebook: Final_Project.ipynb

Actions:

0: Hold

1: Buy

2: Sell

Reward: Portfolio value = cash + (stock * current price)

The agent learns a Q-table that maps states to action values, helping decide the best action in each situation. After training, the agent is evaluated, and its performance is compared with a traditional buy-and-hold strategy.
