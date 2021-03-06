# UNIC-Internship-2021

This repo contains three coding files, including my first two simplified attempts at data analysis and Machine Learning, along with demonstrational graphics files, all of which are detailed below.


Coding File 1: drone_LinReg_VelocityXOrientationX.py      
Features a preliminary attempt at Linear Regression to determine whether a relationship or correlation exists between Wind Speed and Velocity-Y

    Image File 1: Velocity-X vs. Orientation-X Scatterplot.png
    Displays the data points where the x values represent the velocity-x and the y values represent the orientation-x in the form of a scatterplot
    
    Image File 2: Residuals of Velocity-X vs. Orientation-X Linear Regression.png
    Demonstrates the accuracy using a histogram showing the distribution of the residuals, where most residual values are around 0, showing the accuracy of the regression on these two variables

Coding File 2: drone_LinReg_WindSpeedVelocityY.py        
Features a preliminary attempt at Linear Regression to determine whether a relationship or correlation exists between Velocity-X and Orientation-X
    
    Image File 1: Wind Speed vs. Velocity-Y Scatterplot.png
    Displays the data points where the x values represent the wind speed and the y values represent the orientation-x in the form of a scatterplot
    
    Image File 2: Residuals of Wind Speed vs. Velocity-Y Linear Regression.png
    Demonstrates the accuracy using a histogram showing the distribution of the residuals, where most residual values are around 0, but some outliers are present in measurable numbers
    
Coding File 3: droneDataRegressionAnalysis.py           
Features a full data analysis using multiple regression algorithms to evaluate the relationship between Wind Speed and Velocity-Y, building off of Coding File 2

    Image File 1: Model Comparison for Regression Analysis.png
    Provides the Mean Absolute Error (MAE) for each of the regression algorithms, showing that the Random Forest Regressor has the lowest discrepancy between actual and predicted results
    
    Image File 2: Random Forest Regressor Predictions vs. Actual Data.png
    Shows the difference between the actual results, shown in orange, and the predicted results, shown in blue, using the most accurate Random Forest Regressor
    
    Image File 3: Residuals of Random Forest Regression.png
    Demonstrates the accuracy using a histogram showing the distribution of the residuals, where most residual values are around 0, with some outliers, but marked improvement over Image File 2 of Coding File 2
    

