# Implementation of DQN using just Numpy
[![Build Status](https://travis-ci.org/LachubCz/DQN-using-Numpy.svg?branch=master)](https://travis-ci.org/LachubCz/DQN-using-Numpy) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/0ebf810ab4524818a61a8958d48570c2)](https://www.codacy.com/app/LachubCz/DQN-using-Numpy?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=LachubCz/DQN-using-Numpy&amp;utm_campaign=Badge_Grade)

Application implements DQN using just Numpy for environment FrozenLake. 

Usage
-----
##### python3 q_learning.py  [-mode mode] [-r_mode r_mode] [-model model]
###### Parameters:

    -mode {train, test}            |  application mode
    -r_mode {weights, map, stats}  |  vizualization mode
    -model MODEL                   |  filename of trained model for testing mode


Examples
-----------------
    python3 q_learning.py -mode train -r_mode map
    python3 q learning.py -mode test -model model.pkl

****
###### Created by: Petr Buchal
