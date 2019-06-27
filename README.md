# Kaggle_kernels


#### Adult Census Income: [Kaggle](https://www.kaggle.com/obrunet/adult-census-income) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Adult%20Census%20Income/Adult%20Census%20Income.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Adult%20Census%20Income/Adult%20Census%20Income.pdf)
* Use case: predict whether income exceeds $50K/yr based on census, define people profiles
* Data: age, workclass, education, marital-status, occupation, race, sex, capital-gain/loss,hours-per-week, country.
* Concepts: supervised ML binary classification, __model explanation__ / feature analysis, __GridsearchCV__. 

#### Real Estate Price: [Kaggle]() - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Real-Estate-Price/California%20Housing%20Prices.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Real-Estate-Price/California%20Housing%20Prices.pdf)
* Use case: predict a real estate price
* Data: Median house prices for California districts derived from the 1990 census.
* Concepts: supervised ML regression, analysis of __geospatial data__ 
  
#### Home Credit Default Risk: [Kaggle](https://www.kaggle.com/obrunet/home-credit-default-risk) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Home-Credit/Kaggle/Home_credit_default_risk.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Home-Credit/Kaggle/Home_credit_default_risk.pdf)
* Use case: predict whether or not an applicant will be able to repay a loan
* Data: previous credits, POS (point of sales), cash loans, previous applications and repayment history
* Concepts: supervised ML binary classification (__LightGBM__, __XGBoost__), imbalanced classes, metric: __area under the ROC curve__

#### Bike Sharing Demand: [Kaggle](https://www.kaggle.com/obrunet/bike-sharing-demand) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Bike-Sharing/Kaggle/Bike_sharing.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Bike-Sharing/Kaggle/Bike_sharing.pdf)
* Use case: forecast use of a city bikeshare system
* Data: datetime, weather infos, rentals number
* Concepts: supervised ML regression (__GradientBoosting Reg, __Ridge/Lasso__), metric: __RMSLE__

#### Customer Segmentation: [Kaggle](https://www.kaggle.com/obrunet/customer-segmentation-k-means-analysis) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Fraud%20Detection/Fraud-Detection.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Fraud%20Detection/Fraud-Detection.pdf)
* Use case: customer segmentation, target customers with whom you can start marketing strategy
* Data: customerID, gender, age, annual income (k$) &	spending score from a supermarket mall customers
* Concepts: __unsupervised__ ML (__KMeans Clustering__)

#### Fraud Detection: [Kaggle](https://www.kaggle.com/obrunet/credit-card-fraud-detection) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer%20Segmentation%20-%20K-Means%20Analysis/k_means.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer%20Segmentation%20-%20K-Means%20Analysis/k_means.pdf)
* Use case: anomalie / fraud detection
* Data: anonymized credit card transactions labeled as fraudulent or genuine, recorded over 2 days
* Concepts: supervised ML binary classification, __classes highly imbalanced__, metric: __Area Under the Precision-Recall Curve__ (AUPRC), __PCA__, Synthetic Minority __Over-sampling__ Technique (SMOTe) & LOF model (LocalOutlierFactor)

#### Customer Churn: [Kaggle](https://www.kaggle.com/obrunet/customer-churn) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer-Churn/01-Customer-churn_completed.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer-Churn/Customer-churn.pdf)
* Use case: predict behavior to retain customers
* Data: the ones who left, services, account infos, contract, payment method, charges, demographic info
* Concepts: supervised ML binary classification, metric: __F1 score, hyperparameters tuning, pipelines__ of models
