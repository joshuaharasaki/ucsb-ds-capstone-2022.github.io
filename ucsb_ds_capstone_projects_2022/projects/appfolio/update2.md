# Creating a Simple Model #

## A Concise Refresher ##

### About the Project ###

Our project aims to create a recommender system that recommends properties to users based on previous user interactions and property features. Our final goal is to integrate our model into the [Santa Barbara property website](https://realm-ucsb.herokuapp.com/) created by UC Santa Barbara’s AppFolio sponsored computer science capstone team.

### Where we left off ###

Our initial post gave a brief introduction of our project, the data we are working with, our obstacles, a brief overview of the model we were interested in using, and how we were working towards understanding the BiLateral Variational Autoencoder. 

Our main struggle with the data was working around the many null values in the item_features dataset. Since then, we have opted to focus on the ratings dataset for the simple model we created for the CS Capstone team, and plan to utilize the item_features dataset in future works.

In terms of the model, we have been able to understand the complexity of the Variational Autoencoder and were able to create a model trained on user interaction data with Santa Barbara County properties to provide to the CS capstone team. 

In the following sections, we will go more in depth on the model we are using, hyperparameter tuning, baseline models that we used to compare to our chosen model, metrics we are using to measure the performance of our model, and our future plans to improve our model. 

## Our Model ##

![](https://cdn.discordapp.com/attachments/927717200247275561/949420982580428820/unknown.png)

