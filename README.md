# Chatbot
Chatbot which can give answers of your questions based on a given story

## Start with analysing the dataset
- Here, in our data we have certain set of stories followed by a question.
- And, we tend to create a chatbot which answers these questions as a yes or a no.

## Initial Steps
- To begin with, we need to set up a vocabulary of all the words we have in our dataset.
- We need to take in account both train and test dataset.
- Now, we need to do text preprocessing, i.e convert raw text into vectors using pad sequences and tokenizer.

## We can then start building our neural network
We create input encoder M, input encoder C & Question Encoder by imorting the following:
- from keras.models import Sequential,Model
- from keras.layers.embeddings import Embedding
- from keras.layers import Input,Activation,Dense,Permute,Dropout,add,dot,concatenate,LSTM

## Achievement
- Achieved 99.99% accuracy rate

## Additional 
- We can write our own stories and questions and run through the model
- But, we can only use the words which my model is aware of, the ones which are there in the vocab
- Achieved 97.93% accuracy for the same

