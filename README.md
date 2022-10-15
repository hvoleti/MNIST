# MNIST

Implementing ANN in Pytorch and CNN in both Pytorch and Tensorflow on MNIST Data


## Observation

This project helped me understand why CNN works best for image classification rather than ANN. 
We know that image consist of large data due to the number of pixels , the dimensions of input features would be large too.

Now, Artificial Neural Nets have large number of parameters due to their connections. It tends to overfitting as the complexity of the model increases with the parameters.

![image](https://user-images.githubusercontent.com/81815144/195981158-c69d85ad-7b52-470e-a350-798569fdf57d.png)

Whereas, if you consider a Convolutional Neural Network, it learns are subjected to operations like pooling and filtration which has less parameters. This reduces chances of complexity eventually reducing overfitting! 

![image](https://user-images.githubusercontent.com/81815144/195981369-7053340c-4bd6-4192-b792-044340eeaa00.png)


