# Brain Tumor Detection — ML Classification Project

## 📘 Overview

### This project uses the Brain Tumor Dataset from Kaggle to analyze patient data and build machine learning models that classify tumor MRI results (Positive/Negative).
### The dataset is processed, visualized, and modeled using Python (pandas, sklearn, seaborn, matplotlib).
### Final model achieved 100% accuracy with Logistic Regression (after encoding and scaling).

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
