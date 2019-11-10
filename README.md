All files are taken from the Udemy course, "Deep Learning with Python and Keras", by Data Weekends, Jose Portilla, Francesco Mosconi.

# Deep Learning

### Artificial Neural Networks (ANN)
    1/ Artificial Neural Network:   A network of neurons (nodes). 
    2/ Deeper Neural Network:   A network that has multiple hidden layers.
    3/ Activation Function:     A function that defines the output of that node, given inputs.
    4/ FeedForward:             A neural network where node connections do form a cycle.
    5/ Gradient Descent:        A optimization algorithm that finds the minimum of a cost function.
    6/ Backpropagation:         An algorithm that calculates the gradient of the error function with respect to the neural network's weight.        
    7/ Learning Rate:           An amount that weights are updated during training, also known as Step Size.
    8/ EWMA:                    A statistic for monitoring the process that averages the data in a way that gives less and less weight to data as they are furthey removed in time.
    9/ Optimizers:              An alogorithm that ties both loss function and model parameter by updating the model in response to the output of the loss function.

### Convolutional Neural Networks (CNN)
    1/ Convolution in 1 Dimension:  used effectively when deriving interesting feature from fix-length segments of the overall data set. Highly applied to any kind of signal data analysis such as audio signal, NLP (LSTM is more promising). 
    2/ Convolution in 2 Dimensions: highly used when dealing with a back-gray image, which consists of 2 dimensions.
    3/ Convolution in 3 Dimensions: highly used when dealing with a colored image, which consists of 3 dimensions.

### Recurent Neural Networks (RNN)
    1/ Time Series:     A series of data points indexed in time order, where the sequence of points is taken at equally spaced.
    2/ Vanilla RNN:     Networks with a loop in them to retain information. 
    3/ LSTM and GRU:    There is a problem of long-term memory with Vanilla RNN, LSTM and GRU are capable of learning long-term dependencies. 
    4/ Rolling Window:  Conducting regression many times with subsamples of original full sample along with rolling time window.

### Improving Performance
    1/ Learning Curve:
    2/ Batch Normalization:
    3/ Dropout:
    4/ Data Augmentation:
    5/ Transfer Learning (Continuous Learning - Fine Tuning):
    6/ Hyperparameter Searches:
    7/ Embeddings:
