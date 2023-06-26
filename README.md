# "Exploring Neuron Morphology: Data Analysis and Predictive Modeling"
 
## Aim
The project aimed to explore the relationships between various morphological measurements, identify differences between neuron groups, and develop predictive models for the total surface area of neurons.

## Project Structure

The project is organized into several sections:

1. **Data Exploration**: The dataset consists of multiple CSV files containing measurements for different neuron groups. The analysis begins by loading and inspecting the data, identifying missing values, and summarizing the dataset dimensions.

2. **Statistical Analysis**: Statistical tests, such as t-tests, are performed to compare properties between neuron groups. The results are presented with t-scores and p-values, leading to conclusions about significant differences.

3. **Correlation Analysis**: The Pearson correlation coefficient is computed to assess the relationships between morphological features. The analysis identifies strongly correlated pairs and highlights influential factors affecting neuron morphology.

4. **Linear Regression**: Linear regression models are developed to predict the total surface area of neurons. Feature selection techniques, including forward selection using Akaike Information Criterion (AIC) and Bayes Information Criterion (BIC), are employed to refine the models.

5. **Random Forest Regression**: Random forest regression models are trained to predict the total surface area of neurons. Variable importance is analyzed to identify the most influential predictors. The model's performance is evaluated using different numbers of trees and compared to the linear regression models.

6. **Clustering Analysis**: K-means clustering is applied to identify distinct neuron types based on morphological measurements. The optimal number of clusters is determined, and discriminatory variables are explored. Scatter plots are created to visualize the clusters.

## Findings

The analysis reveals several key findings:

- The distribution of morphological measurements shows varying characteristics, with right-skewness and exponential-like distributions observed for certain variables.
- There are no significant differences in neuron properties between Group 1 and Group 2.
- Linear regression models provide strong predictive power for the total surface area of neurons, with certain variables showing higher significance.
- Random forest regression identifies total volume as the most important predictor, followed by the number of nodes, number of tips, total length, and number of branches.
- The random forest model performs well overall, with a good fit to the data and accurate predictions for the test set.
- The optimal number of trees for the random forest model lies between 100 and 200, as additional trees do not substantially reduce the mean square error.


## Conclusion

This project provides valuable insights into neuron morphology and its relationship with various measurements. The findings contribute to our understanding of neuronal properties and their potential implications in neuroscience research and medical applications.

Please note that the results and interpretations presented here are based on the specific dataset used. Further analysis and validation may be required for different datasets or research objectives.

