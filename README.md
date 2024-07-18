# Diabetic-Prediction-Model
The project entails training an ML model that predicts if patients have diabetes or not.
Data Source:
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases.
🔍 Project Overview:
Objective: The primary goal of this dataset is to predict, based on specific diagnostic measurements, whether a patient has diabetes. 🩺📈
1️⃣ Exploratory Data Analysis (EDA): Informative visualizations, missing value checks, and descriptive statistics.
2️⃣ Data Preprocessing: Handling of missing values, encoding categorical variables, and normalization.
3️⃣ Modeling: Selection of appropriate algorithms and model training.
4️⃣ Evaluation and Interpretation: Performance evaluation using relevant metrics.
5️⃣ Conclusion: Summarizing findings and discussing future steps.
Insights are:
👉 65.1% of the data are diabetic patients. 
👉 The Age feature divided in 5 subsets and in group 3 reported more than 50% of the population as diabetes. This leads to have a very careful consideration of the risk of this group with high possibility of the diabetes.
👉 Average of insulin for both group with and without diabetes are 116.04 and 83.18 (U/mL) respectively.
👉 Average of DPF (Diabetes Pedigree Function), for both group with and without diabetes are 0.55 and 0.43.
👉 The machine learning algorithm used for this analysis is logistic regression with reported f1 score around 0.59 that shows the algorithm works quite well as it is more than 0.5 and remarkable ROC_AUC_score = 0.78.
👉 Coefficient plot has been applied to emphasize the effect of the features on the prediction result. 

Result:
📈 Models achieved remarkable accuracy, enabling us to predict diabetes patients with a high degree of certainty. Early diagnosis and intervention can make a significant impact on patients' lives.
This project has been a testament to the incredible possibilities that Machine Learning offers in the healthcare domain. 
