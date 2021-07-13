# siamese-faces
Using Siamese NN (2 conv layers + flatten + dense) for small faces database (40 persons) from here https://www.kaggle.com/kasikrit/att-database-of-faces/code.

Constrative loss.

Be carefull when compute accuracy: labels(0 - same person, 1 - different), preds (euclidian distance between features after NN)
