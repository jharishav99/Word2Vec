This repository contains a Python script that implements an algorithm to find the odd word in a list using word embeddings and cosine similarity. The concept leverages pre-trained word embeddings to determine which word in a given list is most dissimilar in meaning compared to the others.

How It Works
Word Embeddings: Utilizes a pre-trained Word2Vec model (though adaptable to other models like GloVe or FastText) to convert words into dense vector representations.

Cosine Similarity: Computes the cosine similarity between each word in the list and the average vector obtained from all word embeddings in the list. A lower cosine similarity indicates greater dissimilarity in context.

Identifying the Odd Word: The word with the lowest cosine similarity to the average vector is identified as the odd word in the list.
