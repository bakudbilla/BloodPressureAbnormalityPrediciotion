# Blood Pressure Abnormality Prediction

# <h3>Abstract</h3>
This project  is aimed at reducing blood pressure fatalities in Ghana especially the  rural areas where access to medical equipment is limited and they are not able to effectively monitor blood pressure levels. Growing up in Garu, a rural area in the upper East region of Ghana. I experienced firsthand what patients go through after it is detected late and they have to suffer the complications.This project aims to develop a classification model for  blood pressure abnormality prediction  by using data on alcohol consumption, smoking status, Gender and BMI. <br>

# <h3>Problem Statement</h3>
Hypertension is a global crisis which affects about 1.28Million adults aged 30–79 years worldwide, most (two-thirds) living in low- and middle-income countries[2]. Growing up in Garu, I experienced  first-hand the struggles patients go through to check their blood pressure levels due to lack of equipment at the hospital. High Blood pressure is one of the leading heart diseases which causes about 17.9million deaths annually

# <h3>The Dataset</h3>
This dataset is a Blood Pressure data used to predict blood pressure abnormality in individuals. This data contains 13 input features such as
     Patient_Number, Blood_Pressure_Abnormality, Level_of_Hemoglobin,
       Genetic_Pedigree_Coefficient, Age, BMI, Sex, Pregnancy,
       Smoking, Physical_activity, salt_content_in_the_diet,
       alcohol_consumption_per_day, Level_of_Stress,
       Chronic_kidney_disease, Adrenal_and_thyroid_disorders.
 These are crucial factors that contribute to high blood pressures that cause people to loose their lives if not detected early.

Dataset Source:KAGGLE 

Data can be found https://www.kaggle.com/datasets/pavanbodanki/blood-press

# <h3>Summary Table</h3>

## Model Training Instances

| Training Instance | Optimizer Used | Regularizer Used | Epochs | Early Stopping | Number of Layers | Learning Rate | Dropout | Accuracy | F1 Score | Recall | Precision |
|------------------|---------------|----------------|--------|---------------|----------------|--------------|---------|---------|---------|--------|-----------|
| Instance 1      | Adam          | -              | 250    | No             | 3              | 0.0001      | 0.35     | 0.8167  | 0.8161  | 0.8166 | 0.8161    |
| Instance 2      | SGD           | L1             | 250    | Yes            | 4              | 0.001       | 0.3      | 0.8767  | 0.8770  | 0.8767 | 0.8783    |
| Instance 3      | RMSProp       | L2             | 250    | Yes            | 4              | 0.0001      | 0.3      | 0.8233  | 0.8242  | 0.8233 | 0.8317    |
| Instance 4      | AdamW         | L1_L2          | 250    | Yes            | 4              | 0.0005      | 0.3      | 0.8733  | 0.8736  | 0.8733 | 0.8741    |

## Logistic Regression Model Summary

| C Value | Penalty | Solver  | Max Iterations | Accuracy | Precision | Recall | F1 Score |
|---------|---------|---------|---------------|----------|-----------|--------|----------|
| 0.5     | L2      | lbfgs   | 100           | 0.6967   | 0.6980    | 0.6967 | 0.7018   |

# <h3>Summary</h3>
