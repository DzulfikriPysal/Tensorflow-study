# Simple tensorflow model for MNIST

click this link to view the jupyter notebook incase error to open the jupyter notebook in GitHub LINK -> 
https://nbviewer.jupyter.org/github/Opapis/Tensorflow-study/blob/master/2%20-%20simple%20tensorflow%20model%20for%20mnist/Untitled.ipynb


This work is just to use tensorflow to create simple model with dense layer to train on MNIST dataset provided by TensorFlow.
First, is to get the MNIST dataset from collection of ready used dataset prepared by tensorflow. MNIST is one of the popular used dataset  used for machine learning. MNIST (Modified National Institute of Standards and Technology) is a large database of handwritten digits that is commonly used for training various image processing systems.The data will be the collection of handwrittern digit from 0 until 9.

<br />
<p align="center">
<img src="screenshot/1.PNG" data-canonical-src="screenshot/1.PNG" width="300" />
</p>

Then, load and split the dataset into training and test variable. Each of the training and  test will have it own data and label.

<p align="center">
<img src="screenshot/2.PNG" data-canonical-src="screenshot/1.PNG" width="500"  />
</p>

After done with the data that will be used, then we prepared the deep learning model that will be used to train for the MNIST dataset. The model used will have 4 layer that connect together to form fully connected neural network.

<p align="center">
<img src="screenshot/3.PNG" data-canonical-src="screenshot/1.PNG" width="500"  />
</p>

After done with the model, we need to compile the model before can be used for training.

<p align="center">
<img src="screenshot/4.PNG" data-canonical-src="screenshot/1.PNG" width="500"  />
</p>

Figure below shows the summary of the model used in the work.

<p align="center">
<img src="screenshot/5.PNG" data-canonical-src="screenshot/1.PNG" width="600"  />
</p>

To train the model, we need to call back the model that have been compiled before and fit with the training dataset and the respective label for each data. then we set the epoch of the model. Epoch is defined as a single pass through the entire training set while training the model that have been compiled. In a single epoch, all training samples are presented to the model once. So the total number of epochs in training a model gives the number of cycles through the entire training.

<p align="center">
<img src="screenshot/6.PNG" data-canonical-src="screenshot/1.PNG" width="900"  />
</p>

After done with training the model, we need to evaluate the model performance by using the evaluate data to test the model. from that we get the model evaluation accuracy which is almost 98% of accuracy.

<p align="center">
<img src="screenshot/7.PNG" data-canonical-src="screenshot/1.PNG" width="900"  />
</p>
