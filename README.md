# Kaggle_kernels

Here are all the challenges i've made so far. I've started several weeks ago, but now i clean and make those kernels public. Side note: some of my solutions require write permission on the hard drive, so very few kernel could have been released on Kaggle (because write permissions aren't allowed)... 

---


## COMPUTER VISION

#### Fashion MNIST: [Kaggle](https://www.kaggle.com/obrunet/fashion-mnist) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Fashion%20MNIST/Kaggle/fashion_mnist.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Fashion%20MNIST/Kaggle/fashion_mnist.pdf)
* Use case: use a neural network on a classification task of clothes' images
* Data: 28x28 grayscale images associated with a label from 10 classes
* Concepts: __Multi Layers Perceptron__ with Tensorflow . 

#### Image classification: [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Dogs-vs-Cats/Kaggle/dogs_vs_cats.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Dogs-vs-Cats/Kaggle/dogs_vs_cats.pdf)
* Use case: Distinguish images of dogs from cats
* Data: binary classification of images in color, 25,000 labeled and 12,500 unlabeled for the submission purpose
* Concepts: deep learning / __computer vision__ using __CNN__ with __Tensorflow__ 

#### Handwritten Digit Generation: [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Digit_generator/kaggle/Digit-Generator.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Digit_generator/kaggle/Digit-Generator.pdf)
* Use case: generation of new digits
* Data: the famous MNIST data intended to learn computer vision fundamentals
* Concepts: unsupervised deep learning with __G.A.N__ - training of a __Generator__ and a __Discriminator__

## N.L.P

#### Quora Insincere Questions Classification - PART 1/2 : [Kaggle](https://www.kaggle.com/obrunet/quora-insincere-questions-classification) - [Notebook](https://github.com/obrunet/Kaggle_kernels_2019/blob/master/Quora%20Insincere%20Questions/Kaggle/Quora%20Insincere%20Questions.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels_2019/blob/master/Quora%20Insincere%20Questions/Kaggle/Quora%20Insincere%20Questions.pdf)
* Use case: Predict whether a question asked on Quora is sincere or not
* Data: 1.3M labelled questions text
* Concepts: supervised ML, 1st part : using __N.L.T.K, tokenization, stemming, TF-IDF__ and __CountVectorizer__

#### Quora Insincere Questions Classification - PART 2/2 - COMING SOON : [Kaggle]() - [Notebook]() - [PDF]()
* Concepts: __Word embedding, Word2Vec, R.N.N__

## RECOMMENDATION SYSTEM

#### Hybrid Recommendation Engine: [Kaggle](https://www.kaggle.com/obrunet/recommandation-system) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/recommendation/Kaggle/Hybrid_Recommendation_Engine.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/recommendation/Hybrid_Recommendation_Engine.pdf)
* Use case: playlist generators for video and music services like Netflix, YouTube and Spotify...
* Data: 100,000 ratings from 1000 users on 1700 movies (MovieLens 100K Dataset)
* Concepts: supervised ML, __Hybrid recommender system__ (mix collaborative/content-based filtering) with __lightFM__

## DATA SCIENCE

#### Bike Sharing Demand: [Kaggle](https://www.kaggle.com/obrunet/bike-sharing-demand) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Bike-Sharing-Demand/Kaggle/Bike_sharing.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Bike-Sharing-Demand/Kaggle/Bike_sharing.pdf)
* Use case: forecast rentals of a city bikeshare system
* Data: datetime, weather infos, rentals number
* Concepts: supervised ML regression (__GradientBoosting Reg, __Ridge/Lasso__), metric: __RMSLE__

#### Adult Census Income: [Kaggle](https://www.kaggle.com/obrunet/adult-census-income) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Adult%20Census%20Income/Adult%20Census%20Income.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Adult%20Census%20Income/Adult%20Census%20Income.pdf)
* Use case: predict whether income exceeds $50K/yr based on census, define people profiles
* Data: age, workclass, education, marital-status, occupation, race, sex, capital-gain/loss,hours-per-week, country.
* Concepts: supervised ML binary classification, __model explanation__ / feature analysis, __GridsearchCV__. 

#### Customer Segmentation: [Kaggle](https://www.kaggle.com/obrunet/customer-segmentation-k-means-analysis) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Fraud%20Detection/Fraud-Detection.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Fraud%20Detection/Fraud-Detection.pdf)
* Use case: customer segmentation, target customers with whom you can start marketing strategy
* Data: customerID, gender, age, annual income (k$) &	spending score from a supermarket mall customers
* Concepts: __unsupervised__ ML (__KMeans Clustering__)

#### Fraud Detection: [Kaggle](https://www.kaggle.com/obrunet/credit-card-fraud-detection) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer%20Segmentation%20-%20K-Means%20Analysis/k_means.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer%20Segmentation%20-%20K-Means%20Analysis/k_means.pdf)
* Use case: anomalie / fraud detection
* Data: anonymized credit card transactions labeled as fraudulent or genuine, recorded over 2 days
* Concepts: supervised ML binary classification, __classes highly imbalanced__, metric: __Area Under the Precision-Recall Curve__ (AUPRC), __PCA__, Synthetic Minority __Over-sampling__ Technique (SMOTe) & LOF model (LocalOutlierFactor)

#### Real Estate Price: [Kaggle](https://www.kaggle.com/obrunet/california-housing-prices) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Real-Estate-Price/California%20Housing%20Prices.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Real-Estate-Price/California%20Housing%20Prices.pdf)
* Use case: predict a real estate price
* Data: Median house prices for California districts derived from the 1990 census.
* Concepts: supervised ML regression, analysis of __geospatial data__ 

#### Home Credit Default Risk: [Kaggle](https://www.kaggle.com/obrunet/home-credit-default-risk) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Home-Credit/Kaggle/Home_credit_default_risk.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Home-Credit/Kaggle/Home_credit_default_risk.pdf)
* Use case: predict whether or not an applicant will be able to repay a loan
* Data: previous credits, POS (point of sales), cash loans, previous applications and repayment history
* Concepts: supervised ML binary classification (__LightGBM__, __XGBoost__), imbalanced classes, metric: __area under the ROC curve__

#### Customer Churn: [Kaggle](https://www.kaggle.com/obrunet/customer-churn) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer-Churn/01-Customer-churn_completed.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/Customer-Churn/Customer-churn.pdf)
* Use case: predict behavior to retain customers
* Data: the ones who left, services, account infos, contract, payment method, charges, demographic info
* Concepts: supervised ML binary classification, metric: __F1 score, hyperparameters tuning, pipelines__ of models

#### House Prices: [Kaggle](https://www.kaggle.com/obrunet/house-prices) - [Notebook](https://github.com/obrunet/Kaggle_kernels/blob/master/House-prices/kaggle/house_prices.ipynb) - [PDF](https://github.com/obrunet/Kaggle_kernels/blob/master/House-prices/kaggle/house_prices.pdf)
* Use case: predict sales prices
* Data: area, shape, condition, construction year...
* Concepts: supervised ML regression, practice __feature engineering__, RFs, and __gradient boosting__