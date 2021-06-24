# Neural_architecture_search_with_genetic_algorithm

I read a book about Evolutionary Algorithm and got introduced to many interesing algorithms. I took interest to Genetic Algorithm and think about the idea that it an be used as Neural Architecture Search(NAS) for Neural Network. Not only to find the best hyperparameter/configuration for the model, but it might can select the best configuration for the variables too.

The data that I use contains river discharge, rain partitipation and the temperature of Durham River in England.
You can access the data from https://data.gov.uk/


This is the result I got from using Genetic Algorithm for NAS. Not only using Genetic Algorithm to find the best hyperparameters but also take count to the variables too. In this case it also go through to check the lags of every past values.
