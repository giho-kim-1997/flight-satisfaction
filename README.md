# flight-satisfaction
COGS 109 Project (https://docs.google.com/document/d/1lJk-qRjV2yMKCYa2hYiow5wGGLAf7swN_lh79TP3Tio/edit?usp=sharing)

Try to predict flight satisfaction for each customers.

First, we clean data with only the objective columns since the other columns are the subjective results from the customer survey.

With using columns,id,	Gender,	Customer, Type,	Age,	Type of Travel,	Class,	Flight Distance,	satisfaction, make logistic models.

Among the columns, we could figure out which column (predictor) can well-represent satisfaction (response) with using MSE approach.

After that, we use k-fold cross-validation to see which multivariate model is the best model to predict satisfaction.
