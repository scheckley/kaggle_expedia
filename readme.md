# Kaggle Expedia Recommendations

My exploration of the Expedia Hotel Recommendations kaggle data set (https://www.kaggle.com/c/expedia-hotel-recommendations).

I am using this data set to explore vatious "big data" tools such as duckdb and dask.

Attempts at machine learning are not so successful. None of the features show strong correlation
with the target vector and attempts to use gradient boosting methods have only resulted in a model
with approx. 40% accuracy, and poor mean average precision at k=5. Without more data it may not be
possible to improve on this significantly. It is what it is.

### To do

* Perform more feature engineering and exploratory data analysis.
* Improve model performance.
