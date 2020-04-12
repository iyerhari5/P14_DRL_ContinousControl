
# Project Continuous Control
---

This project works with the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

## Project Details
In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

## Getting Started
It is recommended to follow the Udacity DRL ND dependencies [instructions here](https://github.com/udacity/deep-reinforcement-learning#dependencies) 

This project utilizes [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md), [NumPy](http://www.numpy.org/) and [PyTorch](https://pytorch.org/) 

A prebuilt simulator is required in be installed. You need only select the environment that matches your operating system:

### Environment 
Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)


The file needs to placed in the root directory of the repository and unzipped.

Next, before starting the environment utilizing the corresponding pre-built app from Udacity  **Before running the code cell in the notebook**, change the `file_name` parameter to match the location of the Unity environment that you downloaded.

### Code Organization

All the code is self contained in `Continuous_Control.ipynb`. The actor/critic models, the ddpg agent and the training code are organized into seprate cells.
 
### Instructions

Follow the code in `Continuous_Control.ipynb` to train the agent!  

