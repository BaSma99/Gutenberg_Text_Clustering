Gutenberg Text Clustering.
1- Preparing the data from Gutenberg Books.

2- Data pre-processing.

3- perform data transformation:

           1- BOW
      
           2- TF-IDF
           
           3- LDA
           
           4-Word2Vec
      
4- Building the clustering algorithms: 

      1- K-means clustering algorithm.

      2- Expectation Maximization(EM) algorithm.
      
      3- Hierarchical clustering algorithm.
      
5- Perform Evaluation:

      1- Perform Kappa Evaluation against the true authors.
      
      2- Perform consistency with the V-Score Evaluation against the true authors.
      
      3- Perform Coherence Evaluation against the true authors.
      
 6- Error analysis:
     
    1- Print the silhouette scores.
    
    2- Create analysis data frame for the true label and predicted label.
    
    3- count the number of matches between most frequent words in clusters and true labels.
    
    4- Create a disctionary of matches labels and matches weights.
    
    5- Find the Most common words with their repeat count in all records that were labelled uncorrectly according to the human label.
