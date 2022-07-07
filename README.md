# Book-Search-Engine-based-on-ElasticSearch

A university project created for the lesson ***"Information Retrieval"*** with my colleague [Nikos Stamopoulos](https://github.com/nikosstam4).

<img src="https://github.com/nikpapage23/Book-Search-Engine-based-on-ElasticSearch/blob/main/logo.jpg">

## 1. Book results based on BM25 ranking
Reading the "BX-Books" dataset and uploading the data to ElasticSearch. Then, given a book lemma, run a query in the index, where we uploaded the data, and then return the book results in descending order based on the BM25 similarity ranking, provided by ElasticSearch.

## 2. Book results based on personalized ranking
We combine the BM25 ranking, the personal score of the user and the average users' score to create our own personalized ranking for the book results. Return the results in descending order based on this ranking.

## 3. Using Neural Network to predict users' scores
Trying to improve the quality of sorting by predicting a user's personal score for each book of the book results.

## 4. k-means clustering of books
Performing k-means clustering of the books based on cosine similarity. Then, trying to extract demographic correlations between the clusters.

### Datasets used:
- BX-Books.csv
- BX-Book-Ratings.csv
- BX-Users.csv

*They can be found and downloaded [here](http://www2.informatik.uni-freiburg.de/~cziegler/BX/).*
