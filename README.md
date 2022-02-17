# Principle Component Analysis Using Numpy Pandas
 
In this project, I have implemented Principle Component Analysis on Iris data to show dimensionality reduction using Numpy and Pandas

# Data

I have used the Iris dataset which has 5 columns and 150 rows

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)
- Class {Iris-Setosa, Iris-Versicolor, Iris-Verginica}

# Goal

To show the logic/math behind PCA using python libraries like Numpy and Pandas such that the cumulative principle component explains over 95% of the variance in our data.
<br/><br/>
**Threshold : 95%**
<br/>
<br/>
# Results
**Data Before PCA** <br/>
<br/>
![Image1](https://github.com/Aishwarya4823/Principle-Component-Analysis-Using-Numpy-Pandas/blob/master/Images/Before.PNG)
<br/>
**Data After PCA** <br/>
<br/>
![Image1](https://github.com/Aishwarya4823/Principle-Component-Analysis-Using-Numpy-Pandas/blob/master/Images/After.PNG)
<br/>
<br/>
We can clearly see that the lower dimensional representation of the data after performing PCA has clear boundaries and explains over 95% of the variance in our model. 
<br/>
<br/>
# Insight 

<br/><br/>
We can always use our original data as a baseline model of our classification algorithm, and PCA modified data as input to the classification model that performs better than the baseline model.
