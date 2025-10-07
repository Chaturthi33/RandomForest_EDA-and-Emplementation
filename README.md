# Brain Tumor Detection — ML Classification Project

## 📘 Overview

### This project uses the Brain Tumor Dataset from Kaggle to analyze patient data and build machine learning models that classify tumor MRI results (Positive/Negative).
### The dataset is processed, visualized, and modeled using Python (pandas, sklearn, seaborn, matplotlib).

# 📂 Dataset Information

####   Source: Kaggle – miadul/brain-tumor-dataset


#### File used: brain_tumor_dataset.csv
#### Records: 20,000 rows × 19 columns

### 🧾 Columns Description
     Feature	Description
     Patient_ID	Unique ID per patient
     Age	Patient age
     Gender	Male/Female
     Tumor_Type	Benign or Malignant
     Tumor_Size	Tumor size (cm³)
     Location	Brain region (Frontal, Temporal, Parietal, Occipital)
     Histology	Tumor cell type
     Stage	Stage I–IV
     Symptom_1/2/3	Reported symptoms
     Radiation_Treatment	Yes/No
     Surgery_Performed	Yes/No
     Chemotherapy	Yes/No
     Survival_Rate	Patient survival likelihood
     Tumor_Growth_Rate	Growth velocity
     Family_History	Yes/No
     MRI_Result	Target variable (Positive=1, Negative=0)
     Follow_Up_Required	Yes/No


#### Data Preprocessing

#####  .Checked for missing values → none found

#####  .Checked for duplicates → none found

#####  .Label encoding applied to categorical columns:

#####  .Gender, Location, Histology, Stage, Symptoms, Treatments, etc.

#####  .Mapped target:

## 📈 Visual Summary
                    
 ### 🔹 Bar chart	        
 ### 🔹 Pie chart             
 ### 🔹 Histogram	         
 ### 🔹 Correlation heatmap 

### ⚙️ Requirements
##### pip install pandas numpy seaborn matplotlib scikit-learn kagglehub

## 📘 Model Overview
#### The Random Forest Classifier is a supervised machine learning algorithm used in this project to predict whether a patient’s brain tumor MRI result is Positive (1) or Negative (0) based on various clinical and imaging features.




