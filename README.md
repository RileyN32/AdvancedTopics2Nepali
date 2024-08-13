# Advanced Topics in Computational Text and Media Sciences #2
This repository contains the code and files for my AdvancedTopics#2 term paper.

-The folder NoAugmentation contains the Jupyter Notebooks used to train the model on 1x the original train set and 6x the original dataset.
-The folder WithAugmentation contains the Jupyter Notebook used to train the model on the augmented train set, which consisted of 1x the original train set plus 5 augmented train sets of the same size. 
-The folder SynonymReplacement contains the Jupyter Notebook used to perform data augmentation on the original train set and create the augmented train set (which is 6x the size of the original train set). 

The original Nepali train and test sets were taken from: https://huggingface.co/datasets/Shushant/NepaliSentiment/tree/main

The Nepali word2vec embeddings used to perform synonym replacement were downloaded from: https://ieee-dataport.org/open-access/300-dimensional-word-embeddings-nepali-language

The Nepali word2vec model is documented here: https://github.com/rabindralamsal/Word2Vec-Embeddings-for-Nepali-Language/blob/master/README.md
