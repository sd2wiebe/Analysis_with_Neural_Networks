# Neural_Network_Charity_Analysis

## Overview of Analysis

The purpose of this analysis is create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup, using info from a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

## Results 

### Data Preprocessing:

<li>The target variable for our model is "IS_SUCCESSFUL".</li>
<li>Feature variables include: status, ask amount, application type, income amount, organization etc.</li>
<li>We removed variables that were neither targets nor features, such as "EIN" and "NAME".</li>

### Compiling, Training, and Evaluating the Model:

<li>For my optimized model I used 5 hidden layers with 25 neurons on each</li>
<li>With each additional hidden layer and as I added more neurons the accuracy improved slightly</li>
<li>Target performance was 75%, unfortunately I was only able to reach ~74.27%</li>
<li> I experimented with removing features, changing bucket sizes, changing activation functions on hidden layers and adding epochs </li>

## Summary

My optimized model was able to accurately predict if companies would be successfull if funded by Alphabet Soup about 74% of the time, which isn't quite the target amount (75%). 
<p align="center"

![alttext](https://github.com/sd2wiebe/Neural_Network_Charity_Analysis/blob/main/accuracy.png)

</p>

I believe Random Forest would serve as a great alternative model to the deep learning model. This is because Random Forest works very similarly to neural network models, and is known to be a good binary classifier.
'

