# An Agent-Based Model of Electric Vehicle behavior with charging
This repository holds the codebase for an Agent-Based Model of Electric Vehicles (EVs). EVs will be able to drive around on a grid from home to work or to the shop, but at some point they need to charge. On the grid charge points are distributed, and the EVs hold in memory successful attempts. Based on their strategy they go to different charging points. This project was conducted for the course Agent-Based Modelling by Michael Lees and Debraj Roy, University of Amsterdam.

## Getting started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Prerequisite libraries, frameworks, and modules can be installed through:

'''
pip install -r requirements.txt
'''

This will install the correct versions of:

* matplotlib (2.0.2)
* numpy (1.12.1)
* pyDOE (0.3.6)
* pandas (0.20.3)
* pathos (0.2.1)
* scipy (1.0.0)
* Mesa (0.8.2)
* SALib (1.1.3)

### Repository

The following list describes the most important files in the project and where to find them:

* /EV: contains all of the codebase of this project.
** /EV/agents.py: contains both the EV and the CP class that implements their properties and updates.

** /EV/model.py: contains the Environment class that implements the Environment's properties and updates.
** /EV/server.py: makes it possible to visualize the model in the browser.
* /Data: contains csv's generated by the code.
* /Graphs: contains mainly images generated by the code.

To run, enter in  a terminal window:
```
python run.py
```
## Contributors

* G. Czupy - Initial work
* S. Jansen - Initial work
* J. Mies - Initial work
* L. van der Wilt - Initial work


