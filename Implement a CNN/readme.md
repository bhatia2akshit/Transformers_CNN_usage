The Implementation is based on Keras Model API and Tensorflow. The architecture uses following information:

1. First layer has 6 filters with kernel sized 5*5.

2. Then a a pooling with size 2*2 is added.

3. Second layer has 16 filters of the kernel with size 5*5.

4. Then we flatten the network.

5. The first dense layers has 1024 neurons.

6. The second dense layer has 128 neurons.

7. Finally the last layer has 10 neurons and each neuron gives the prediction for a number.

in image cnn.jpg, this network is drawn for reference.
