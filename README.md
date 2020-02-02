
## Sequence to Sequence generation.

Recurrent Neural Network(LSTM) for Sequence Prediction, here the encoder-decoder architecture is used to predict the output sequence.

For character wise seq-to-seq prediction: 

run the code

**python LSTM-seq-generator.py**

For word wise seq-to-seq prediction: 

run the code

**python LSTM-words-generator.py**

## Hyperparameters:

| Hyperparameter  | Value         |
| -------------   | ------------- |
| batch_size      |  10           |
| epochs          |  500          |
| validation_split|  0.05         |
| embedding_size  |  50           |
| LSTM layers     |  1            |
