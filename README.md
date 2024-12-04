# Machine-Learning-Model-for-Predictive-Analysis

Heart disease, commonly referred to as cardiovascular disease, continues to be a major cause of death across the globe. Early diagnosis of heart disease is essential for the purpose of providing appropriate medical support. In healthcare research machine learning (ML) methods have recently become more popular. Moreover, with the use of Machine learning prediction of heart disease can be done very efficiently. By identifying the risk factors, patterns and other data analysis, Machine learning can forecast the likelihood of a person developing heart disease. Our aim in this project is to create an accurate prediction model with the use of Machine learning techniques for the early diagnosis of heart disease. The dataset that we collected comes from a renowned health database and by using this kind of dataset in machine learning an accurate and dependable heart disease prediction model can be created. This can dramatically improve patient care and other clinical outcomes. There is a growing need for efficient ML-based methods to assess and use these data for predictive modeling in healthcare as there’s a vast accessibility of electronic health records and other sources of health related data. The results of this project have the potential to have a considerable impact on clinical practice, public health strategies, and policy-making as it can provide insightful information for identifying individuals with high risk of getting heart disease. In this project starting from the technique for data processing, comparing and finding correlation between each risk factor and target, training and evaluating the model, as well as the performance metrics of the employed ML models, including accuracy, precision, recall, and F1 score all are explored with visualization detail. All these works come down to our motivation with this project, which is to add to the expanding body of knowledge in this area and offer valuable productive information for healthcare professionals and researchers by offering a thorough examination of ML approaches for heart disease prediction.


Dataset description
Source
The original data came from the Cleveland database from UCI Machine Learning Repository. Link: https://archive.ics.uci.edu/ml/datasets/heart+Disease
However, we've downloaded it in a formatted way from Kaggle.
Link: https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset
Accessing dataset
The original database contains 76 attributes, but here only 14 attributes will be used. Attributes (also called features) are the variables that we'll use to predict our target variable. In our case, the independent variables are a patient's different medical attributes and the dependent variable is whether or not they have heart disease.
 

 

The following are the features we'll use to predict our target variable (heart disease or no heart disease).
1.	age - age in years
2.	sex - (1 = male; 0 = female)
3.	cp - chest pain type
●	0: Typical angina: chest pain related decrease blood supply to the heart
●	1: Atypical angina: chest pain not related to heart
●	2: Non-anginal pain: typically esophageal spasms (non heart related)
●	3: Asymptomatic: chest pain not showing signs of disease
4.	trestbps - resting blood pressure (in mm Hg on admission to the hospital)
●	anything above 130-140 is typically cause for concern
5.	chol - serum cholestoral in mg/dl
●	serum = LDL + HDL + .2 * triglycerides
●	above 200 is cause for concern
6.	fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
●	'>126' mg/dL signals diabetes
7.	restecg - resting electrocardiographic results
●	0: Nothing to note
●	1: ST-T Wave abnormality
○	can range from mild symptoms to severe problems
○	signals non-normal heart beat
●	2: Possible or definite left ventricular hypertrophy
○	Enlarged heart's main pumping chamber
8.	thalach - maximum heart rate achieved
9.	exang - exercise induced angina (1 = yes; 0 = no)
10.	oldpeak - ST depression induced by exercise relative to rest
●	looks at stress of heart during exercise
●	unhealthy heart will stress more
11.	slope - the slope of the peak exercise ST segment
●	0: Upsloping: better heart rate with exercise (uncommon)
●	1: Flat Sloping: minimal change (typical healthy heart)
●	2: Downsloping: signs of unhealthy heart
12.	ca - number of major vessels (0-3) colored by fluoroscopy
●	colored vessel means the doctor can see the blood passing through
 
●	the more blood movement the better (no clots)
13.	thal - thalium stress result
●	1,3: normal
●	6: fixed defect: used to be defect but ok now
●	7: reversable defect: no proper blood movement when excercising
14.	target - have disease or not (1=yes, 0=no) (= the predicted attribute)
Correlation

 
Data description
This problem is a classification problem. The problem of determining whether a person has heart disease or not is a classification problem because the task involves assigning discrete class labels to each instance in the dataset. In this case, the classes are "has heart disease" and "does not have heart disease." The goal is to build a predictive model that can learn from the given features (such as age, sex, chest pain type, etc.) and classify new instances into one of these two classes based on the learned patterns and relationships in the data. Classification algorithms are specifically designed to handle this type of problem where the output is categorical in nature.
Number of data points: 1028, both quantitative and categorical. Quantitative: age, bp, chol etc.
Categorical: sex, chestpaintype etc.
Data distribution

 
