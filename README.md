# GridsearchCV: Cracking open the black box

In this demonstration I show how to make decisions with the data provided by a grid search.  
This can be done by putting the cv_results_ option from the grid search into a pandas dataframe. That then allows us to manipulate the results to make decisions about which hyper-parameters we should use in our modeling.  
For example, at times the best params from gridsearch will have a wide difference between the mean train and mean test scores, when we would generally want results that are closer together in order to reduce over-fitting.  
We can also make columns in the dataframe for the difference, weighted difference and more.  
I am looking forward to seeing all the ideas people bring up so we can all benefit from them with our continuing search for the best hyper-parameters of our models.  

The data for this project comes from here:  
[https://www.openml.org/d/41893](https://www.openml.org/d/41893)  
