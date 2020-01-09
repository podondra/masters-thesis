# Neural Networks Based Domain Adaptation in Spectroscopic Sky Surveys

We present an analysis of the impact of neural-based domain adaptation
in astronomical spectroscopy. Domain adaptation addresses the problem
of applying prior knowledge to a new data of interest. Therefore, we selected
a problem of quasar identification in the Large Sky Area Multi-Object Fiber
Spectroscopic Telescope survey using labelled data from the Sloan Digital Sky
Survey. We choose to experiment with four neural models for domain adaptation:
Deep Domain Confusion, Deep Correlation Alignment, Domain-Adversarial Network
and Deep Reconstruction-Classification Network. However, our experiments
reveal that these model cannot improve classification performance
in comparison to a convolutional neural network that does not consider domain
adaptation. Using dimensionality reduction, statistics of the selected methods
and misclassifications, we show that the domain adaptation methods are not
robust enough to be applied to the complex and dirty astronomical data.
