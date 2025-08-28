# Reinforcement Learning Agent

This project implements a Reinforcement Learning (RL) agent from scratch using **PyTorch**.  
The agent is trained to interact with OpenAI Gym environments and learn optimal policies through trial and error.

---

## Features
- Implementation of a Deep Q-Network (**DQN**) agent
- Uses experience replay and target networks for stable training
- Modular design: can be extended to other environments
- Training and evaluation inside a Jupyter Notebook
- Logging of episode rewards and visualization of learning progress

---

## Environments
The code is built around OpenAI Gym tasks. Examples you can run:
- `CartPole-v1` — balance a pole on a moving cart
- `MountainCar-v0` — drive a car up a steep hill
- `LunarLander-v2` — land a spacecraft safely

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/rl-agent.git
   cd rl-agent
