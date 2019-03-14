
# NER-Test
## Requirements
 - python 3.6
 - pytorch
 - gensim
 - nltk
 - TorchCRF (pip install git+https://github.com/s14t284/TorchCRF#egg=TorchCRF)

## Testing NER with different models for small sized dataset.
1. NER_using_RNN-using-word2vec.ipynb have LSTM-linear classifier with input feature word2vec.
2. NER_using_RNN-using-word2vec-pos.ipynb have LSTM-linear classifier with input features word2vec & pos(onehot-encode).
3. NER_using_LSTM_CRF-using-word2vec.ipynb have LSTM-linear classifier with input features word2vec.
4. NER_using_LSTM_CRF-using-word2vec-posFAIL.ipynb have LSTM-linear classifier with input features word2vec & pos(onehot-encode). FAIL
