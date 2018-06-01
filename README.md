## The Good'ol MNIST!

MNIST is a classic dataset consisting of hand-written digits. This dataset is extensively used to test several ML algorithms upon. Though very simple, this dataset gets you going in the domain. In this project, I establish the power of Convolutional Neural Networks in image recognition by an extremely simple neural network.    
More about MNIST at [Wikipedia](https://en.wikipedia.org/wiki/MNIST_database).

### Convolutional Neural Networks
Flattening images as vectors results in the loss of spatial information. Further, for flattened images, even of a meagre 1MP resolution, a **million** parameters are needed. That's the figure for a single layer. Imagine what the case can be for a Deep Network! (The present day state-of-the-art networks have more than a hundred layers!) The number would be impractical even for modest network sizes.  


Convolution Operations in the networks serve two purposes:  
  
1. Preserving the spatial information, as there is no flattening involved and  
2. Reducing the parameters, by weight sharing.

### The Project  
I used a very simple model, having just two Convolutional blocks. Such a simple model delivers accuracies above 99%. This testifies the effectiveness of Convolutional Models.   
Here's a few bits of my project:  
<img src = "https://github.com/PradyumnaCh/MNIST/blob/master/images/summary.png"  align="middle" width="500" height="400">
<img src = "https://github.com/PradyumnaCh/MNIST/blob/master/images/dataset.png" align="middle" width="450" height="300" >
<img src = "https://github.com/PradyumnaCh/MNIST/blob/master/images/predictions.png" align="middle" width="470" height="330">  


__Visit my GitHub [here](https://github.com/PradyumnaCh/).__
