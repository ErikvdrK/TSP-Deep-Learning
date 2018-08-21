# TSP-Deep-Learning
Repository for my thesis on "Combining Deep Learning with Local Search to Solve Combinatorial Optimization Problems"
This repository contains two neural networks to solve the Travelling Salesman Problem (TSP)
supervised_TSP.py contains a supervised neural network for the TSP.
Q_leraning_TSP.py contains a Q-learning neural network for the TSP


# Requirements
Python 3  
Tensorflow 1.4+  
Numpy 
Optional: LKH solver & Windows 7+


# Usage of the neural network

## Testing 
The "Trained network" folder contrains a pre-trained neural network. This neural network can be loaded by setting .... to True in 

Optionally, the TSP tours that are found with the neural network are compared to the optimal TSP tour. T makes comparisons with the optimal tour that is found with the LKH solver. This is only supported on Windows. 

## Training
- Instructions follow later
`For a full description of how this, take a look at my thesis that is included in the ... folder.`

## Testing + Training Q-learning
- Instructions follow later

# Files
generate_instances.py: 
neural_network.py: 

TSP_class.py: Class that contains a TSP instance. Is also used to turn the TSP into usable input for the neural network
TSP_figure_class.py: (Optional) Class that is used to show the progress of the neural network.




# Future plans
For now, this repository is simply a dump of all code that was used for my thesis.
Over the following weeks this repository will be updgraded to a more ready-to-use version with clear instructions.

Add full Q-learning support


