# Chinese Word2Vec
This is an iPhython notebook implementation of Chinese Charactor Word2Vec skip-gram model

It provides an implementation of the skip-gram architectures for computing vector representations of Chinese charactors

Given a text corpus, it learns a vector for every word in the vocabulary using the Skip-Gram neural network architectures

Besides Chinese charactors level embedding, it can also support word or phrase based embedding and other languages

Tips: Use Python3 to avoid code page related issue

## About this model

I used the most frequent 3000 chinese charactors as the source for 128d embedding
 
trained a 400MB wikipedia Chinese corpus a got the following mapping graph

## Understand Word2Vec

Word2Vec is a way of representing words in vector form 
so that the distance among vectors makes the representation sematically meaningful

https://www.tensorflow.org/versions/r0.12/tutorials/word2vec/index.html

http://mccormickml.com/2016/04/27/word2vec-resources/

