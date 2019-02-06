# Implementation of DQN using just Numpy
[![Build Status](https://travis-ci.org/LachubCz/DQN-using-Numpy.svg?branch=master)](https://travis-ci.org/LachubCz/DQN-using-Numpy) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/0ebf810ab4524818a61a8958d48570c2)](https://www.codacy.com/app/LachubCz/DQN-using-Numpy?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=LachubCz/DQN-using-Numpy&amp;utm_campaign=Badge_Grade)

Application implements DQN using just Numpy. Thereafter the DQN agent is adapted for the FrozenLake environment, which is also implemented using just Numpy. 

Usage
-----
##### python3 q_learning.py  [-mode mode] [-r_mode r_mode] [-model model]
###### Parameters:

    -mode {train, test}            |  application mode
    -r_mode {map, weights, stats}  |  vizualization mode
    -model MODEL                   |  filename of trained model for testing mode


Examples
-----------------
    python3 q_learning.py -mode train -r_mode map
    python3 q_learning.py -mode train -r_mode weights
    python3 q_learning.py -mode train -r_mode stats
    python3 q_learning.py -mode test -model model.pkl

Training modes
-----------------
**Map mode** shows agent's moves in the FrozenLake environment during learning.

<img src="https://raw.githubusercontent.com/LachubCz/DQN-using-Numpy/master/images/map.gif" height="300"/>

**Weights mode** shows weights of neural network during training.

<img src="https://raw.githubusercontent.com/LachubCz/DQN-using-Numpy/master/images/weights.gif" height="250"/>

**Stats mode** prints outcome of every training episode.

<img src="https://raw.githubusercontent.com/LachubCz/DQN-using-Numpy/master/images/stats.gif" height="300"/>

****
###### Created by: Petr Buchal
