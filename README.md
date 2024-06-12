# Prey Predator Simulations

## ODE Model
The ODE.ipynb in the Simulation folder can be used to get the graph of the ODE model for a configurable starting point. In the notebook the parameters alpha, beta, gamma and delta as well as the initial starting populations x0 for the prey and y0 for the predator can be set. 

## CA Models
All of the following notebooks can be found in the Simulations folder.
- Basic_CA: Our basic implementation without any movement.
- Movement_CA: Our implementation with random and hunt movement.
- Reshuffle_CA: Our implementation with reshuffling after every step.

All of these notebooks can just be run without any further setup. The parameters can be changed in the Simulation section of the notebooks.

## Experiments
The same code as for the models is used but now every parameter confiuration is run and the results are saved in a json file. To save the file accordingly the paths in the loops of the experiments have to be adjusted.

## Visualization and Data Exploration
To visualize the results of the experiments this notebook can be used. Just the paths have to be changed to point to the files generated in the experiments runs.
