In this notebook we import a classifier model from github and make predictions taking into account that the data must be scaled and an array must be built in order to be able to run the model as follows
new_pred = classifier_colab.predict(scaler_colab.transform(np.array([[[40,20000]])))) 
