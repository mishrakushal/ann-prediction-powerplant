# Artificial Neural Network Prediction Model
This is a Artificial Neural Network model to predict the electrical energy output of a Combined Cycle Power Plant. 
<br>
## Some background of Combined-Cycle Power Plants: <br>
A combined-cycle power plant is an electrical power plant in which a Gas Turbine (GT) and a Steam Turbine (ST) are used in combination to produce more electrical energy from the same fuel than that would be possible from a single cycle power plant.

The gas turbine compresses air and mixes it with a fuel heated to a very high temperature. The hot air-fuel mixture moves through the blades, making them spin. The fast-spinning gas turbine drives a generator to generate electricity. The exhaust (waste) heat escaped through the exhaust stack of the gas turbine is utilized by a Heat Recovery Steam Generator (HSRG) system to produce steam that spins a steam turbine. This steam turbine drives a generator to produce additional electricity. CCCP is assumed to produce 50% more energy than a single power plant.

## About this model:
The input layer of this neural network takes into consideration:
- Temperature (T),
- Ambient Pressure (AP),
- Relative Humidity (RH),
- Exhaust Vacuum (V)

> Using the above attributes, the neural network goes through 100 epochs with 2 hidden layers. <br>
> It predicts the net hourly electrical energy output (PE).

The model has an r-squared value of ``0.00877``. This may be improved using more hidden layers and going through more epochs.

---
### Resources:
- Dataset: https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant

