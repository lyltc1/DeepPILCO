This repo tries to reproduce the results of the following paper in PyTorch

- Gal, Y., McAllister, R. and Rasmussen, C.E., 2016, April. Improving PILCO with Bayesian neural network dynamics models. In Data-Efficient Machine Learning workshop, ICML.

However, it is failed to learn a good controller. The purpose of releasing this repo is to encourage if someone interested in to help to seek for potential bugs or check for reproducibility of the algorithm. 

# Env:
To be consistent with the original paper, I have modified the environment 'CartPole-SwingUp' with same 'physics' coefficients used in the paper. 

##### Previously I have posted a [discussion](https://discuss.pytorch.org/t/should-we-set-requires-grad-false-for-this-rl-computational-graph/8143) in PyTorch, with a visualization of computational graph of DeepPILCO. 

### Any help or comments are highly welcomed to make this algorithm work or check for reproducibility together. 
