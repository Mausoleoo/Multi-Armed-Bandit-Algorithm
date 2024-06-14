# Multi Armed Bandit Algorithm

The objective of this assignment is to experiment with simple bandit learning algorithms by implementing them from scratch and comparing their performance based on two criteria: (1) the average accumulated reward and (2) the proportion of time the optimal action, defined as the action with the highest expected reward, is taken.

### Requirements

Python 3.9.12

##### Libraries
numpy == 1.26.2

matplotlib == 3.8.3

### Functions

The function MultiArmedBandit(n = 10, steps = 1000, method = 'greedy', Alpha = 0.1,  NonStationary = 'drift', Permute_Prob = 0, Step = None) can execute all the methods needed for the project. The parameters need to be changed in order to use a specific method.

n -> Number of Arms

steps -> Number of attempts to be made at exploration and exploitation

method -> Needed method ['greedy', 'epsilon', 'optimistic', 'gradient']

Alpha -> Alpha value for the gradient method

NonStationary -> Non stationary rewards ['drift','reverting']

Permute_Prob -> Probability for getting an abrupt change for each step

Step -> Step size for epsilon fixed size (None = Decreasing Step)

### Execution Instructions

The code in this repository was written in a Jupyter Notebook. Each part of the project is separated with its respective code. To execute the code, simply run each cell in sequence, one after the other. The entire code execution will take approximately 10 minutes to complete. 
