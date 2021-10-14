# Final Files Contents Explained

* data
    - Directory containing all data-related files. ‘Train.csv’ is the unprocessed data. ‘Df_final.csv’ is the preprocessed data. ‘Data_description.txt’ contains a description of all features in the dataset. 
* Lasso without RFE.ipynb
    - Jupyter notebook with Lasso model using full set of attributes
* Lasso.ipynb
    - Jupyter notebook with Lasso model using full set of attributes as well as a reduced feature set found by running RFE. We found that running the model with the reduced feature set did not improve the performance so it was dropped in the file “Lasso without RFE.ipynb”
* Linear Regression OLS.ipynb
    - Jupyter notebook with Linear Regression using OLS ran on the standardized data with the rmse and score reported. The notebook contains a grid search to find the optimal hyperparameters for the model as well with the optimised scores reported. 
* Polynomial Regression(deg=2).ipynb
    - Jupyter notebook with Polynomial Regression of degree 2 using a full set of attributes.
* Ridge.ipynb
    - Jupyter notebook with Ridge model using full set of attributes as well as a reduced feature set found by running RFE. 
* SGDRegressor_w_ResidualPlots.ipynb
    Jupyter notebook with SGDRegressor model using full set of attributes. Residual plots of both training and test set were provided as a sanity check.
* SVR.ipynb
    Jupyter notebook with Support Vector Regression (SVR) model
* Data_preprocess.ipynb
    - All code related to preprocessing the data and making it suitable for training.
* Data_visualization.ipynb
    - All graphs related to data visualization
