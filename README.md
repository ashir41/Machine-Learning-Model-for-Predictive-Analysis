# Machine-Learning-Model-for-Predictive-Analysis

Cardiovascular disease, commonly known as heart disease, remains a significant global cause of mortality. Timely identification of heart disease is crucial for delivering appropriate medical intervention. In the realm of healthcare research, machine learning (ML) techniques have gained prominence. Leveraging ML, the prediction of heart disease can be executed with high efficiency. Through the analysis of risk factors, patterns, and data insights, machine learning can anticipate the likelihood of an individual developing heart disease. Our objective in this project is to construct a precise prediction model using machine learning methodologies for early heart disease diagnosis. The dataset we've gathered originates from a reputable health database, and such datasets, when employed in machine learning, can facilitate the creation of a reliable heart disease prediction model. This has the potential to significantly enhance patient care and clinical outcomes. With the abundance of electronic health records and health-related data sources, there's an escalating requirement for effective ML-driven techniques to leverage and interpret this data for predictive modeling in healthcare. The outcomes of this project bear the potential to profoundly influence clinical procedures, public health strategies, and policy formulation, as it can furnish valuable insights for identifying individuals at a heightened risk of developing heart disease. The project covers diverse aspects ranging from data preprocessing techniques, assessing correlations between risk factors and the target variable, model training and evaluation, to performance metrics such as accuracy, precision, recall, and F1 score, all underscored with detailed visualizations. These efforts are all driven by our motivation, which centers on contributing to the growing knowledge base in this domain and offering meaningful and practical insights for healthcare practitioners and researchers. The project provides a comprehensive exploration of machine learning approaches for predicting heart disease.



Dataset description

Source
The original data came from the Cleveland database from UCI Machine Learning Repository.

Link: https://archive.ics.uci.edu/ml/datasets/heart+Disease

However, we've downloaded it in a formatted way from Kaggle.

Link: https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset

The subsequent features will be employed for predicting the target variable, which indicates the presence or absence of heart disease:

Age: The age of the individual in years.
Sex: Gender of the individual (1 = male; 0 = female).
Chest Pain Type (cp)
   Typical angina - chest pain linked to reduced blood supply to the heart.
   Atypical angina - chest pain not related to the heart.
   Non-anginal pain - often esophageal spasms (not heart-related).
   Asymptomatic - chest pain showing no signs of disease.
Resting Blood Pressure (trestbps): Initial blood pressure upon admission (in mmHg); values above 130-140 may be concerning.
Serum Cholesterol (chol): Serum cholestrol level in mg/dl; values above 200 could be concerning.
Fasting Blood Sugar (fbs): Whether fasting blood sugar is greater than 120 mg/dl (1 = true; 0 = false); values above 126 mg/dl might indicate diabetes.
Resting Electrocardiographic Results (restecg)
   Nothing significant to note.
   Abnormal ST-T Wave - ranging from mild symptoms to severe problems; suggests non-normal heart rhythm.
   Possible or definite left ventricular hypertrophy - enlargement of the heart's main pumping chamber.
Maximum Heart Rate Achieved (thalach).
Exercise Induced Angina (exang): Whether exercise induced angina (1 = yes; 0 = no).
ST Depression Induced by Exercise (oldpeak): Relative ST depression during exercise compared to rest; higher values might suggest a stressed heart.
Slope of Peak Exercise ST Segment (slope):
    Upsloping - improved heart rate with exercise (uncommon).
    Flat Sloping - minimal change (typical for a healthy heart).
    Downsloping - indicates an unhealthy heart.
Number of Major Vessels (ca): This attribute signifies the count of major vessels (ranging from 0 to 3) that are visualized with fluoroscopy 
The presence of color within a vessel indicates that a doctor can observe blood flowing through it, which is a positive indicator.
More significant blood movement through these major vessels indicates improved circulation and suggests the absence of clotting issues.
Thalium Stress Result (thal):
   These values correspond to normal thalium stress results.
   Represents a fixed defect, indicating that there was a defect previously, but it has now stabilized and is no longer a concern.
   Denotes a reversible defect, which indicates inadequate blood movement during exercise.
Target: This attribute serves as the predicted outcome. It denotes whether the individual is affected by heart disease.
   Implies the individual has heart disease.
   Indicates the individual does not have heart disease.


 
