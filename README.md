﻿# Neural-Network-from-scratch

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

![image](https://user-images.githubusercontent.com/73353537/153706848-101e2478-8f35-40d4-ab67-af18f5a91502.png)

Image from: [](https://towardsdatascience.com/neural-networks-from-scratch-easy-vs-hard-b26ddc2e89c7)

Note that you can try the network with different number of hidden layers, nodes and activation function. However the last layer will always be softamx because I was trying to solve a classification problem and I've used softmax with cross-entropy loss.

I implemented SGD optimizer as well and you can change the batch size each time.

Some results:

![image](https://user-images.githubusercontent.com/73353537/153706870-93d3b73b-c5f7-4646-a673-6aee4dc8a055.png)


