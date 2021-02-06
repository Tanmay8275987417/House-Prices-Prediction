# House Prices Prediction

Predicting the Sales price for for each house For each Id. Submissions are evaluated on Root-Mean-Squared-Error (RMSE)

The Train and Test data is preprocessed simultaneously by droping the unwanted features having null values more than 50%, While the features having null values less tha 50% is fill with there mean and mode respectively. This data is analysed graphically by using Heat Map.

The Categorical Variables are processed by using the OneHot-Encoding Technique and prepared the final Train and Test Data, The train-Test Data is Concanated to creat final_df data frame.

Now the Split up of final_df in df_Train and df_Test and Droping the Sale price feature from test data ML model is created.

By using the Xgboost Regressor, the ML model if fitted on Train dataset and predicted on test Dataset. 
