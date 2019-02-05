# Implementation of DQN using just Numpy


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
