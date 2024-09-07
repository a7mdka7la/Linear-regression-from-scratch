# Linear-regression-from-scratch
The actual steps of the prediction part:
1- Defined a linear equation of one variable (e.g. y = 2x+3)
2- Selected 5 different values for x (x1,x2,...,x5) and calculated the corresponding y values 
3- Used x and y values as training data, and applied mean standardized square error technique to obtain the equation of the line that best fit the training data (compared to my defined equation)
4- Repeated 1,2 and 3 after adding random noise term to the equation

The actual steps of the classification part:
1- Using the IRIS dataset, I grouped samples of class 2 and class 3 to form a new class
2- Splitted class I samples into 40 samples for train and 10 samples for test
3- Splitted class II samples into 80 samples for train and 20 samples for test
4 Trained the classification model using least squares technique, positive for class I and negative for others, this model is suitable to classify the input sample as class I or "other classes"
