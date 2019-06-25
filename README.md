# Kaggle_kernels
All my Kaggle kernels (all made public jupyter notebooks in python) as a competition contributor


### Adult Census Income: [Kaggle](https://www.kaggle.com/obrunet/adult-census-income) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Adult%20Census%20Income/Adult%20Census%20Income.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Adult%20Census%20Income/Adult%20Census%20Income.pdf)
* Concept : model explanation - find clear insights on the profiles of the people that make more than USD 50K a year
* Type : standard supervised binary classification task (RandomForrest, Decision Tree, Extra Tree Clf) 
* Dataset : age, workclass, education, marital-status, occupation, race, sex, capital-gain/loss,hours-per-week, country.
* Goals :
  * Get use to usual classification models, cross validation & tuning hyperparameters with GridsearchCV. 
  * Features analysis
  
### Home Credit Default Risk: [Kaggle](https://www.kaggle.com/obrunet/home-credit-default-risk) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Home-Credit/Kaggle/Home_credit_default_risk.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Home-Credit/Kaggle/Home_credit_default_risk.pdf)
* Concept : predict whether or not an applicant will be able to repay a loan
* Type : advanced supervised binary classification task (RandomForrest, LightGBM, XGBoost models) using the area under the ROC curve as metric
* Dataset : previous credits, POS (point of sales), cash loans, previous applications and repayment history.
* Goals :
  * Deal with imbalanced dataset.
  * Make prediction when accuracy is not the best metric (ROC AUC is a better representation of model performance)
  * Features analysis and importances

### Customer Segmentation: [Kaggle](https://www.kaggle.com/obrunet/customer-segmentation-k-means-analysis) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Fraud%20Detection/Fraud-Detection.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Fraud%20Detection/Fraud-Detection.pdf)
* Concept : customer segmentation, also known as market basket analysis
* Type : unsupervised machine learning technique (KMeans Clustering Model)
* Dataset : customerID, gender, age, annual income (k$) &	spending score from a supermarket mall customers
* Goals :
  * How to achieve customer segmentation using KMeans Clustering.
  * Who are your target customers with whom you can start marketing strategy easy to converse.
  * How the marketing strategy works in real world

### Fraud Detection: [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer%20Segmentation%20-%20K-Means%20Analysis/k_means.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer%20Segmentation%20-%20K-Means%20Analysis/k_means.pdf)
* Concept : anomalie / fraud detection
* Type : advanced supervised binary classification task using Area Under the Precision-Recall Curve (AUPRC)
* Dataset : anonymized credit card transactions labeled as fraudulent or genuine, recorded over 2 days
* Goals :
  * Identify fraudulent credit card transactions, given the class highly imbalance ratio.
  * Using SMOTe the Synthetic Minority Over-sampling Technique
  * Testing the LOF model (LocalOutlierFactor)

