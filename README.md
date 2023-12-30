# Synfire Chains

## This project surrounds Synfire Chains and successfully reproduces and extends the results of the paper of ["Stable propagation of synchronous spiking in cortical neural networks"](https://www.nature.com/articles/990101) by Diesmann et al (1999). 

### Task 1: Implementation of a simulator for the model in the paper. 
__Model:__ Leaky Integrate-and-Fire (LIF) neuron with:
- Alpha synapse
- Poisson background noise
- Refractoriness
- Input spike burst initialisation
- All-to-all connectivity between layers
- Spike time delay between layers

### Task 2: Validation of neuron, synapse and network properties.

### Task 3: Raster displays of propagating spike volley along fully connected synfire chain.

### Task 4: Neural transmission function for pulse-packet input.

__Relationship plots__: 
- Spike probability ($\alpha$) and Input spike number ($a_{in}$)
- Temporal accuracy ($\sigma_{out}$) of spike response and Input synchrony ($\sigma_{in}$)

### Task 5: State-space analysis of propagating spike synchrony.

### Task 6: 
The project ends with an additional investigation of the use of different synapse models in the SNN and the impact on the results on experiments conducted for the purpose of the paper. 

This additional research task is concluded with the findings that the Exponential synapse model is a suitable substitute and performs similarly when undergoing the same experiments as the Alpha model, while being less computationally intensive, implying a cheaper alternative for certain tasks for the SNN. 

On the other hand, the Biexponential model's increases susceptibility to noise yields uncorrelated results, while also having increased computational complexity, making the complexity-stability unfeasible for less demanding tasks for an SNN.

&nbsp;
&nbsp;

_This project was completed by Bastien Baluyot and Abdel-Qader Al-Kilany as a coursework assignment for the ["Neuroscience for Machine Learners"](https://neuro4ml.github.io/) module at Imperial College London._
