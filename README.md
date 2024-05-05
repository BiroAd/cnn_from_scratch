# Image classification from scratch

This repo hosts my homework project for the course [Neural networks](http://www.mit.bme.hu/oktatas/targyak/vimijv07) at Budapest University of Technology and Economics. The project is a solution for classifying [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) images from scratch. I did not use any high level framework like tensorflow for this work, only numpy.

During my homework, I tried multiple architectural solutions. The notebook demonstrates how the different models perform in comparison.

## Result

In the IPython notebook, you can clearly see that the best models achieved 72% accuracy. I experimented with models using dropout and without dropout, indicating that overfitting was likely not the limiting factor. Deeper architectures could potentially improve accuracy.
