
<h1>Word Embeddings Indicate Historical Growth in Moral Concern for People, Animals, and the Environment</h1>

<h2>Stefan Leach, Andrew P. Kitchin, and Robbie M. Sutton</h2>

In this repository we will demonstrate how to use the contempary word embedding models supported by the Gensim library and the historical word embedding models supported by the Histwords library to generate the data used in [link to paper]. 

See https://github.com/RaRe-Technologies/gensim-data for a list of models and documentation for Gensim.
Histwords github repository found here: https://github.com/williamleif/histwords 
All English (1800s-1990s) pretrained models found here: https://nlp.stanford.edu/projects/histwords/.

We present our code in three jupiter notebooks:

<h2>contempary_models_average_vectors.ipynb</h2>
We calculate the cosine between each focal enitity and the average vector of the moarl words in the contempary models.

<h2>historical_models_average_vectors.ipynb</h2>
We calculate the cosine between each focal enitity and the average vector of the moarl words in the historical models. To use this notebook you will need to clone the Histwords github repository found here: https://github.com/williamleif/histwords as well as download the All English (1800s-1990s) pretrained models found here: https://nlp.stanford.edu/projects/histwords/.

<h2>historical_models_word_counts.ipynb</h2>
We calculate the word counts of each of our focal enitites and control entities in the historical models. To use this notebook you will need to clone the Histwords github repository found here: https://github.com/williamleif/histwords as well as download the All English (1800s-1990s) pretrained models found here: https://nlp.stanford.edu/projects/histwords/.
