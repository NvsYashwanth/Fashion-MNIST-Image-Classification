# Fashion-MNIST
`Fashion-MNIST` is a dataset of [Zalando](https://jobs.zalando.com/tech/)'s article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. `Fashion-MNIST` serves as a direct **drop-in replacement** for the original [MNIST dataset](http://yann.lecun.com/exdb/mnist/) for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

Here's an example how the data looks (each class takes three-rows):
![](https://github.com/NvsYashwanth/Fashion-MNIST/blob/master/Images/fashion-mnist-sprite.png)

### Labels
Each training and test example is assigned to one of the following labels:

| Label | Description |
| --- | --- |
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

## Results
* A validation dataset of size 12,000 was deduced from the Training dataset with its size being changed to 48,000.
* This linear model uses 784 nodes at input layer, 512, 256 nodes in the first and second hidden layers respectively, with ouput layer of 10 nodes (10 classes).
* The test accuracy is ***89%*** (***This result uses dropout probability of 20%***)
* A "model.pt" file has been included. With this one can directly load the model state_dict and use for testing.
