# Multi Armed Bandit Algorithm

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

Step -> Step size for epsilon fixed size
