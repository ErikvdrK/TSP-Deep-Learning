# TSP-Deep-Learning
Repository for my research master thesis on "Combining Deep Learning with Local Search to Solve Combinatorial Optimization Problems"  
This repository contains two neural networks to solve the Traveling Salesman Problem (TSP) using a local search approach:
- supervised_TSP.py: A supervised neural network.
- Q_learning_TSP.py: A Q-learning neural network.  


# Requirements
Python 3  
Tensorflow 1.4+  
Numpy  
Optional: LKH solver & Windows 7+


# Usage of the neural network

## Testing supervised
The "Trained network" folder contrains a pre-trained neural network. This neural network can be loaded by setting .... to True in 

Optionally, the TSP tours that are found with the neural network are compared to the optimal TSP tour. T makes comparisons with the optimal tour that is found with the LKH solver. This is only supported on Windows. 

## Training supervised
- Instructions follow later  
<!---
For a full description of how this, take a look at my thesis that is included in the ... folder.
--> 

## Testing Q-learning
- Instructions follow later

## Training Q-learning
- Instructions follow later

# Files
generate_instances.py: 
neural_network.py: 

TSP_class.py: Class that contains a TSP instance. Is also used to turn the TSP into usable input for the neural network
TSP_figure_class.py: (Optional) Class that is used to show the progress of the neural network.




# Future plans
For now, this repository is simply a dump of all code that was used for my thesis.
Over the following months this repository will be updgraded to a more ready-to-use version with clear instructions.

