# Crop Prediction (Data Science)
This project aims to analyze and provide insights into agriculture production using data science techniques. The dataset used for this project is obtained from the Agriculture Production dataset.

## Dataset Overview
The dataset contains information about various agricultural features and the corresponding crop labels. It includes the following features:

N: Ratio of Nitrogen content in the soil
P: Ratio of Phosphorus content in the soil
K: Ratio of Potassium content in the soil
temperature: Temperature in degrees Celsius
humidity: Relative humidity in percentage
ph: pH value of the soil
rainfall: Rainfall in mm
The shape of the dataset is (N, 8), where N=2200 represents the number of data points. The dataset does not contain any missing values.

## Exploratory Data Analysis
The mean values for each feature are as follows:
Mean of N: 50.55
Mean of P: 53.36
Mean of K: 48.15
Mean of temperature: 25.62
Mean of humidity: 71.48
Mean of ph: 6.47
Mean of rainfall: 103.46

## Crop Summary
Interactively, you can select a crop label to view its summary statistics. The summary includes the minimum, average, and maximum values required for each feature by the selected crop.

## Feature Comparison
Interactively, you can select a feature to compare the average values across different crop labels. The output displays the average value for each crop label for the selected feature.

## Feature Distribution
The distribution of each feature is visualized using subplots. Each subplot represents the distribution plot for a specific feature.

## Cluster Analysis
The optimum number of clusters is determined using the Elbow method. The dataset is then clustered into four clusters using the K-means algorithm. The crops belonging to each cluster are displayed.

## Visualizations:

The barplot is shown below:
![BarPlot](https://github.com/waleedahmed0001/Crop_Prediction/blob/main/Visualizations/Barplot.PNG)


The Average of Features is shown below:
<div align="center">
  <img src="https://github.com/waleedahmed0001/Crop_Prediction/blob/main/Visualizations/Average.PNG" alt="Features Mean">
</div>




The Dsitplots of Features are shown below:
![Average](https://github.com/waleedahmed0001/Crop_Prediction/blob/main/Visualizations/Distplots.PNG)



## Model Training and Evaluation
The dataset is split into training and testing sets using an 80:20 ratio. Logistic Regression is applied to train the model, and predictions are made on the test set. The performance of the model is evaluated using various metrics, including accuracy, precision, recall, F1-score, and the confusion matrix. The classification report provides detailed metrics for each class.

The confusion matrix is shown below:

<div align="center">
  <img src="https://github.com/waleedahmed0001/Crop_Prediction/blob/main/Visualizations/Confusion_Matrix.PNG" alt="Confusion Matrix">
</div>


## Crop Prediction
A sample prediction is made using the trained model based on provided climatic conditions. The suggested crop for the given climatic conditions is displayed.

## Conclusion
In this project, we have analyzed the Agriculture Production dataset using various data science techniques. The insights gained from the analysis can help farmers and agricultural stakeholders make informed decisions about crop selection and farming practices based on different climatic conditions and soil characteristics. The trained model can be utilized for crop prediction and recommendation purposes.

The code and the report are available on GitHub for reference and further exploration.
