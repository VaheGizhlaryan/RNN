This project implements a basic Recurrent Neural Network (RNN) from scratch to generate text character by character.
The RNN model is trained on a given plain text file, learning patterns and dependencies in the data.
It uses a vanilla RNN architecture with optional dropout layers for regularization.
The RNN is trained using the Adagrad optimization algorithm, which adapts the learning rate for each parameter separately.

During training, the model generates sample text periodically to showcase its progress. The generated text becomes increasingly coherent and resembles the patterns found in the training data as the RNN iteratively learns from the input text. The training process continues for a specified number of epochs, updating the model's parameters to minimize the cross-entropy loss.
