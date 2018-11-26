# ANNWCC
Tutorial for clinical data classification. 
Clinical and biological data classification has applications in several areas such as the diagnosis, estimation and prognosis of diseases. It is one of the most challenging problems in the field of machine learning, and one of the most critical problems in medicine. In order to address this issue, we propose a new method based on a combination of an ANN and the WCC algorithm in order to classify a clinical dataset.
This repository includes datasets which are taken from the literatures and source codes which are wrote in MATLAB programing language. Our method, which can be used for balanced or unbalanced data, was verified using nine real clinical and biological datasets and compared with two efficient optimization algorithms. The experimental results show that our method achieves better results than the other approaches. 



# The Datasets
We have used the biological and real clinical data sets used in various literatures. The datasets are relative to several fields such as heart, diabet and cnacer diseases. These data sets have different characteristics. For example, a number of their samples are more than their features, or a number of their attributes are more than their samples. Also, some of the datasets are binary classification problems whereas others are multi-class classification problems. in the preprocess stage, data which have missing values are removed. Then fuzzification and normalization of them are done. The acquired datasets can be used for clinical and biological data classification using machine learning approaches. The properties of the datasets are depicted in fig.1. NOI, NOF, NOC, DT, and MV are abbreviations for a number of instances, a number of features, a number of classes, data type, and missing values respectively.

![image](https://user-images.githubusercontent.com/45210797/49004248-14f90100-f179-11e8-8b6a-db964e61c2fe.png)

Fig.1: The properties of the datasets


# The source codes
We implemented ANNWCC in the MATLAB programing language. In the source codes which consist of several functions, we combined an artificial neural network (ANN) with the World Competitive Contests (WCC) algorithm, designing a model for each existing class using an ANN and then training it using WCC. We then evaluated the performance of the algorithms in the various experiments and described their functionality. The criteria used for comparison of the algorithms were convergence, stability, error, the correlation between predicted labels and actual labels, accuracy, ac and specificity. The results forANNWCC algorithm were better than those of the others. 
