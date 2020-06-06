# ReluVerify
This Repo containts code for Formal Verification of Neural network controlled robot. We consider linear robot dynamics, and assume ReLU neural networks. The workspace is defined in Obstacles.json

-We use linear dynamics for the plant x+ = Ax + Bu, u = NN(x)

-A sample model is found in `model.h5` which is a keras model.

-The workspace regions are defined in `regions` folder

-The sepecification is that the Robot doesn't hit an obstacle. and If the specificaiton is violated, what are the safe regions?

-Formal specification can be found in the [paper](https://dl.acm.org/doi/pdf/10.1145/3302504.3311802)
