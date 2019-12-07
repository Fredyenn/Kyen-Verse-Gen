# Rap Lyrics Generator - Kanye West

## Introduction
This project uses 300+ Kanye West's verses to train on Recurrent Nural Network (RNN). The verses file is [from a dataset on Kaggle](https://www.kaggle.com/viccalexander/kanyewestverses). The dataset contains total of 364 verses from 243 songs. Each verses are seprated by an empty line which consist of "\n". This project is trained on characters based features. i.e. the embeding step is based on characters, not words.
This project is inspried by a NLP course on coursera in Tensorflow in practice specitialization offer by deeplearning.ai and [Tensorflow tutorial](https://www.tensorflow.org/tutorials/text/text_generation). The process is to prepare the lyrics and window them into segments the use the characters in these windows to predict the next character. Since each character is related to its previous and next character, RNN and LSTM that carry hidden state from previous cell are suitable for this application.   
