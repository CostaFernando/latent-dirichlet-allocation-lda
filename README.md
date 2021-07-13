# Latent Dirichlet Allocation (LDA)
Topic modeling with Latent Dirichlet Allocation (LDA).

This project is part of Udacity's Natural Language Processing Nanodegree. In this project is done topic modeling using Latent Dirichlet Allocation (LDA).

The dataset is a list of over one million news headlines published over a period of 15 years. And the goal is to extract topics from the headlines (Unsupervised Machine Learning).

LDA is used to classify text in a document to a particular topic. It builds a topic per document model and words per topic model, modeled as Dirichlet distributions. 

* Each document is modeled as a multinomial distribution of topics and each topic is modeled as a multinomial distribution of words.
* LDA assumes that the every chunk of text we feed into it will contain words that are somehow related. Therefore choosing the right corpus of data is crucial. 
* It also assumes documents are produced from a mixture of topics. Those topics then generate words based on their probability distribution. 
