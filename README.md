# Neural Networks from Scratch

In this series, we learn different concepts about deep learning by implementing neural networks from scratch.
To get started, follow the steps:
- Clone this repo (git clone https://github.com/ahaque2/neural-network-from-scratch.git)
- install the requirements (install -r requirements.txt)
- Open any Jupyter notebook and run


### Topics

[1_Simple_Count_Model.ipynb](1_Simple_Count_Model.ipynb)
- A bigram model that uses the frequency of bigrams as knowledge to generate text. This is a simple non-neural model

[2_Simple_Bigram_NN_Model.ipynb](2_Simple_Bigram_NN_Model.ipynb)
- A bigram (pseudo) neural network with just one layer

[3_Simple_Mlp_Model.ipynb](3_Simple_Mlp_Model.ipynb) 
- A Multi-Layer Perceptron (MLP) model. We implement [Bengio et al.](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)

[4_MLP_Model_Initialization_and_Hyper_parameters.ipynb](4_MLP_Model_Initialization_and_Hyper_parameters.ipynb)
- We look at pitfalls related to initializing a neural network and some related hyperparameters

[5_Batch_normalization.ipynb](5_Batch_normalization.ipynb)
- We implement the Batch Normalization Layer

[6_Model_Optimization_and_Hyperparameter_tuning.ipynb](6_Model_Optimization_and_Hyperparameter_tuning.ipynb)
- Model optimization by evaluating the activations (forward pass) and gradients (backward pass)

[7_Back_propagation.ipynb](7_Back_propagation.ipynb)
- We implement backpropagation (layer level)
  

### Acknowledgement

This tutorial is inspired by Andrej Karpathy's [_Neural Network: Zero to Hero_](https://www.youtube.com/@AndrejKarpathy) Lecture series and uses much of its content. I also recommend checking out [Jay Alammar](https://jalammar.github.io/illustrated-transformer/) blogs on Transformer architecture and self-attention.
