# Catherine Leal's Data Portfolio

These personal projects demonstrate some of the data analysis and data science skills I developed during my undergraduate and graduate studies.

## Supervised Learning 
|Category | Project | Description | Topics | Language + Libraries | 
| --- | --- | --- | --- | --- | 
| Classification| [Predicting Fetal Health with Tree-Based Models](https://github.com/catherinealeal/FetalHealthClassifier) | Three classification models (decision tree, AdaBoost, random forest) are trained to predict whether a fetus’s health is normal, suspect or pathological based on CTG data. Models are compared using accuracy and F1-score. |Decision Trees, AdaBoost, Random Forests, Generalization Error, F1-Score, Feature Importance|Python - sklearn.tree, sklearn.ensemble, sklearn.model_selection, sklearn.metrics, matplotlib| 
|Classification| [Comparing Classifiers for Predicting Survival of Heart Failure Patients](https://github.com/catherinealeal/ClassifyingHeartFailurePatients) | K-Nearest Neighbors, Gaussian Naive Bayes, and Logistic Regression models are trained to predict survival of heart failure patients. | KNN, Gaussian NB, LR, PCA, Parameter Tuning, Precision, Recall, F1-Score | Python - sklearn.naive_bayes, sklearn.linear_model, sklearn.neighbors, sklearn.model_selection, sklearn.preprocessing, sklearn.decomposition, sklearn.metrics| 
|Regression| [Predicting Medical Costs with Linear Regression](https://github.com/catherinealeal/InsuranceCostPrediction) |Medical insurance companies provide coverage to customers based on their predicted yearly medical costs. The goal of this project is to build a linear regression model that predicts an individual’s yearly medical costs based on their background information.| Simple + Multiple Linear Regression, Residual Analysis, Lasso Regresion for Feature Selection | Python - sklearn.linear_model, matplotlib| 

## Unsupervised Learning 
|Category | Project | Description | Topics | Language + Libraries | 
| --- | --- | --- | --- | --- | 
| Deep Learning | [Automatic Brain MRI Segmentations](https://github.com/catherinealeal/DLBrainSegmentation) | As a part of my 2023 internship at Pestilli Lab, I worked on 2 projects with the common goal of automating white matter tract segmentations using neural networks. One project focused on entire-brain automated segmentation while the second project focused on the tracking of just auditory pathways. | Data Preprocessing, Hyperparameter Tuning, CNNs | Python - pandas, seaborn |
| Clustering | [Analyzing Blood Biomarkers to Identify Patients at Risk of Diabetes](https://github.com/catherinealeal/ClusteringDiabeticBiomarkers/tree/main) | K-Means and Spectral Clustering are used to explore patterns in patient biomarker data and assess whether unsupervised methods can help identify individuals at risk of diabetes. | KMeans, Spectral Clustering, PCA, Silhouette score, Adjusted Rand Index, Normalized Mutual Info| Python - sklearn.preprocessing, sklearn.cluster, sklearn.metrics, sklearn.decomposition, matplotlib| 
| Clustering| [Clustering Health Data to Recognize Obesity Levels](https://github.com/catherinealeal/ClusteringWeightCategories/tree/main) | Hierarchical Clustering, DBSCAN, and Gaussian Mixture Models are used to group individuals based on lifestyle and health features to see if the clusters reflect their obesity levels.| Hierarchical Clustering, DBSCAN, GMM, Silhouette Score, ARI| Python - sklearn.preprocessing, sklearn.decomposition, sklearn.cluster, sklearn.mixture, sklearn.metrics, matplotlib| 

## Other Projects
|Category | Project | Description | Topics | Tools | 
| --- | --- | --- | --- | --- |
| Modeling | [Survival Analysis of Veterans with Lung Cancer](https://github.com/catherinealeal/VeteranSurvivalAnalysis)  | Parametric and non-parametric methods are used to analyze the survival of veterans with lung cancer using time-to-event data and co-variates.|Survival Analysis, Weibull/Exponential Parametric Model, Kaplan-Meier Estimator, Likelihood Ratio Test, Log-Rank Test| R - survival(Surv, survreg, survfit, survdiff)| 
| Data Analytics | [Revenue Loss Analysis with SQL](https://github.com/catherinealeal/RevenueLossAnalysis) | I examine a company’s transactional data to understand factors contributing to their revenue loss and to identify strategies for improving profit.| Joins, Aggregrating, Case Statements, Sorting | SQLite | 
| Data Visualization | [Platform Statistics Dashboard with Tableau](https://github.com/catherinealeal/BLDashboard) | As a part of my 2023 internship, I used Tableau to create plots and dashboards for displaying a platform's usage statistics. | Data Visualization | Tableau |
