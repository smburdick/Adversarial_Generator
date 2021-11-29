# Generating Adversarial Examples with a SAT Solver
Adversarial examples are specialized inputs created with the intension of confusing a neural network classifier, resulting in a misprediction of the given image. 

![](https://www.tensorflow.org/tutorials/generative/images/adversarial_example.png)

Often the changes to these inputs are indistinguishable to humans, but still cause the model to mispredict. 

We can include these adversarial images back into our train set to help improve model perforamnce. 

In this notebook we explore searching for adversarial examples with the [Z3 SMT Solver](https://ericpony.github.io/z3py-tutorial/guide-examples.html) as the core of our engine. The notebook includes two demos: 
1. Simple binary classifier with two features
2. Multi-class classifier on the infamous [MNIST dataset](https://en.wikipedia.org/wiki/MNIST_database). 

This project is for McGill University's Fall 2021 COMP597 Final Project. 

## References

Athalye, Anish. “Synthesizing Robust Adversarial Examples.” Arxiv.org, 7 June 2018, https://arxiv.org/pdf/1707.07397.pdf. 

Pei, Kexin. “DeepXplore: Automated Whitebox Testing of Deep Learning Systems.” Arxiv.org, 24 Sept. 2017, https://arxiv.org/pdf/1705.06640.pdf. 
