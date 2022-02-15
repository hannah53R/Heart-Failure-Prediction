# Heart-Failure-Prediction
EDA and prediction using machine learning in RStudio.

# About
In this project I conduct an exploratory data analysis (EDA) on heart failure data and use multiple machine learning algorithms to predict the survival of patients suffering with heart failure. I begin by visualizing the data and presenting summary statistics, then identify which features have the highest correlation to the target variable using The Mann-Whitney U test, followed by constructing the models, and finally comparing the results of the models.

# Introduction
In 2019, the World Health Organization (WHO) reported an estimated 17.9 million people died from Cardiovascular diseases (CVDs), accounting for 32% of all global deaths. Heart Failure (HF) occurs when the heart muscle isn’t able to pump blood to meet the demands of the body, and remains prevalent among people suffering with CVD.

Supervised learning will be used to map inputs to outputs, or in other words, use the predictor variables across the data set to predict the target variable (death event). The target variable takes on two values, 0 or 1, so classification algorithms will be used to build the models.

This project uses an assortment of machine learning algorithms () to predict survival of patients with heart failure. In practical terms, this can provide healthcare professionals with insight into what lifestyle and bodily measurements can be leveraged to help treat and mitigate patients suffering from heart failure. This information can in turn identify what patients with HF are most at risk for mortality, and allow healthcare professionals to treat them accordingly. 

# About the dataset 
The original dataset is publicly available and can be found at https://plos.figshare.com/articles/dataset/Survival_analysis_of_heart_failure_patients_A_case_study/5227684/1 

The dataset is composed of 299 patient medical records across 13 features, collected in 2015. Some of the variable names were changed to follow a common formatting style. The records detail information on patient lifestyle and clinical and body readings. Some features are categorical, while others are continuous or discrete. Explanation of variables can be found below. Boolean variables define 0 as being false and 1 as being true, unless otherwise stated. 

Age: the age of the patient (yrs).

Anaemia: if the patient has anaemia (boolean). A patient was considered to have anaemia if haematocrit levels were lower than 36%. 

High Blood Pressure: if the patient has high blood pressure (boolean). No information on the criteria used to classify a patient as having high blood pressure.

Creatinine Phosphokinase (CPK_Level): level of CPK enzyme in blood (mcg/L). 

Diabetes: if the patient has diabetes (boolean).

Ejection Fraction: the percentage of how much blood the left ventricle pumps out with each contraction (%).

Sex: the sex of the patient (boolean). 0 indicates female, 1 is male. 

Platelets: count of platelets in the blood (kiloplatelets/mL).

Serum Creatinine (Creatinine): level of creatinine in the blood (mg/dL).

Serum Sodium (Sodium): level of sodium in the blood (mEq/L).

Smoking: if the patient smokes (boolean).

Time: follow up period (days).

Death Event (target variable): if the patient died during the follow up period (boolean). 0 indicates survived, 1 deceased. 


# Results 






 



