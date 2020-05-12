# Telco-Customer-Churn-Prediction
Several models used to predict the customer churn of a Telco Company. Second personal project of the Metis Data Science bootcamp. 

The main files in this repo include:

1) telco_EDA_FEATS.ipynb <br>
This is the notebook I used to perform some exploratory data analysis and feature engineering. The engineering included creating categorical bins out of some of the continuous variables like 'total charges' and 'number of products owned'. I also created deviation features to capture values relative to members of a category it belongs to.

2) TELCO_CHURN_MODELS.ipynb<br>
This huge notebook contains all of the modeling for various classification algorithms from baseline to fully tuned. If you want to skip over all of the baselining and tunning, there is a 'Final Models' sections towards the end of the notebook that contains the best models including a tuned XGboost model that had the best performance. I apologize if the notebook seems messy or redundant with a lot of re-used code. There are many things I would do differently now to write this in a cleaner way although the models did end up being rather predictive.

3) Telco Churn Presentation.pdf<br>
The slides I presented to my peers at Metis.

4) Telco_churn_original.csv<br>
The original dataset from Kaggle.
