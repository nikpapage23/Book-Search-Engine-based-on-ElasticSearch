# Book-Search-Engine-based-on-ElasticSearch

A university project created for the lesson ***"Information Retrieval"*** with my colleague [Nikos Stamopoulos](https://github.com/nikosstam4)

######################################################################################
          ___           _     ___                  _      ___           _          
  ___ ___| _ ) ___  ___| |__ / __| ___ __ _ _ _ __| |_   | __|_ _  __ _(_)_ _  ___ ©
 / -_)___| _ \/ _ \/ _ \ / / \__ \/ -_) _` | '_/ _| ' \  | _|| ' \/ _` | | ' \/ -_)
 \___|   |___/\___/\___/_\_\ |___/\___\__,_|_| \__|_||_| |___|_||_\__, |_|_||_\___|
                                                                  |___/            

                          __...--~~~~~-._   _.-~~~~~--...__
                        //               `V'               \\ 
                       //                 |                 \\ 
                      //__...--~~~~~~-._  |  _.-~~~~~~--...__\\ 
                     //__.....----~~~~._\ | /_.~~~~----.....__\\
                    ====================\\|//====================
                                        `---`
######################################################################################

#### 1. Book results based on BM25 ranking
Reading the "BX-Books" dataset and uploading the data to ElasticSearch. Then, given a book lemma, run a query in the index, where we uploaded the data, and then return the book results in descending order based on the BM25 similarity ranking, provided by ElasticSearch.

#### 2. Book results based on personalized ranking
We combine the BM25 ranking, the personal score of the user and the average users' score to create our own personalized ranking for the book results. Return the results in descending order based on this ranking.

#### 3. Using Neural Network to predict users' scores
Tring to improve the quality of sorting by predicting a user's personal score for each book of the book results.

#### 4. k-meand clustering of books
Performing k-means clustering of the books based on cosine similarity. Then, trying to extract demographic correlations between the clusters.
