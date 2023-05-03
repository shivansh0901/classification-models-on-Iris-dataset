# classification-models-on-Iris-dataset

DATA PRE-PROCESSING:

We can directly load the data using pandas into google colab notebook or we could use scikit to import data as well.
Further, the data is split into training and testting sets in a desired ratio. Generally the most common ratio is of 80:20, i.e. 80% for training and 20% for testing.
Next, we apply feature scaling in our data to standardise it using StandardScaler from sklearn library.
Moreover, after this the implementation changes in both the models, we can apply logistic regression on first notebook and for ANN we can go ahead by normalisation and then apply the concepts of implementing ANNs.


PERFORMANCE METRICS:

It is generally observed that ANN work well on more complex models with non linear relationship between dependent variabls, whereas logistic regressions are better when seen in the simpler models. 
In the case of implementation of both classification models on the Iris dataset, we see that both the models perform well and give an accuracy ~= 97%.

The performance metrics of both the models have also been included in the colab notebook as well.

The logistic regression notebook has a confusion matrix plotted to analyse the performance whereas in the ANN model notebook, i have plotted the graphs of - 
MODEL LOSS and MODEL ACCURACY.
