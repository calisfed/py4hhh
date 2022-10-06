# Pros and Cons of basic ML algorithms

- [Pros and Cons of basic ML algorithms](#pros-and-cons-of-basic-ml-algorithms)
  - [Random Forest](#random-forest)
  - [Gradient Boosting](#gradient-boosting)
  - [Linear Regression](#linear-regression)
  - [Support Vector Machine](#support-vector-machine)
  - [K Nearest Neightbor](#k-nearest-neightbor)
  - [Adaboost](#adaboost)
  - [Native Bayes](#native-bayes)
  - [Neutral Networks](#neutral-networks)
  - [Logistic Regression](#logistic-regression)
  - [SVD](#svd)
  - [PCA](#pca)
  - [K Means](#k-means)

## Random Forest

- Best fit
  - Suited for at almost any ML problem
  - Ex. Bioinformatics
- Pros
  - Can work in parallel
  - Suscepitble to overfits
  - Automatically handles missing values if you - impute using a special number
  - No need to transform any variable
- Cons
  - Difficult to interpret
  - Weaker on regression when estimating values at the extremities of the distribution of response values
  - Biased in multiclass problems toward more frequent classes

## Gradient Boosting

- Best fit
  - Apt at almost any ML problem
  - Search engines (solving the problem of learning to rank)
- Pros
  - It can approximate most non-linear function
  - Best in class predictor
  - Automatic handles missing values
  - No need to transform any values
- Cons
  - It can overfit if run for too many iterations
  - Sensitive to noisy data and outliers
  - Doesn't work at its best without parameter tuning

## Linear Regression

- Best fit
  - Baseline prediction
  - Econometric predictions
  - Modeling
  - Marketing response
- Pros
  - Simple to understan and explain it seldom overfit
  - Using L1 & L2 regularization is effective in - feature selection
  - Fast to train
  - Easy to train on big data thanks to its stochastic version
- Cons
  - You have to work hard to make it fit non linear function
  - Can suffer from outliers

## Support Vector Machine


- Best fit
  - Character recognition
  - Image recognition
  - Text classifition
- Pros
  - Automatic nonlinear feature creation
  - Can approximate complex nonlinear functions
  - Works only with a portion of the examples (the suport vectors)
- Cons
  - Difficult to interpret when applying nonlinear kernels
  - Suffers from too many examples, after 10 000 examples, it starts taking too long to train

## K Nearest Neightbor

- Best fit
  - Computer vision
  - Multilablel tagging
  - Recommender systems
  - Spell checking problems
- Pros
  - Fast, lazy traing
  - Can handle naturally handle extreme multiclass prblems (like tagging text)
- Cons
  - Slow and cumbersome in predicting phase
  - Can fall to predict correctly dus to the curse of dimensionality

## Adaboost

Adaboost

- Best fit
  - Facedetection
- Pros
  - Automatically handles missing values
  - No need to transform any variable
  - It doesn't overfit easily
  - Few parameters to tweak
  - It can leverage many different weaklearners
- Cons
  - Sensitive to noisy data and outliers
  - Never the best in class predictions

## Native Bayes

- Best fit
  - Face recognition
  - Sentiment analysis
  - Spam detection
  - Text classification
- Pros
  - Easy and fast to implement, doesn't require too much memory and can be used for online learning
  - Easy to understand
  - Takes into account prior knowledge
- Cons
  - Strong and unrealistic independence assumptions
  - Fails estimating rare occurrences
  - Suffers from irrelevant features

## Neutral Networks

- Best fit
  - Image Recognition
  - Language recognition and translation
  - Speech recognition
  - Vision recognition
- Pros
  - It can approximate any nonlinear function
  - Robust to outliers
  - It can work with image, text and sound data
- Cons
  - It requires you to define a network architecture
  - Difficult to tune because of too many parameters and you have to decide the architecture of the network
  - Difficult to interpret
  - Easy oto overfit

## Logistic Regression

- Best fit
  - Ordering results by probability
  - Modeling marketing responses
- Pros
  - Simple to understand and explain
  - It seldom overfits
  - Using L1 & L2 regularization is effective to feature selection
  - The best algorithm for predicting probabilities of an event
  - Fast to train
- Easy to train on big data thanks to its stochastic version
- Cons
  - You have to work hard to make it fit nonlinear functions
  - Can suffer from outliers

## SVD

- Best fit
  - Recommendation Syste,
- Pros
  - Can restructure data in a meaningful way
- Cons
  - Difficult to understand why data has been restructured in a certain way

## PCA

- Best fit
  - Removing collinearity
  - Reducing dimensions of the dataset
- Pros
  - Can reduce data dimensionality
- Cons
  - Implies strong linear assumptions (components are weighted summations of features)

## K Means

- Best fit
  - Segmentation
- Pros
  - Fast in finding clusters
  - Can detect outliers in multiple dimensions
- Cons
  - Suffers from multicollinearit
  - Clusters are spherical, can't detect groups of other shape
  - Unstable solutions. depends on initialization
