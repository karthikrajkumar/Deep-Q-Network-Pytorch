# Navigation - Vanilla DQN with Pytorch 

![Banana Image](https://camo.githubusercontent.com/b3ba13bafd8458e8c4fad71d8a06cb439821f8c1/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f766964656f2e756461636974792d646174612e636f6d2f746f706865722f323031382f4a756e652f35623161623462305f62616e616e612f62616e616e612e676966)

In this project we will be training an agent to navigate the space by collecting yellow banana and avoiding blue banana. We will be using Unity Environment.

## Environment Details
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

     0 - move forward.
     1 - move backward.
     2 - turn left.
     3 - turn right.
     
The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes

For this use case, we dont have to install Unity environment as it has already been built. please find the details specific to operating systems.

*    [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
*    [Mac OS](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
*    [Win 32](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
*    [Win 64](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

## Installation details
you would be requiring the following
*    Python 3.6 or above [click here](https://www.python.org/downloads/)
    
*    Jupyter notebook/ lab

    python3 -m pip install --upgrade pip
    python3 -m pip install jupyter
    
    jupyter notebook
    
*    Pytorch [click for installation](https://pytorch.org/)
*    Numpy & matplotlib
     
    pip install numpy
    pip install matplotlib
     

## How to run this ?
Open the Navigation python notebook (Navigation.ipynb) and start running cell by cell or run all.
*    Note: The Unity environment needs to be downloaded and in Navigation.ipynb the path to load the environment needs to be changed accordingly.
