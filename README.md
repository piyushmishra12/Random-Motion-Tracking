# Random-Motion-Tracking
This repository is to learn and understand motion tracking. 

* Kalman Filter

1. (16.11.2022) V1: Simulated Brownian motion using Wiener random walk. tracked this random walk using basic Kalman filter in numpy.
2. (17.11.2022) V2: Extended this to multiple particles. Took an example of 10 particles. For now, the idea is to have the same filter parameters for each particle, in a for loop, calculate the predictions and store them. Plot the actual (simulated) motions against the predicted motions.
