# Neural-Network-from-scratch

In this notebook I've implemeneted a fully paramtrized neural network from scratch using only numpy library. 

To follow this notebook you have to install numpy, pandas and matplotlib:

```
pip install numpy pandas matplotlib
```

or if you're using [Anaconda Distribution](https://anaconda.org/)

```
conda install numpy pandas matplotlib
```

The data can be downloaded from [Kaggle](https://www.kaggle.com/zalando-research/fashionmnist).

In this notebook I've implemented forward and backpropagation algorithms using the partial derivatives. For updating weight i've used gradient descent algortihms.

![image](https://user-images.githubusercontent.com/73353537/153706897-d920b25d-9417-4f76-8bca-7504f75a1999.png)

Note that you can try the network with different number of hidden layers, nodes and activation function. However the last layer will always be softamx because I was trying to solve a classification problem and I've used softmax with cross-entropy loss.

I implemented SGD optimizer as well and you can change the batch size each time.

Some results:
![image](https://user-images.githubusercontent.com/73353537/153706904-f1a1c311-5c29-44b1-926c-a1188ecb7ca0.png)
