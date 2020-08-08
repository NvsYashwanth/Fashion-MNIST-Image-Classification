# Fashion-MNIST
`Fashion-MNIST` is a dataset of [Zalando](https://jobs.zalando.com/tech/)'s article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. `Fashion-MNIST` serves as a direct **drop-in replacement** for the original [MNIST dataset](http://yann.lecun.com/exdb/mnist/) for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

Here's an example how the data looks (each class takes three-rows):
![](https://github.com/NvsYashwanth/Fashion-MNIST/blob/master/Images/fashion-mnist-sprite.png)
A validation dataset of size 12,000 was deduced from the Training dataset with its size being changed to 48,000. This linear model uses 784 nodes (image pixels) at input layer, 512, 256 nodes in the first and second hidden layer, with the ouput layer of 10 nodes each for a class. A "model.pt" file has been included. With this one can directly load the model state_dict and use for testing. With a dropout probability of 20%, this model achieves 89% overall accuracy.
