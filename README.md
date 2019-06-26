# Kaggle_kernels


#### Adult Census Income: [Kaggle](https://www.kaggle.com/obrunet/adult-census-income) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Adult%20Census%20Income/Adult%20Census%20Income.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Adult%20Census%20Income/Adult%20Census%20Income.pdf)
* Use case: predict whether income exceeds $50K/yr based on census, define people profiles
* Data: age, workclass, education, marital-status, occupation, race, sex, capital-gain/loss,hours-per-week, country.
* Concepts: supervised binary classification, model explanation / feature analysis, GridsearchCV. 
  
#### Home Credit Default Risk: [Kaggle](https://www.kaggle.com/obrunet/home-credit-default-risk) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Home-Credit/Kaggle/Home_credit_default_risk.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Home-Credit/Kaggle/Home_credit_default_risk.pdf)
* Use case: predict whether or not an applicant will be able to repay a loan
* Data: previous credits, POS (point of sales), cash loans, previous applications and repayment history
* Concepts: supervised binary classification (LightGBM, XGBoost), imbalanced classes, metric: area under the ROC curve

#### Bike Sharing Demand: [Kaggle](https://www.kaggle.com/obrunet/bike-sharing-demand) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Bike-Sharing/Kaggle/Bike_sharing.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Bike-Sharing/Kaggle/Bike_sharing.pdf)
* Use case: forecast use of a city bikeshare system
* Data: datetime, weather infos, rentals number
* Concepts: supervised regression (GradientBoosting Reg, Ridge/Lasso), metric: RMSLE

#### Customer Segmentation: [Kaggle](https://www.kaggle.com/obrunet/customer-segmentation-k-means-analysis) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Fraud%20Detection/Fraud-Detection.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Fraud%20Detection/Fraud-Detection.pdf)
* Use case: customer segmentation, target customers with whom you can start marketing strategy
* Data: customerID, gender, age, annual income (k$) &	spending score from a supermarket mall customers
* Concepts: unsupervised machine learning (KMeans Clustering)

#### Fraud Detection: [Kaggle](https://www.kaggle.com/obrunet/credit-card-fraud-detection) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer%20Segmentation%20-%20K-Means%20Analysis/k_means.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer%20Segmentation%20-%20K-Means%20Analysis/k_means.pdf)
* Use case: anomalie / fraud detection
* Data: anonymized credit card transactions labeled as fraudulent or genuine, recorded over 2 days
* Concepts: supervised binary classification, classes highly imbalanced, metric: Area Under the Precision-Recall Curve (AUPRC), PCA, Synthetic Minority Over-sampling Technique (SMOTe) & LOF model (LocalOutlierFactor)

#### Customer Churn: [Kaggle](https://www.kaggle.com/obrunet/customer-churn) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer-Churn/01-Customer-churn_completed.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer-Churn/Customer-churn.pdf)
* Use case: predict behavior to retain customers
* Data: the ones who left, services, account infos, contract, payment method, charges, demographic info
* Concepts: supervised binary classification, metric: F1 score, hyperparameters tuning, pipelines of models
