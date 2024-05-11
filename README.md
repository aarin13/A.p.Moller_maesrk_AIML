# A.p.Moller_maesrk_AIML
Assesment code repo for AP Moller Maesrk

# Solution

When tackling the regression task with a dataset rich in categorical values, achieving highly accurate models can be challenging. However, employing encoding techniques like Label Encoder, along with tree-based methods such as Decision Trees (DT) or Random Forest Regression (RFR), proves beneficial. RFR, particularly, excels due to its ability to average over conditions of encoded categorical data, yielding a more generalized outcome over the training data trends.

Despite employing a feedforward neural network with two dense layers for regression, it didn't contribute significantly to improving accuracy.

In the given dataset, outliers and nonsensical negative cost values were present, which were excluded from training. Moreover, no significant correlation was observed between the features and the target variable, with some features contradicting the target variable's behavior.

Since the data wasn't in a time series format, autoencoders or recurrent models weren't applicable for predicting the next timestep occurrence.

The average absolute error for RFR and the neural network stood at 29.53 and 29.24, respectively.

Libraries used - PyTorch, Sklearn, Seaborn, Pandas, Numpy.



Added results.xlsx with predicted values
![image](https://github.com/aarin13/A.p.Moller_maesrk_AIML/assets/92866904/0801dcea-c9c2-430e-9c15-a4bc27152105)

