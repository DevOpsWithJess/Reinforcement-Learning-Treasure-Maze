# Reinforcement Learning Treasure Maze
Python | TensorFlow | Deep Q-Learning
## Author: Jessica Johnson
## Language: Python (TensorFlow / Keras)

## Overview

This project implements a reinforcement learning agent that learns how to navigate a treasure maze environment using reward-based learning.

The goal of the agent is to discover the optimal path through a maze to reach the treasure while avoiding inefficient exploration. The agent improves its decision making over time by learning from rewards and penalties received during training episodes.

The project was implemented in Python using a Jupyter Notebook environment and demonstrates core reinforcement learning concepts including exploration vs. exploitation, Q-value prediction, and neural network–based policy learning.

---

## Environment

The environment is represented as a grid-based maze where:

- The **pirate agent** starts at a random position
- The **treasure** is located at a fixed goal position
- The agent can move **up, down, left, or right**
- Each move returns a reward value used to train the model

The maze structure is stored as a matrix where each cell represents a valid position in the environment.

## Project Notebook

The full implementation, training process, and results can be viewed in the Jupyter Notebook below:

- [Reinforcement Learning Treasure Maze Notebook](Johnson_Jessica_ProjectTwo.ipynb)

## Training Results

During training, the agent gradually improved its navigation strategy as it learned from rewards and penalties.

Over many training episodes, the win rate increased until the model consistently found the optimal path to the treasure.

Example training output:
- Epoch: 191/999
- Loss: 0.0003
- Win rate: 1.000
