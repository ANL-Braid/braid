
# High Energy Diffraction Microscopy (HEDM)


BraggNN is a machine learning-based method that can localize Bragg peaks in high energy diffraction microscopy images more than 200x faster than conventional methods.
Data collected at an experiment (at APS or SLAC) is combined with simulation data to train a sample-specific DNN model, which is then deployed to the experiment for fast processing, filtering, and quality control. These various components are incorporated into a Globus Flow that uses Globus to rapidly move data for training, funcX for simulation and model training, and Globus to move models to the edge. In the future, the flow will also use funcX for inference at the edge.
For more details, see [ArXiv2008.08198](https://arxiv.org/pdf/2008.08198.pdf). 
BraggNN is developed in the DOE BES project **Actionable Information from Sensor to Data Center**, in collaboration with SLAC.

## Flow Definition

<img align="right" src="images/HEDM1.png" width="350">


## Links