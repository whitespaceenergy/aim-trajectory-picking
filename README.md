# aim-trajectory-picking
![g_diggers](https://img.shields.io/badge/gold-diggers-yellow)
![GitHub](https://img.shields.io/github/license/Vildeeide/aim-trajectory-picking)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
![GitHub contributors](https://img.shields.io/github/contributors/equinor/aim-trajectory-picking)

<em>Trajectory picking package for the AI for Maturation project. Created by summer interns 2021</em>

##  Introduction
This trajectory picking package is a tool for determining sets of wellbore trajectories which optimizes different variables, using different algorithms.
The trajectory picking task is operationalized as a graph problem, where each trajectory has a donor, a target and a non-negative value, in addition to a list of other trajectories it collides with. Given that no trajectories should share the same donor, nor target, and not collide with other trajectories, different algorithms are implemented which attempt to pick optimal trajectories.


## Getting started 
```
pip install git+https://github.com/equinor/aim-trajectory-picking.git@master
pip install -r test_requirements.txt
pip install .
pytest

```
This package works with Python 3.


[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/Naereen/)
### Authors: ## 
Alexander Johnsgaard\
Even Åge Smedshaug\
Jonatan Lærdahl\
Vilde Dille Øvreeide\
Henrik Pettersen 

