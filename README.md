# Sales-Predictions
Predicting the Sales of Various Products
https://docs.google.com/presentation/d/1Y3OObHvC00maIxLe346m3X8wJ0pnCgEnWaVZmjjrIt0/edit?usp=sharing
This project outlines the relationship between various outlet items, outlet metrics and how it relates to prices
There are several visuals that help tell the story about the data including histograms depicting the distribution and a heatmap outlining the correlation between Item MSRP and the Sales.
In order to find a relationship of how the price is affected by all the other various metrics, I did two different models
The first model was a simple linear regression model and the results did not seem accurate with the massive difference between the training and testing set. The second model that I used worked significantly better and much more efficient
The second model was a decision tree model, and after running a few variation with varying depths, I discovered that the most accurate depth was 7. Using the decision tree model with a depth of 7 brought the R2 and the MSE values close together indicating that it was an efficient model. The diagrams on the right show the most efficient depth
I recommend using the decision tree model to evaluate the data because of the efficiency and effectiveness of the model.
