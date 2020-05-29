# Gradient_descent_ML
This is a linear regression Machine Learning model which I have created with Coursera' s guided project. This is based on the "chirps dataset" which has 'X' variable as number of chirps by a cricket and 'Y' as the temperature.

In this example we're using the count of chirps per minute as the independent variable to then predict the dependent variable, temperature. In short, we're using a little data science to make ourselves a cricket thermometer.

This relationship is assumed to be linear and thus we use Gradient Descent Algorithm to reduce the loss function.
I have given the code for python's function which directly does this job and an equivalent hand-written code for the same.

The code I have written imports a class from linreg.py file which is included in this repository.

CONCLUSION:
At the end of the day, when you create a model, you use training data. Then you start feeding test data (real observations) to see how well the model actually works. You may find that the model is a little inaccurate over time, in which case you retrain the model with some new data. Retraining the model means you're creating a new fit line that's used for predictions.

This regression can be used to examine the variability of the relationship between temperature and chirp count. Of course, if the model proves too inaccurate (that is, the predictions aren't very good), then it suggests that we might need to introduce more independent variables like humidity, time of year, latitude, amount of moonlight, and so on. If you have such data, you can do separate lines regressions for each independent variable, and then do multiple regressions with combinations of independent variables.

Again, once you are working with more than one or two independent variables, it's much easier to use machine learning to crunch the numbers than to try to visualize it graphically.
