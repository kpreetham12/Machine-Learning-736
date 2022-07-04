# Reinforcement-Learning-in-Super-Mario-Bros

The game Super Mario Bros is a very popular action game featuring a "real-life" scenario and a huge state space. It is one of the best game environments to learn about the different reinforcement learning algorithms. The AI bot must deal with many items and challenges in the Super Mario Bros environment, supporting a knowledge-rich approach to the learning process.

The goal of this project is to use Deep Reinforcement Learning technique called Proximal Policy Optimization to train an agent to self-play Super Mario Bros. Using Proximal Policy Optimization, our AI agent will learn how to play by watching only the raw game pixels, we utilize convolutional layers early in the network, followed by dense layers to retrieve our policy and state-value output. We use Stable-baselines3 library to import the PPO reinforcement learning algorithm we.

The aim of this project in layman terms is to, start on the left edge of a level and travel to the flagpole without dying while maximizing the score. Therefore I have trained an AI agent that can effectively complete a single level of Super Mario.
