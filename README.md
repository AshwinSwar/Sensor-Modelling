# Bayesian Sensor-Modelling

### In this repo, there are some priliminary testing I did on the calibration of Ion Selective Electrodes. There are two notebooks. One is where I explore a supervised approach to calibration and the other is where I discuss an unsupervised approach. <br>

### Supervised Calibration <br>
In this scenario, we have both the sensor responses and the ionc activities that caused the responses. The problem then becomes a classic supervised parameter estimation problem. <br>
### Unsupervised Calibration<br>
Here, we only have access to sensor responses and we want to estimate all the parameters as well as the ionc activities that resulted in those sensor responses. This approach is interesting because getting the ionic activities is a time consuming and labor intensive task whereas getting the sensor responses is cheap and easy. I look into a Bayesian approach which is called Bayesian Blind Source Separation to tackle this problem.

