# CIFAR 10 using LeNet5 and Keras

This repository has 1 tasks performed with **LeNet5** on the **Cifar10** Dataset

* Cifar 10 Image Classification


## Network

![LeNet5 Image](https://i.stack.imgur.com/tLKYz.png)

LeNet5 was introduced by [Yan LeCun](http://yann.lecun.com) back in 1998. It's a form of a convolutional network originally intented for the classification of the MNIST Dataset (Handwritten Digits).

* *Activation Functions*: tanh
* *Kernel Size*: 5x5

## Training

Training went on for **10** epochs with a **batch size** of 64

* *Loss Function*: Categorical Cross Entropy
* *Optimizer*: Adam

## Results

| Task                        | Loss  | Accuracy |
|-----------------------------|-------|----------|
| Cifar 10                    | 1.5606 | 0.5354 |



## References

* [Keras](https://keras.io/)
* [TensorFlow](https://www.tensorflow.org)
* [Matplotlib](https://matplotlib.org)
* [Cifar10](https://www.cs.toronto.edu/~kriz/cifar.html)
* [LeNet5](http://yann.lecun.com/exdb/lenet/)
* [Yan LeCun](http://yann.lecun.com)
* [MNIST](http://yann.lecun.com/exdb/mnist/)
