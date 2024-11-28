# AIDI1002-Final-Project

## Project Description
In this project we have implemented the methodologies used in "Stock Market Prediction Using Support Vector Regressor with Radial Basis Function Kernel" research paper and tryed to improve the results using different model and latest data. The paper showcases the use of Support Vector Regressor method on data from Indonesia Stock Exchange, we have replecated the code and added a new model Long short-term memory (LSTM) model on recent data because the data used in the research is from 2010 till 2021.

## Research Paper
<h3>Title: <a href= "https://dl.acm.org/doi/abs/10.1145/3512388.3512444">Stock Market Prediction Using Support Vector Regressor with Radial Basis Function Kernel</a></h3>
<h3>Orignial Code Link: <a href= "https://github.com/K6RTCS/Stock-Market-Prediction-RBF">Source Code</a></h3>
In this research paper they have performed Support Vector Regressor method on data from Indonesia Stock Exchange.

## Original Code Implimentation
In the original code they have sourced the data from yahoo finance using yahoo finance API, and they have used data from 2010 till 2021. They have tried to implement Support vector regression on the data by splitting the data into two sets one train set which includes data from 2010  to 2019 and the other test set includes data from 2020 to 2021.
### For the train set results were:
<ul>
    <li><b>Root Mean Square Error:</b>179.17</li>
    <li><b>R2:</b>1.0</li>
    <li><b>Mean Absolute Error:</b>1.48</li>
</ul>

### For the test set results were:
<ul>
    <li><b>Root Mean Square Error:</b>228.79</li>
    <li><b>R2:</b>0.99</li>
    <li><b>Mean Absolute Error:</b>13.80</li>
</ul>

## Updating and implementing different model
We have first tried to replicate the code and provide the same output, then we implemented the Long short-term memory (LSTM) model and we also updated the data till 2024, so in the new code we used data from 2015 till 2024. Also, we tried to implement the new code the same way as the research, we created two sets of data and implemented the LSTM model.