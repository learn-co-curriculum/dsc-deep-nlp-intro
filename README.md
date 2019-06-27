
# Deep NLP with Word Embeddings - Introduction

## Introduction

In this section you'll strengthen your deep learning and natural language processing skills by learning about word embeddings! Word embeddings are a unique coding schema for text corpa that preserve many underlying features, allowing for interesting geometric relations in this hyperspace. Specifically, you'll look at how similarity metrics can represent how two words relate to each other, and these transformations can be applied to multiple word pairs. For example, a similarity metric could encapsulate analogies like "man is to woman as king is to ____". 

## Objectives
You will be able to:
* Explain some high level concepts regarding word embeddings


### Word Embeddings

In this section, you'll learn about the concept of Word Embeddings, and how you can use them to model the semantic meanings of words in a high-dimensional embedding space! Word embeddings use similarity metrics to represent how two words relate to each other. This way, we can understand the words in our corpus to a bigger extent. A typical example is the example of "Man" vs "woman" and "king" vs "queen": word embeddings can capture that the word "man" relates to the word "woman" the same way the word "king" relates to "queen"!


### Using Word2Vec

Creating word embeddings is not an easy task. Word Embeddings can be created using so-called "Word2Vec" models that are  given enough training data. At its core, Word2Vec is just another Deep Neural Network, that looks at sequences of words and words that are often used in similar contexts (or *close* to each other in sentences). In this section you'll learn how to train a Word2Vec model, and you'll explore the Embedding Space.


### Classification with Word Embeddings

To wrap up this section, we'll focus on the practical aspects of how Word2Vec and Word Embeddings can be used to improve our Text Classification models. We'll start by learning how Transfer Learning can be used by loading pre-trained word vectors into our Word2Vec model. Then, we'll learn about how we can get the word vectors we need and combine them into Mean Word Vectors, and how we can streamline this process by writing our own vectorizer class that is compatible with scikit-learn pipelines. Next, we'll see how Deep Neural Networks with their own Embedding Layers can be trained, and how Keras preprocesses the text data to make everything run smoothly!


## Summary

In this section, you'll dive deeper into NLP and get better classification results using Word Embeddings!
