# unsupervised-learning-challenge

This is a basic unsupervised learning model using cryptocurrency data.

## PREPROCESSING

I first drop all the coins not being traded, the coins that have any nulls, and the coins that haven't had any mining done. I also drop the coin name and coin ticker.

From there I convert the remaining non-numeric data into dummy variables and scale the data to standardize.

## DIMENSIONALITY

I use PCS to keep 90% of the explained variance and then use a t-SNE to further reduce the number of dimensions.

## MODEL

Finally I try to find clusters in my data using K-means. I find through inertia that either 3 or 5 clusters is the best and 5 clusters ended up being the best fitting after running the model.

## RECOMMENDATION

In the end I recommend that the coins can be clustered and that five clusters will cover most of the data.