# Tensorflow--
getting started with training models...
1. First of all you need to install the latest version of Anaconda
2. Run Anaconda as administrator
2. Then install jupyter notebook on Anaconda
3. click on Environments on the top let corner
4. Type Tensorflow in the "Search Environments" tab
5. Then download it
6. Similarly type Keras and install it too
7. Open your jupyter notebook and bang-on you are all ready to go
8. import tensorflow as tf >>> on jupyter notebook and it will run smoothly
9. import keras >>> on jupyter and it will run smoothly
10. some useful commands
  1. from keras.datasets import mnist # for loading datasets that are already available
  2. mnist.load_data() # for loading data
  3. from keras import models # importing models from keras
  4. from keras import layers # importing layers from keras
  5. network = models.Sequential() # using Sequential() method to add layers, etc
  6. network.add(layers.Dense(Density, activation = 'any activation function', input_shape= (input layes shape)))
  7. activation functions can be sigmoid, ReLU, Leaky ReLU, Tanh, etc. most commonly used is ReLU where as for output layer sigmoid is used.
  8. network.compile(optimizer='any optimizer', loss='any loss calculating method', metrics=['accuracy']) 
  9. network.fit(train_image, train_lable, epochs=of your choice, batch_size=of your choice)
  10. test_loss, test_acc = network.evaluate(test_image, test_lable) 
  11. print('test_acc:', test_acc) 
11. Help taken from Sir Rauf Ur Rahim (PIAIC teacher)
