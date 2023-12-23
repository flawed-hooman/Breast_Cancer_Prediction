## Breast_Cancer_Prediction
A project on Breast Cancer Prediction using KNN and Logistic Regression. A comparison between the two methods has also been shown.

This repository contains the following contents.
* Breast Cancer Wisconsin (Diagnostic) Data Set 
* Sample program

## About the Dataset 
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.  They describe characteristics of the cell nuclei present in the image.Separating plane was obtained using Multisurface Method-Tree (MSM-T) [K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], a classification method which uses linear programming to construct a decision tree.  Relevant features were selected using an exhaustive search in the space of 1-4 features and 1-3 separating planes.

Attribute Information:
1) ID number <br>
2) Diagnosis (M = malignant, B = benign) <br>
3-32) Ten real-valued features are computed for each cell nucleus: <br>
  a) radius (mean of distances from center to points on the perimeter) <br>
  b) texture (standard deviation of gray-scale values) <br>
  c) perimeter <br>
  d) area <br>
  e) smoothness (local variation in radius lengths) <br>
  f) compactness (perimeter^2 / area - 1.0) <br>
  g) concavity (severity of concave portions of the contour) <br>
  h) concave points (number of concave portions of the contour) <br>
  i) symmetry <br>
  j) fractal dimension ("coastline approximation" - 1) <br>

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

## Model Training
Open "[breast-cancer-prediction-knn-logistic-regression(1).ipynb](breast-cancer-prediction-knn-logistic-regression(1).ipynb)" in Jupyter Notebook and execute from top to bottom.<br>
The provided dataset has been used.
The classifications has been done using both K-Nearest Neighbours and Logistic Regression Algorithms.
 ### KNN:-
 K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique. It assumes the similarity between the new  case/data and available cases and puts the new case into the category that is most similar to the available categories. It is a non-parametric            algorithm, which means it does not make any assumption on underlying data.
 
 ### Logistic Regression:-
 Logistic regression is one of the most popular Machine Learning algorithms, which comes under the Supervised Learning technique. It is used for           predicting the categorical dependent variable using a given set of independent variables. Logistic regression predicts the output of a 
 categorical dependent variable. Therefore the outcome must be a categorical or discrete value. It can be either Yes or No, 0 or 1, true or False, etc,    but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and  1. The curve from the logistic function      indicates the likelihood of the data.

## Comparing the algorithms
 The training accuracy and model accuracy score of both the algorithms has been compared and shown using histograms. It is thus observed that Logistic     Regression is giving more accurate result than KNN.
 
<img src="https://github.com/flawed-hooman/Breast_Cancer_Prediction/assets/117461708/b8a40207-0327-4a98-a885-31a3343dfb3b" width="60%">

<img src="https://github.com/flawed-hooman/Breast_Cancer_Prediction/assets/117461708/50797aa4-f250-4973-a435-dd927d8bac5a" width="60%">

## License 
Breast_Cancer_Prediction is under [Apache v2 license](LICENSE).
