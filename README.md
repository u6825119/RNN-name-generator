# RNN-name-generator
English name generating model at character level trained with GRU layers
rnn_name_generator: Generates English names in two modes 
(1) argmax: adapts the character with highest possibilities from the next-character probabilities distribution matrices at each GRU output layer.
(2) sampling: generate random names using thermal sampling with softmax over the probabilities distributions.
