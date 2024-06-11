# Awesome Quantum Machine Learning

A list of awesome papers and cool resources in the field of quantum machine learning (machine learning algorithms running on quantum devices). It does not include the use of classical ML algorithms for quantum purpose. Don't hesitate to suggest resources I could have forgotten (I take pull requests).

# Reviews

* [Quantum Machine Learning: What Quantum Computing Means to Data Mining](https://www.researchgate.net/publication/264825604_Quantum_Machine_Learning_What_Quantum_Computing_Means_to_Data_Mining) (2014)
* [Quantum-enhanced machine learning](https://arxiv.org/abs/1610.08251)
* [Quantum Machine Learning](https://arxiv.org/abs/1611.09347v2) (2016)
* [A Survey of Quantum Learning Theory](https://arxiv.org/abs/1701.06806) (2017)
* [Quantum Machine Learning: a classical perspective](https://arxiv.org/abs/1707.08561) (2017)
* [Opportunities and challenges for quantum-assisted machine learning in near-term quantum computers](https://arxiv.org/abs/1708.09757) (2017)
* [Quantum machine learning for data scientists](https://arxiv.org/abs/1804.10068) (2018)
* [Supervised Learning with Quantum Computers](https://www.springer.com/gp/book/9783319964232) (2018)
* [A non-review of Quantum Machine Learning: trends and explorations](https://quantum-journal.org/views/qv-2020-03-17-32/) (2020)

# Discrete-variables quantum computing

## Variational circuits

Variational circuits are quantum circuits with variable parameters that can be optimized to compute a given function. They can for instance be used to classify or predict properties of quantum and classical data, sample over complicated probability distributions (as generative models), or solve optimization and simulation problems.

### Theory

* [Quantum Statistical Inference](https://arxiv.org/abs/1812.04877) (2018)
* [The Expressive Power of Parameterized Quantum Circuits](https://arxiv.org/abs/1810.11922) (2018)
* [Quantum hardness of learning shallow classical circuits](https://arxiv.org/abs/1903.02840) (2019)
* [The power of quantum neural networks](https://arxiv.org/abs/2011.00027) (2020)
* [Power of data in quantum machine learning](http://arxiv.org/abs/2011.01938) (2020)
* [Information-theoretic bounds on quantum advantage in machine learning](https://arxiv.org/abs/2101.02464) (2021)
* [Structural risk minimization for quantum linear classifiers](https://arxiv.org/abs/2105.05566) (2021)
* [Generalization in quantum machine learning from few training data](http://arxiv.org/abs/2111.05292) (2021)

### Data-encoding

* [Robust data encodings for quantum classifiers](https://arxiv.org/abs/2003.01695) (2020)
* [Quantum embeddings for machine learning](https://arxiv.org/abs/2001.03622) (2020)
* [Quantum algorithms for approximate function loading](http://arxiv.org/abs/2111.07933) (2021)
* [Quantum Polar Metric Learning: Efficient Classically Learned Quantum Embeddings](https://arxiv.org/abs/2312.01655) (2023)

### Classification and regression

* [Quantum Perceptron Model](https://arxiv.org/abs/1602.04799) (2016)
* [Quantum Neuron: an elementary building block for machine learning on quantum computers](https://arxiv.org/abs/1711.11240) (2017)
* [A quantum algorithm to train neural networks using low-depth circuits](https://arxiv.org/abs/1712.05304) (2017)
* [Classification with Quantum Neural Networks on Near Term Processors](https://arxiv.org/abs/1802.06002) (2018)
* [Towards Quantum Machine Learning with Tensor Networks](https://arxiv.org/abs/1803.11537) (2018)
* [Hierarchical quantum classifiers](https://arxiv.org/abs/1804.03680v1) (2018)
* [Circuit-centric quantum classifiers](https://arxiv.org/abs/1804.00633) (2018)
* [Universal discriminative quantum neural networks](https://arxiv.org/abs/1805.08654) (2018)
* [A Universal Training Algorithm for Quantum Deep Learning](https://arxiv.org/abs/1806.09729) (2018)
* [Quantum Convolutional Neural Networks](https://arxiv.org/abs/1810.03787) (2018)
* [An Artificial Neuron Implemented on an Actual Quantum Processor](https://arxiv.org/pdf/1811.02266.pdf) (2018)
* [Efficient Learning for Deep Quantum Neural Networks](https://arxiv.org/abs/1902.10445) (2019)
* [Parameterized quantum circuits as machine learning models](https://arxiv.org/abs/1906.07682) (2019)
* [Machine Learning Phase Transitions with a Quantum Processor](https://arxiv.org/abs/1906.10155) (2019)
* [Hybrid Quantum-Classical Convolutional Neural Networks](https://arxiv.org/abs/1911.02998) (2019)
* [Building quantum neural networks based on a swap test](https://arxiv.org/abs/1904.12697) (2019)
* [Data re-uploading for a universal quantum classifier](https://quantum-journal.org/papers/q-2020-02-06-226/) (2020)
* [Quantum Earth Mover's Distance: A New Approach to Learning Quantum Data](https://arxiv.org/abs/2101.03037) (2021)
* [Certificates of quantum many-body properties assisted by machine learning](https://arxiv.org/abs/2103.03830) (2021)
* [Quantum optimization for training quantum neural networks](https://arxiv.org/abs/2103.17047) (2021)
* [Provable Advantage in Quantum Phase Learning via Quantum Kernel Alphatron](https://arxiv.org/abs/2111.07553) (2021)

### Generative models

* [Quantum Boltzmann Machine](https://arxiv.org/abs/1601.02036) (2016)
* [A Quantum Hopfield Neural Network](https://arxiv.org/abs/1710.03599) (2017)
* [A generative modeling approach for benchmarking and training shallow quantum circuits](https://arxiv.org/abs/1801.07686) (2018)
* [Universal quantum perceptron as efficient unitary approximators](https://arxiv.org/abs/1801.00934) (2018)
* [Quantum generative adversarial learning in a superconducting quantum circuit](https://arxiv.org/abs/1808.02893) (2018)
* [Quantum generative adversarial learning](https://arxiv.org/abs/1804.09139) (2018)
* [Quantum generative adversarial networks](https://arxiv.org/abs/1804.08641) (2018)
* [Differentiable Learning of Quantum Circuit Born Machine](https://arxiv.org/abs/1804.04168) (2018)
* [The Born Supremacy: Quantum Advantage and Training of an Ising Born Machine](https://arxiv.org/abs/1904.02214) (2019)
* [Entangling Quantum Generative Adversarial Networks](https://arxiv.org/abs/2105.00080) (2021)


### Reinforcement learning

* [Advances in Quantum Reinforcement Learning](https://arxiv.org/abs/1811.08676) (2018)
* [Quantum Enhancements for Deep Reinforcement Learning in Large Spaces](https://arxiv.org/abs/1910.12760) (2019)
* [Quantum agents in the Gym: a variational quantum algorithm for deep Q-learning](https://arxiv.org/abs/2103.15084) (2021)
* [Variational quantum policies for reinforcement learning](https://arxiv.org/abs/2103.05577) (2021)

### Kernel methods and SVM

Quantum circuits that are used to extract features from data or to improve kernel-based ML algorithms in general

* [Supervised learning with quantum enhanced feature spaces](https://arxiv.org/abs/1804.11326) (2018)
* [Quantum Sparse Support Vector Machines](https://arxiv.org/abs/1902.01879) (2019)
* [Sublinear quantum algorithms for training linear and kernel-based classifiers](https://arxiv.org/pdf/1904.02276.pdf) (2019)
* [Supervised quantum machine learning models are kernel methods](http://arxiv.org/abs/2101.11020) (2021)

### Auto-encoders

* [Quantum autoencoders via quantum adders with genetic algorithms](https://arxiv.org/abs/1709.07409) (2017)
* [Quantum Variational Autoencoder](https://arxiv.org/abs/1802.05779) (2018)

### Bayesian approaches

* [Bayesian Deep Learning on a Quantum Computer](https://arxiv.org/abs/1806.11463) (2018)
* [Variational inference with a quantum computer](https://arxiv.org/abs/2103.06720) (2021)

### Barren plateau

The barren plateau phenomenon occurs when the gradient of a variational circuit vanishes exponentially with the system size for a random initialization. When an architecture exhibits this phenomenon, it hinders its potential for being trainable at large-scale.

* [Barren plateaus in quantum neural network training landscapes](https://arxiv.org/abs/1803.11173) (2018)
* [An initialization strategy for addressing barren plateaus in parametrized quantum circuits](https://arxiv.org/abs/1903.05076) (2019)
* [Cost function dependent barren plateaus in shallow parametrized quantum circuits](https://arxiv.org/abs/2001.00550) (2020)
* [Trainability of Dissipative Perceptron-Based Quantum Neural Networks](https://arxiv.org/abs/2005.12458) (2020)
* [Noise-Induced Barren Plateaus in Variational Quantum Algorithms](https://arxiv.org/abs/2007.14384) (2020)
* [Impact of barren plateaus on the hessian and higher order derivatives](https://arxiv.org/abs/2008.07454) (2020)
* [Entanglement Induced Barren Plateaus](https://arxiv.org/abs/2010.15968) (2020)
* [Absence of Barren Plateaus in Quantum Convolutional Neural Networks](https://arxiv.org/abs/2011.02966) (2020)
* [Analyzing the barren plateau phenomenon in training quantum neural networks with the ZX-calculus](https://arxiv.org/abs/2102.01828) (2021)
* [Effect of barren plateaus on gradient-free optimization](https://arxiv.org/abs/2011.12245) (2020)
* [Connecting ansatz expressibility to gradient magnitudes and barren plateaus](https://arxiv.org/abs/2101.02138) (2021)
* [Equivalence of quantum barren plateaus to cost concentration and narrow gorges](https://arxiv.org/abs/2104.05868) (2021)


## QRAM-based quantum ML

The following QML algorithms assume the existence of an efficient way to load classical data on a quantum device, such as a quantum RAM (QRAM). While this can be a complicated requirement in the short-term, QRAM-based algorithms often come with a rigourously-proven speed-up.

### Classification and regression

* [Quantum algorithms for feedforward neural networks](https://arxiv.org/abs/1812.03089) (2018)
* [Quantum classification of the MNIST dataset with Slow Feature Analysis](https://arxiv.org/abs/1805.08837) (2018)
* [Quantum algorithms for Second-Order Cone Programming and Support Vector Machines](https://arxiv.org/abs/1908.06720) (2019)
* [Quantum Algorithms for Deep Convolutional Neural Networks](https://arxiv.org/abs/1911.01117) (2019)
* [Quantum speed-up in global optimization of binary neural nets](https://iopscience.iop.org/article/10.1088/1367-2630/abc9ef/meta) (2021)
* [Classical and Quantum Algorithms for Orthogonal Neural Networks](https://arxiv.org/abs/2106.07198) (2021)

### Unsupervised learning

* [Quantum principal component analysis](https://arxiv.org/abs/1307.0401) (2013)
* [Quantum algorithms for topological and geometric analysis of big data](https://arxiv.org/abs/1408.3106) (2014)
* [Quantum Recommendation Systems](https://arxiv.org/abs/1603.08675) (2016)
* [Smooth input preparation for quantum and quantum-inspired machine learning](https://arxiv.org/abs/1804.00281) (2018)
* [q-means: A quantum algorithm for unsupervised machine learning](https://arxiv.org/abs/1812.03584) (2018)
* [Quantum expectation-maximization for Gaussian mixture models](https://arxiv.org/abs/1908.06657) (2019)
* [Towards quantum advantage via topological data analysis](https://arxiv.org/abs/2005.02607) (2020)
* [Quantum Spectral Clustering](https://arxiv.org/abs/2007.00280) (2020)
* [Quantum Algorithms for Data Representation and Analysis](https://arxiv.org/abs/2104.08987) (2021)
* [Resonant Quantum Principal Component Analysis](https://arxiv.org/abs/2104.02476) (2021)
* [Quantum algorithms for group convolution, cross-correlation, and equivariant transformations](https://arxiv.org/abs/2109.11330) (2021)

### Reinforcement learning

* [Quantum reinforcement learning](https://arxiv.org/abs/0810.3828) (2008)
* [Generalized Quantum Reinforcement Learning with Quantum Technologies](https://arxiv.org/abs/1709.07848) (2017)
* [Speeding-up the decision making of a learning agent using an ion trap quantum processor](https://arxiv.org/abs/1709.01366) (2017)
* [Exponential improvements for quantum-accessible reinforcement learning](https://arxiv.org/abs/1710.11160) (2017)
* [Advances in Quantum Reinforcement Learning](https://arxiv.org/abs/1811.08676) (2018)
* [Quantum-accessible reinforcement learning beyond strictly epochal environments](https://arxiv.org/abs/2008.01481) (2020)
* [Experimental quantum speed-up in reinforcement learning agents](https://arxiv.org/abs/2103.06294) (2021)

### Optimization

* [Quantum gradient descent and Newton’s method for constrained polynomial optimization](https://arxiv.org/abs/1612.01789) (2016)
* [Quantum gradient descent for linear systems and least squares](https://arxiv.org/abs/1704.04992) (2017)
* [Quantum algorithms and lower bounds for convex optimization](https://arxiv.org/pdf/1809.01731.pdf) (2018)

### Dequantization of QRAM-based QML

Kingdom of Ewin Tang. Papers showing that a given quantum machine learning algorithm does not lead to any improved performance compared to a classical equivalent (either asymptotically or including constant factors):

* [A quantum-inspired classical algorithm for recommendation systems](https://arxiv.org/abs/1807.04271) (2018)
* [Quantum-inspired classical algorithms for principal component analysis and supervised clustering](https://arxiv.org/abs/1811.00414) (2018)
* [Quantum-inspired low-rank stochastic regression with logarithmic dependence on the dimension](https://arxiv.org/abs/1811.04909) (2018)
* [Quantum-inspired algorithms in practice](https://arxiv.org/abs/1905.10415) (2019)
* [Sampling-based sublinear low-rank matrix arithmetic framework for dequantizing quantum machine learning](https://arxiv.org/abs/1910.06151) (2019)

## Applications

* [Graph Cut Segmentation Methods Revisited with a Quantum Algorithm](https://arxiv.org/abs/1812.03050) (2018)
* [Quantum Medical Imaging Algorithms](https://arxiv.org/abs/2004.02036) (2020)
* [Quantum Machine Learning in High Energy Physics](https://arxiv.org/abs/2005.08582) (2020)
* [Medical image classification via quantum neural networks](https://arxiv.org/abs/2109.01831) (2021)

## Software

* [TensorFlow Quantum: A Software Framework for Quantum Machine Learning](https://arxiv.org/abs/2003.02989) (2020)

# Continuous-variables quantum computing

## Variational circuits

* [Continuous-variable quantum neural networks](https://arxiv.org/abs/1806.06871) (2018)
* [Machine learning method for state preparation and gate synthesis on photonic quantum computers](https://arxiv.org/abs/1807.10781) (2018)
* [Near-deterministic production of universal quantum photonic gates enhanced by machine learning](https://arxiv.org/abs/1809.04680) (2018)
* [A Continuous Variable Born Machine](https://arxiv.org/abs/2011.00904) (2020)

## Kernel methods and SVM

* [Quantum machine learning in feature Hilbert spaces](https://arxiv.org/1803.07128) (2018)

# Other awesome lists

* [Awesome Quantum Machine Learning](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning)
* [Awesome Quantum Computing](https://github.com/desireevl/awesome-quantum-computing)
* [A Guide to QC and QI](https://github.com/gate42qc/Guide-to-QC-and-QI)
