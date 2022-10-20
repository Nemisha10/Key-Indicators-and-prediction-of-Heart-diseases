# Key-Indicators-and-prediction-of-Heart-diseases

# Problem Statement 
Heart disease is one of the major causes of death for persons of most races in the US, according to the CDC (African Americans, American Indians and Alaska Natives, and white people). High blood pressure, high cholesterol, and smoking are the three main risk factors for heart disease that at least half of all Americans (47%) have. Other significant indicators are the presence of diabetes, obesity (high BMI), a lack of physical activity, and excessive alcohol consumption. In the field of medicine, it is crucial to identify and combat the causes that have the biggest influence on heart disease. In turn, advances in computation enable the use of machine learning techniques to identify "patterns" in data that can foretell a patient's state.

# Dataset
https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease 

# Methodology
Only roughly 20 variables remained from the original dataset's almost 300 variables. This dataset can be used to apply a variety of machine learning techniques, most notably classifier models, in addition to conventional EDA. The variable "HeartDisease" should be handled as a binary ("Yes" - respondent had heart disease; "No" - respondent had no heart disease). However, the classes are unbalanced,fixing the weights/undersampling should result in noticeably improved findings. I created a logistic regression model using the dataset.
