This dataset contains z^2 scores for all possible pairs of 4,924 subreddits (these subreddits had more than 500 comments made by more than 100 unique users in the month of June 2016).

Each file in the double_z folder coresponds to one subreddit and each line in a file is formatted as follows:
anchor_subreddit <tab> pair_subreddit <tab> z^2_score <tab> author_similarity_rank <tab> phrase_similarity_rank <tab> raw_author_similarity <tab> raw_phrase_similarity 

The graph (.gml) files contain author and term similarity networks where nodes are subreddits and edges are determined by author and term similarity respectively.
Each graph has the following node attributes:
id, name (subreddit name), modularity (community id determined by multilevel algorithm) and subcount (subscriber count of the subreddit as per June 2016).

If you make use of this dataset, please cite the following:
Srayan Datta, Chanda Phelan, and Eytan Adar. 2017. Identifying Misaligned Inter-Group Links and Communities. Proc. ACM Hum.-Comput. Interact. 1, 2, Article 37 (November 2017), 23 pages.
https://doi.org/10.1145/3134672  