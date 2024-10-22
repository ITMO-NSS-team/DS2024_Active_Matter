
Repository of the research article "Differential equation discovery of robotic swarm as active matter" in the 27th International Conference on Discovery Science 2024. 
=============================

The repository presents the results of the numerical experiments presented in the paper:

- Dynamics of a single robot without external influence (experiment_1)
- Dynamics of a single robot with external influence (experiment_2)
- General robots dynamics (experiment_3)

The experiment data is stored in **.pickle** format and is represented as nested lists containing frame-by-frame motion detection results of the self-rotating robots. Each nested list contains information about the position of all robots at a given time. In addition to the orientation angle of the robots, the primary data we work with includes the displacement coordinates along the abscissa and ordinate axes.

For each experiment, there are both input and output data. The general file discovery_science.html contains the entire experiment pipelines.

The repository also includes the images used in the article.
### The algorithms used:

- algorithm for the search of differential equations based on data (https://github.com/ITMO-NSS-team/EPDE)
- algorithm for automated solution of differential equations based on neural networks (https://github.com/ITMO-NSS-team/torch_DE_solver)
- algorithm for digital image correlation (https://github.com/PolymerGuy/muDIC)