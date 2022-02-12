# Doubt Your Model

## Uncertainty estimation methods for classification (MNIST dataset)

### Methods
- Deep Ensembles [ [Lakshminarayanan et al., NeurIPS 2017](https://arxiv.org/abs/1612.01474) ]
- Deep Ensembles + Adversarial Training [ [Lakshminarayanan et al., NeurIPS 2017](https://arxiv.org/abs/1612.01474) + [Goodfellow et al., ICLR 2015](https://arxiv.org/abs/1412.6572) ]
- Monte Carlo Dropout [ [Gal and Ghahramani, ICML 2016](https://arxiv.org/abs/1506.02142) ]

### MNIST Data
- IID MNIST(digit 0-4)
- OOD MNIST(digit 5-9)

### Tasks

#### Task I: Uncertainty evaluation: test examples from known (IID) vs unknown (OOD) classes

![Predictive Entropy](https://github.com/RamiSketcher/doubt-your-model/blob/main/figures/PE.png)


#### Task II: Accuracy as a function of confidence (Reliability Diagram)

![Reliability Diagram](https://github.com/RamiSketcher/doubt-your-model/blob/main/figures/RD.png)
