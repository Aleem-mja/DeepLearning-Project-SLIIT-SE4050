
# DeepLearning-Project-SLIIT-SE4050
## IT22339324 - Wijerathne M A S M
## Sentiment Analysis on Movie Reviews using Bidirectional LSTM 
This notebook implements a supervised text classification model using a Bidirectional Long Short-Term Memory (BiLSTM) neural network.No pretrained weights are used — both the embedding and LSTM are trained on IMDB from scratch. <br>
The goal is to classify movie review texts as positive or negative by capturing the semantic and contextual meaning of words within sentences.
### Features
- Data preprocessing (cleaning, tokenization, lemmatization, stopword removal)
- Word embeddings using **GloVe (Global Vectors for Word Representation)**
- **Bidirectional LSTM** model for deep text understanding
- Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix
- Option to test the model with **custom movie reviews**
### Dataset
The dataset used is the **IMDB Movie Review Dataset (aclImdb)**:
- 25,000 training reviews  
- 25,000 test reviews  
- Balanced between positive and negative sentiments  
Dataset source: [IMDB Large Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
