# Super-Convergence: Very Fast Training of Neural Networks Using Large Learning Rates

This post describe a phenomenon, which goes by name “super-convergence”,
where neural networks can be trained an order of magnitude faster than with
standard training methods. The existence of super-convergence is relevant to
understanding why deep networks generalize well. One of the key elements of
super-convergence is training with one learning rate cycle and a large maximum
learning rate. A primary insight that allows super-convergence training is that large
learning rates regularize the training, hence requiring a reduction of all other forms
of regularization in order to preserve an optimal regularization balance
