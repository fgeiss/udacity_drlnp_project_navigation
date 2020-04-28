# Project 01 Navigation for Udacities Deep Reinforcement Learning Nano Degree

## Project Details
The goal of this project is to implement and train an agent with Q-Learning to play a game. The game setting consists of a large square world in which the agent navigates with discrete actions 
- **`0`** move forward
- **`1`** move backward 
- **`2`** turn left
- **`3`** turn right

The aim to collect as many yellow bananas as possible while avoiding blue bananas. The final score is the number of the collected yellow bananas minus the number of the collected blue bananas.

The space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects and walls around the agent's forward direction.

## Getting Started


1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the folder of this repository and unzip (or decompress) the file. 

## Instructions

Follow the instructions in `Navigation.ipynb` to get train and evaluate the agent.


## Results

Results are documented in the [project report](Report.md)
