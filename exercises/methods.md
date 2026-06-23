# Exercise

## Methods

We collected information about 50,000 customers from an online retailer. Each customer was described using 100 variables including purchase history, browsing behaviour, website activity, and demographic information.

To reduce noise, customers with fewer than five purchases were excluded from the analysis. Missing values were imputed using the population average.

To identify groups of similar customers, we first standardised all variables so that they had comparable scales. We then reduced the data to 10 dimensions using principal components analysis. Similarity between customers was measured using Euclidean distance. 

Finally, customers were assigned to clusters using a $k$-means clustering algorithm (with $k=5$).

The resulting clusters were interpreted as distinct customer types and used to guide marketing strategy.
