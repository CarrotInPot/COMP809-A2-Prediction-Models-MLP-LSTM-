# COMP809-A2-Prediction-Models-MLP-LSTM

This repository contains the code and documentation for a project aimed at predicting PM2.5 (particulate matter) concentrations using Multi-Layer Perceptron (MLP) and Long Short-Term Memory (LSTM) models. This project is part of the Data Mining and Machine Learning course (COMP809) and was conducted by Samuel Meads and Leon Lee as an assignment due on June 9, 2024.

## Project Overview
Air pollution poses significant risks to public health, with PM2.5 being strongly correlated with cardiovascular diseases. Accurate predictions of PM2.5 concentrations are crucial for mitigating these health risks. This project involves building and comparing prediction models using MLP and LSTM techniques to forecast PM2.5 levels.

### Objectives
Conduct a literature review on data mining methods used in various application domains.
Develop and validate prediction models for PM2.5 using MLP and LSTM.
Evaluate model performance using metrics such as RMSE, MAE, and R².

### Repository Structure
Part_A_Research_Report.pdf: A literature survey on data mining methods in fraud analysis, including a review of peer-reviewed papers, thematic discussions, and proposed approaches.
Part_B_Report.pdf: The main report for the prediction models, including data preprocessing, model development, results, and discussion.
Part_B.ipynb: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.

### Data
The dataset used for this project includes PM2.5 and PM10 measurements, along with various predictors such as air pollution indices and meteorological data. The data was collected hourly from January 2019 to December 2023 from two air quality monitoring stations in Auckland (Penrose Station and Takapuna Station).

## Methodology
### Data Preprocessing
Identified and handled missing data and outliers.
Ensured all datasets had the same temporal resolution.
Selected the top five attributes with the highest correlation to PM2.5 using Pearson Correlation.
### Model Development
Multi-Layer Perceptron (MLP): Implemented using sklearn.neural_network.MLPRegressor with experiments to determine the optimal number of neurons and hidden layers.
Long Short-Term Memory (LSTM): Developed using a sequential model with adaptive moment estimation (ADAM) optimization, experimenting with epochs, batch sizes, and neuron numbers.
### Evaluation
Models were evaluated using Root Mean Square Error (RMSE), Mean Absolute Error (MAE), and R².
Comparison of actual vs. predicted PM2.5 concentrations to assess model performance.
### Results and Discussion
Detailed analysis of the performance of MLP and LSTM models.
Insights and observations on the effectiveness of each model.
Suggestions for future improvements and potential applications.

## Authors
Samuel Meads, Leon Lee.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

