## Train a Smartcab How to Drive


### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pygame](https://www.pygame.org/wiki/GettingStarted)
    
If you use [Anaconda](https://www.continuum.io/downloads) then `Pygame` can then be installed using the following command:

Windows & Linux:
`conda install -c https://conda.anaconda.org/tlatorre pygame`


### Files

This project contains two directories:

`/images/`: This folder contains images of cars used in building the graphical user interface. You do not need to modify any of these files.

`/smartcab/`: This folder contains the Python scripts that create the environment, graphical user interface, the simulation, and the agents. You **do not**  need to modify any of these files:

`environment.py`: This Python file will create the smartcab environment.

`planner.py`: This Python file creates a high-level planner for the agent to follow towards a set goal.

`simulation.py`: This Python file creates the simulation and graphical user interface.

The only file you need to modify is

`agent.py`: This is the main file where you will be coding your work on the project.
    
### Code

Template code is provided in the `smartcab/agent.py` python file. Additional supporting python code can be found in `smartcab/enviroment.py`, `smartcab/planner.py`, and `smartcab/simulator.py`. While some code has already been provided to get you started, you will need to implement additional coding in `agent.py` to successfully complete the project.

### Run

In a terminal or command window run one of the following commands:

```python smartcab/agent.py```  
```python -m smartcab.agent```
