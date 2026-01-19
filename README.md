\# Self-Driving Car using Reinforcement Learning (PPO)



This project implements a self-driving car agent using

Proximal Policy Optimization (PPO) in the CarRacing-v2 environment.



\## Project Overview

\- Environment: Gymnasium CarRacing-v2

\- Algorithm: PPO (Stable-Baselines3)

\- Policy: CNN (CnnPolicy)

\- Frame Stacking: 4 frames (12-channel observation)

\- Hardware: Local NVIDIA GPU (CUDA)



\## Training Details

\- Timesteps: 100,000

\- Observation Space: (12, 96, 96)

\- Action Space: Continuous (steering, gas, brake)



Training was limited to 100k timesteps due to local compute constraints.

The setup can be scaled to longer training runs.



\## Files

\- Project 2 - Self Driving.ipynb → Training \& inference code

\- ppo\_self\_driving\_v2.zip → Trained PPO model



\## How to Run

1\. Install dependencies

2\. Open the notebook

3\. Load the pretrained model

4\. Run inference (no retraining required)



Pretrained model is included for direct evaluation.



