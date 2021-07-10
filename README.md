# Credit-Risk-Analysis
Access the South German Credit Dataset at: http://archive.ics.uci.edu/ml/datasets/South+German+Credit+%28UPDATE%29

# Dataset Description 
The dataset consists of a set of attributes that describe the people who have been classified as good or bad credit risk by a south German bank. There are 1000 entries in the dataset, among which 700 are classified as good credit risk and 300 as bad credit risk.

# Analysis
I have demonstrated how to utilize Python packages (e.g. pandas, NumPy, Seaborn, Matplotlib, and sci-kit-learn) to generate a variety of visualizations, perform statistical calculations, and build a classifier model.   

I have also illustrated how to overcome challenges working on binary classification problems with an imbalanced dataset using the Synthetic Minority Oversampling Technique (SMOTE). SMOTE creates synthetic new samples from the existing ones among the minority class to balance the distribution of the classes.

Class imbalance is common among industries where low occurrence of the minority class is typical, such as rare disease diagnosis, fraud detections, and system failure. If data augmentation is not performed on the imbalanced dataset prior to training the classifier, the result is often a high-accuracy low-recall model.

# Sections 

**1.	Descriptive Analysis**
- Cross tabulations are created to display the frequency and proportions of components by credit risk classifications, which highlight potential relationships between variables.
- A variety of charts are generated to summarize information, accentuate key patterns from the dataset, and provide clear comparisons between subgroups.
	
**2.	Cramer’s V**
-  Data preparation with encoding categorical variables.
-  Heatmap of Cramer’s V is created to illustrate the strength of association between the transformed categorical features and response variable. The results help identify features that are likely to be good predictors.

**3.	Logistic Regression and SMOTE**
- Logistic regression model is created with predictor variables identified as having the strongest association with the response variable.
- SMOTE is used to oversample the minority class in the training dataset for re-training the logistic regression model.
- A comparison of model performance pre and post class adjustment is evaluated by accuracy and recall scores, and confusion matrix.
