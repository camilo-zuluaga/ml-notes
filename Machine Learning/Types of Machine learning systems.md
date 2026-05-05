# Types of Machine learning

There are so many different types of machine learning that it is useful to classify them in broad categories following this criteria:
1. How are they supervised (supervised, unsupervised, semi-supervised, self-supervised, and others)
2. Can they learn on the fly (online vs batch learning)
3. Whether they work by simply comparing new data to known data, or detecting patterns to make predictions (instance-based vs model-based learning)

These criteria are not exclusive; you can combine them in any way you like.

# Training supervision
ML systems can be classified according to the amount and type of classification they get during training: supervised learning, unsupervised leaning, semi-supervised learning, self-supervised learning an reinforcement learning.

1. [Supervised learning](./types-machine-learning/Supervised%20learning.md)

2. [Unsupervised learning](./types-machine-learning/Unsupervised%20learning.md)

3. [Semi-supervised learning](./types-machine-learning/Semi-supervised%20learning.md)

4. [Self-supervised learning](./types-machine-learning/Self-supervised%20learning.md)

5. [Reinforcement learning](./types-machine-learning/Reinforcement%20learning.md)

# Batch Versus Online learning
Another criteria to classify machine learning systems, is if they can learn incrementally from a stream of incoming data.

1. [Batch Learning](./types-machine-learning/Batch%20Learning.md)
2. [Online Learning](./types-machine-learning/Online%20Learning.md)

# Instance-Based Versus Model-Based Learning
One more way to categorize machine learning systems is by how they *generalize*. Most machine learning tasks consist of making predictions on new instances, so it needs to be able to make good predictions (generalize) for examples it has never seen before.

1. [Instance-based Learning](./types-machine-learning/Instance-based%20Learning.md)
2. [Model-based Learning](./types-machine-learning/Model-based%20Learning.md)

# Typical Machine learning workflow
### Summary:
- You study the data.
- You select a model.
- You train it on the training data.
- Finally, you apply the model to make predictions on new cases (*inference*) hoping it generalizes well.