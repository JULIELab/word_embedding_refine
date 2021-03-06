# Refining Word Embeddings for Sentiment Analysis
The code for paper "Refining Word Embeddings for Sentiment Analysis"

## Abstract
Word embeddings that can capture semantic
and syntactic information from contexts
have been extensively used for various
natural language processing tasks. However,
existing methods for learning contextbased
word embeddings typically fail to
capture sufficient sentiment information.
This may result in words with similar vector
representations having an opposite sentiment
polarity (e.g., good and bad), thus
degrading sentiment analysis performance.
Therefore, this study proposes a word vector
refinement model that can be applied to
any pre-trained word vectors (e.g.,
Word2vec and GloVe). The refinement
model is based on adjusting the vector representations
of words such that they can be
closer to both semantically and sentimentally
similar words and further away from
sentimentally dissimilar words. Experimental
results show that the proposed
method can improve conventional word
embeddings and outperform previously
proposed sentiment embeddings for both
binary and fine-grained classification on
Stanford Sentiment Treebank (SST).

## Parameters
|Parameter|Are|
|:---|:---|
|--filename|pre-trained word embeddings file|
|--lexicon|lexicon which provide sentiment intensity|
|--top|top-k nearest neighbor|
|--iter|refinement interation|
|--beta|parameter beta|
|--gamma|parameter gamma|
|--valence|max value of valence|