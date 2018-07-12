## Recommender System with Python and SQLite ##


Recommender systems have become a very important part of the online shopping experience. Given the number of possible choices available, it is hard to decide where to start combing through the online catalog. That is the beauty of recommender systems. It provides extra guidance and helps alleviate decison fatigue.

Recommendations are precomputed beforehand and stored in the database. This enables control of the frequency of updating the recommendations. Additionally, user and item recommendation are calculated using implicit library. Collaborative filtering suffers from cold start problem where users without purchase history cannot get personal recommendation. This can be addressed by showing similar items and most popular items.

The dataset is from UCI Machine Learning Repository, containing all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. Many customers of the company are wholesalers.

Citation:
Daqing Chen, Sai Liang Sain, and Kun Guo, Data mining for the online retail industry: A case study of RFM model-based customer segmentation using data mining, Journal of Database Marketing and Customer Strategy Management, Vol. 19, No. 3, pp. 197â€“208, 2012 (Published online before print: 27 August 2012. doi: 10.1057/dbm.2012.17).

Techniques used:
Collaborative filtering for implicit data, alternating least squares


