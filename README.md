# Improved-Model-Remediaton-on-CelebA-Dataset
TensorFlow Model Remediation is a library that provides solutions for machine learning practitioners working to create and train models in a way that reduces or eliminates user harm resulting from underlying performance biases.

$ pip install tensorflow-model-remediation
Note: Make sure you are using TensorFlow 2.x.

Documentation

This library contains a collection of machine learning remediation techniques for addressing potential bias in a model.

For the current model we have used the below technique:

MinDiff technique: Typically used to ensure that a model predicts the preferred label equally well for all values of a sensitive attribute. Helpful when trying to achieve equality of opportunity.

Overview of the project:

For the project we have used the MinDiff technique using the Alexnet model as an original model. From the project we can clearly see improvements both in FPR and FNR. The differnce between the slices has reduced. 

Link: https://colab.research.google.com/drive/1YGnRLqT2DvncfwppAQ17fli_OtyWqXkh?usp=sharing
