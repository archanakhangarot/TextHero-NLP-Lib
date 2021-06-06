Texthero makes use of multiple NLP and machine learning toolkits such as Gensim, NLTK, SpaCy and scikit-learn. You don't need to install them all separately, pip will take care of that.

Texthero include tools for:

Preprocess text data: it offers both out-of-the-box solutions but it's also flexible for custom-solutions.
Natural Language Processing: keyphrases and keywords extraction, and named entity recognition.
Text representation: TF-IDF, term frequency, and custom word-embeddings (wip)
Vector space analysis: clustering (K-means, Meanshift, DBSAN and Hierarchical), topic modelling (wip) and interpretation.
Text visualization: vector space visualization, place localization on maps (wip).
Supported representation algorithms:

Term frequency (count)
Term frequency-inverse document frequency (tfidf)
Supported clustering algorithms:

K-means (kmeans)
Density-Based Spatial Clustering of Applications with Noise (dbscan)
Meanshift (meanshift)
Supported dimensionality reduction algorithms:

Principal component analysis (pca)
t-distributed stochastic neighbor embedding (tsne)
Non-negative matrix factorization (nmf)
