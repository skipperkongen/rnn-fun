# RNN Fun

This repo contains fun examples of using RNNs (i.e. LSTMs).

- Generate poetry with a character-level language model
- Reinforcement learning for boat-balancing problem (TODO)

## Generate poetry with a character-level language model

The directory `generate-poetry` contains this example, including all files need to train.

You need:

- Python 3
- Numpy
- Tensorflow 1.8
- Keras
- Jupyter

Open the Jupyter notebook `generate-poetry.ipynb` and run all the cells.

Please note that training can take a long time (many hours).
You can safely skip the "training" cell and generate poetry from the
pre-trained models, i.e. run cells before and after "training".

### Background material

Slight modification of code in the article [Text Generation With LSTM Recurrent Neural Networks in Python with Keras](https://machinelearningmastery.com/text-generation-lstm-recurrent-neural-networks-python-keras/).

Other material:

- [Character-Aware Neural Language Models](https://arxiv.org/abs/1508.06615)
- [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)

### Fixing runtime errors

You may need to update your version of Tensorflow (use `pip` not `conda` command):

```
pip install --upgrade tensorflow
```

I have tested with version 1.8 of Tensorflow.
