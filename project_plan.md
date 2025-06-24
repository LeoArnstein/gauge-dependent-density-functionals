# Project Plan

### 1. Generating the data

- Choose the kind of systems to use - atomic and molecular or molecular only with 1 electron only, 2 electrons only or both.
- Choose the parameter spaces to sample from (e.g. molecules with atomic seperations from 1 to 6 a<sub>0</sub>) and how densely to sample from them, which will determine the size of the datasets.
- Perform convergence tests to select the grid size and density.
- Choose the properties to study. In the BSc project that this work builds on, the following properties were used: total energy, kinetic energy, electron affinity, fundamental gap. Other possibilities include external potential energy, molecular binding energy, electronegativity and 1st ionisation energy of 2-electron systems (as 1st ionisation energy is essentially the same as total energy for 1-electron systems). Including a larger number of properties could strengthen the argument but also require more time.
- Generate the data and divide into training, validation and testing.

### 2. Machine learning

- Tune, train and test convolutional neural networks on the data.
- If time permits, investigate using other machine learning models. A good option could be kernel ridge regression models (KRR), as, like neural networks, they are universal approximaters that are commonly used in ML-DFT. KRR models are also less 'black-box' than NNs, so could potentially provide insight into why gauge-dependent density functionals are harder to model accurately. 
