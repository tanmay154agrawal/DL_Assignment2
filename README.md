# DL_Assignment2
## LSTM

This is an implementation of a Long Short-Term Memory (LSTM) network for sequence modeling, built using TensorFlow.

LSTM is a type of Recurrent Neural Network (RNN) that can model temporal dependencies in data by maintaining a hidden state and selectively forgetting and remembering information over time. This makes it well-suited for tasks such as speech recognition, language translation, and image captioning.
## Dependencies
Python 3.5 or higher  
Pytorch   
NumPy   
Pandas    
## Usage
Clone this repository.   
Install the dependencies listed above.   
Prepare your training data in a suitable format (e.g. a NumPy array with shape (num_samples, sequence_length, num_features)).    
Instantiate an instance of the LSTM class with the desired hyperparameters.    
Train the model    
Test the model    
## Hyperparameters
hidden_size: the number of neurons in each LSTM layer   
num_layers: the number of LSTM layers in the network    
dropout: the dropout rate applied between LSTM layers    
learning_rate: the learning rate used for optimization    
batch_size: the batch size used for training     
epochs: the number of training epochs         
## Credits
This implementation was created by Tanmay Agrawal. It is based on the TensorFlow documentation and the following resources:   
 https://towardsdatascience.com/a-comprehensive-guide-to-neural-machine-translationusing-seq2sequence-modelling-using-pytorch-41c9b84ba350  
 https://machinelearningmastery.com/define-encoder-decoder-sequence-sequence-modelneural-machine-translation-keras/    
 


