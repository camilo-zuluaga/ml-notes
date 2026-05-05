# Model-based Learning

## Summary
Another way to generalize from a set of examples is by building a *model* of these examples and then use it to make *predictions*. This one relies on pure mathematical and statistical algorithms.

So this model can have parameters to an equation or function that are represented as $\theta$, so for example you can have: $h(x) = \theta_{0}x_{0} + \theta_{1}x_{1} ... \theta_{0}x_{0}\theta_{n}x_{n}$, in which $x$ are our attributes, to know what parameters values $\theta_{n}$ will make our model perform the best. You will need to specify a performance measure, by either define an *utility function* that measure how good your model is, or define a *cost function* that measures how bad your model is.

> *For linear regression problems, people typically use a cost function that measures the distance between the linear model’s predictions and the training examples; the objective is to minimize this distance.*

### Learning
- The model is trained on large datasets and then used to make predictions on new data.
    - Can be thought as a set of rules that the machine uses to make predictions.

### Advantages
- Faster predictions
- More accuracy
- Better understanding of data

### Downsides
- Requires a large dataset
- Needs the expert knowledge of statistical algorithms and mathematical modeling.

> *Model selection consists in choosing the type of model and fully specifying its architecture, and the final result. Training a model means running an algorithm to find the model parameters that will make it best fit the data to hopefully make good predictions on new data.*
