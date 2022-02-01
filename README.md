# Blueskychallenge-tech-phantoms

BLUE SKY CHALLENGE - BLUE SKY BELOW
Forecasting Sensor Measurements in Smart Air Quality Monitoring System

The need to forecast air quality has increased significantly in the past few years. With the dataset provided to us, we have created CO level and Temperature predictions for the seven days with one week of data as a training dataset. The initial dataset has four parameters: Date, Time, CO, Temperature. A new dataset has been created with Date and Time merged as a single column, and the values of the dataset are analyzed as plots and bar graphs and help us arrive at the nature of the dataset. In training the dataset with regression models, we have used multiple linear regression, decision tree regression, and random forest regression, which helps to view the actual and predicted values. We arrive at the variance and MAPE scores for each regression model with these values. In addition, we calculated the R2 scores and MSE values to arrive at the most efficient model. We believe random forest regression has performed much better than other models from the values observed. We present all three models in the source file. The scope of improvement includes hyperparameter tuning of particular parameters and the use of a pre-trained model. The project is done in Google Colab python notebook, and the dataset provided is uploaded. 

Instructions:
Download the python notebook(in .ipynb format) and the dataset
Open the python notebook in Google Colab and upload the dataset
Run all the code snippets to reproduce the similar outputs 
