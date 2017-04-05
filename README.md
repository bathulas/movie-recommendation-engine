# movie-recommendation-engine

# Dataset: Movielens
# Environment: Apache Spark, Python, AWS EC2 m4.large 
# Movie recommendation engine built using Collaborative filtering with explicit feedback






# Collaborative filtering is commonly used for recommender systems. 
# These techniques aim to fill in the missing entries of a user-item association matrix. 
# spark.mllib currently supports model-based collaborative filtering, in which users and products are described by a small set of latent factors that can be used to predict missing entries. 
# spark.mllib uses the alternating least squares (ALS) algorithm to learn these latent factors. 
# The implementation in spark.mllib has the following parameters:

# numBlocks is the number of blocks used to parallelize computation.
# rank is the number of latent factors in the model.
# iterations is the number of iterations of ALS to run. 
# ALS typically converges to a reasonable solution in 20 iterations or less.
# lambda specifies the regularization parameter in ALS.
