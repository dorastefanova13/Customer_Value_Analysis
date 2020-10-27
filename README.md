I created this project to practice data exploration, visualization, and modeling with Python.

The analysis is following the methodology in the example by Barış Karaman (https://towardsdatascience.com/data-driven-growth-with-python-part-1-know-your-metrics-812781e66a5b)

The first part is mostly data exploration and visualization for an Online Retailer data set. Couple of new measures are created, such as monthly active customers, montly sales, new customer ratio. This part ends with generating summary retention table I am creating couple of new variables and at the end a summary retention table with monthly cohorts. 
https://nbviewer.jupyter.org/github/dorastefanova13/Customer_Value_Analysis/blob/main/01_Metrics_Exploration.ipynb

The second part of the analysis covers the customer segmentation topic. It begins with defining the optimal number of clusters for Recency, Frequency, and Revenue. Finally,  the RFM score and cluster is calsulated for each customer.
https://nbviewer.jupyter.org/github/dorastefanova13/Customer_Value_Analysis/blob/main/02_Customer_Segmentation.ipynb

The next part of the analysis deals with predicting the customer value. The model is using 3 months of revenue data for predicting the revenue for the next 6 months. The XGBoost is used for building the model.
https://nbviewer.jupyter.org/github/dorastefanova13/Customer_Value_Analysis/blob/main/03_Customer_LTV_Prediction_Model.ipynb

The last part of the analysis deals with predicting churn. Two different models are built (GLM and XGBoost) and evaluated.
https://nbviewer.jupyter.org/github/dorastefanova13/Customer_Value_Analysis/blob/main/04_Churn_Analysis.ipynb

