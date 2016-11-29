# Chinese Word2Vec
This is an iPhython notebook implementation of Chinese Charactor Word2Vec skip-gram model

It provides an implementation of the skip-gram architectures for computing vector representations of Chinese charactors

Given a text corpus, it learns a vector for every word in the vocabulary using the Skip-Gram neural network architectures

Besides Chinese charactors level embedding, it can also support word or phrase based embedding and other languages

## About this model

I used the most frequent 3000 chinese charactors as the source for 128d embedding
 
trained a 400MB wikipedia Chinese corpus got the following mapping graph

![DEMO](/demo/embedding128%20window4%20iteration5000001.png?raw=true)

## Tips

- Use Python3 to avoid code page related issue

- Here is how I solved the problem displaying Chinese Charactors in matplotlib http://blog.sciencenet.cn/blog-43412-343002.html

## Understanding Word2Vec

Here are some useful links for understanding Word2Vec if you are new here

https://www.tensorflow.org/versions/r0.12/tutorials/word2vec/index.html

Word2Vec is a way of representing words in vector form 
so that the distance among vectors makes the representation sematically meaningful

http://mccormickml.com/2016/04/27/word2vec-resources/
