# Report

## Model Details
we have used Multi layer perceptron, input size is the environment input size and vice versa for the output. Please check the implementation of model in model.py
####    TODO
- Convolutional Neural Network

## Parameters
* Number of episodes: 4000 (maximum)
* maximum per time step=1000
* epsilon start=1.0
* epsilon end=0.01
* epsilon decay rate=0.999

## Results
Snipping tool has been used to clip from python notebook.

### The average score per 100 episodes
![Banana Image](https://raw.githubusercontent.com/karthikrajkumar/vanilla-dqn/master/report2.JPG)

### Growth of Scores  
![Banana Image](https://raw.githubusercontent.com/karthikrajkumar/vanilla-dqn/master/report1.JPG)

## Agent Details
we have tried with the plain vannila Deep Q Network.
####    TODO - Implement with
*    Double DQN
*    Dueling 
*    Prioritized Experience Replay
*    Noisy exploration
*    Distributional
