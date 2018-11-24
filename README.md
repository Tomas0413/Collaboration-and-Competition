# Project Details

This environment has two agents that control Tennis rackets to bounce a ball over a net.

* The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation.
* Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.
* After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.


# Getting Started

Open Collaboration-and-Competition.ipynb Jupyter notebook, it also contains a section on how to install the necessary dependencies.

Download the Tennis environment (binary file) for your operating system and configure file_name variable (in Collaboration-and-Competition.ipynb Jupyter notebook) to point to the location of the binary file.

* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

# Instructions

Open Collaboration-and-Competition.ipynb Jupyter notebook and execute each code block to train the agent using DDPG.
