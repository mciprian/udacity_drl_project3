# Solution to Udacity - Deep Reinforcement Learning Project 3: Collaboration and Competition

This repository contains the solution that I have proposed to the Collaboration and Competition project, which is based on the material presented in the DDPG lesson. The repository consists of the following files:
- **Tennis.ipynb:** Notebook that contains the adaptation of the DDPG Agents to solve the proposed problem.
- **multi_ddpg_agent.py:** Implementation of the DDPG Agents, based on the material provided in previous lessons.
- **workspace_utils.py:** Workspace utilities, It was used to keep alive the workspace for long periods.
- **Report.pdf:** Document describing the details of the implementation
- **checkpoint_actor.pth:** Actor Model trained during the development of the project.
- **checkpoint_critic.pth:** Critic Model trained during the development of the project.

This code solves the Tennis Environment, which is described as (Taken from Project description): 

"In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping." 

## Instructions 

- Make sure that the Tennis.ipynb, multi_ddpg_agent.py, workspace_utils.py, checkpoint_actor.pth and checkpoint_critic.pth files are in the same folder.
- The notebook was built using the course Workspace, so it must be reproduced in a kernel that has the same libraries installed.

