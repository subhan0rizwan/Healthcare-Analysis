# Healthcare-Analysis
## Introduction
This project aimed to analyze the relationship between weather conditions, patient health, and treatment outcomes. The goal was to build machine learning models that predict health outcomes based on weather data and patient conditions. Additionally, an ongoing framework is being developed for an interactive app that allows users to predict diseases and receive treatment recommendations based on their symptoms.

![download (5)](https://github.com/user-attachments/assets/6e907de9-f4b9-44a0-89bd-e05ee87d5de7)

## Problem Statement
Patients' health can be affected by environmental factors such as weather conditions. Understanding these relationships could help improve treatment plans and hospital preparedness. The project involved analyzing a dataset of patients’ health conditions, weather variables, and treatment outcomes to build predictive models.

![download (4)](https://github.com/user-attachments/assets/9b5d79db-c483-46d1-9b6e-1bed967f96c5)

Furthermore, a separate but related effort is being made to develop an interactive app that helps users predict possible diseases from symptoms and offers treatment suggestions based on the dataset used in this project.

## Dataset
The dataset consists of:

**Patient information**: Age, gender, underlying health conditions, etc.
**Weather data:** Temperature, humidity, air quality, etc.
**Treatment details:** Types of treatment received and outcomes (recovery, worsening condition).
**Symptoms:** Used to develop the disease prediction model in the ongoing app framework.

### Data Preprocessing
**Handling Missing Data**: Missing values were imputed using statistical methods.
**Feature Engineering**: Derived additional features from weather data such as temperature fluctuations, heat waves, or cold spells.
**Categorical Data Encoding**: Categorical features were encoded using one-hot encoding.

## Methodology
### Exploratory Data Analysis (EDA)
Identified trends between weather patterns, the frequency of specific medical conditions, and the patients treated.

Visualized the distribution of these variables across different patient outcomes.

![download (8)](https://github.com/user-attachments/assets/a7941d24-467c-49b7-b5e6-b166fad9b649)

### Machine Learning Models
Several machine learning models were tested:

Logistic Regression
Random Forest
Gradient Boosting
K-Nearest Neighbors (KNN)

### Model Training & Evaluation
Cross-validation was used to assess model performance.

![download (11)](https://github.com/user-attachments/assets/b2a147f3-50f8-45d7-9d2b-ffb2f39b92b2)

Evaluation metrics included accuracy, precision, recall, and F1-score.


## Results
The models performed with lower-than-expected predictive accuracy, likely due to the complexity and noisiness of the data.
The best model is Random Forest, which has an accuracy score of 65% but is still not ideal for practical deployment.

![download (9)](https://github.com/user-attachments/assets/d2b95aea-0fef-421e-901f-f8813c694417)


### Challenges faced:
The data had high variability, making it difficult to extract clear patterns.
Limited data on certain patient conditions, reducing model generalizability.

## Ongoing Framework: Interactive App Development
A major extension of this project is the development of an interactive app that predicts diseases based on symptoms and provides treatment recommendations. The app utilizes the same dataset but focuses on symptoms as inputs to provide:

Disease prediction: Based on selected symptoms, the app predicts the most likely diseases.
Treatment suggestions: Offers suggested treatments and precautions for the predicted diseases.
This framework is still under development, to deploy a user-friendly interface that assists users in identifying possible health conditions and relevant treatments.

## Challenges & Learnings
**Feature Importance Analysis:** Weather factors like temperature and humidity had some influence, but patient-specific variables such as age and pre-existing conditions played a bigger role.
**Complexity of real-world data:** The dataset was noisy, with many confounding factors making it difficult to achieve high accuracy.
**Interactive App Development:** Building a robust system to handle multiple symptom inputs and provide reliable predictions remains a challenging task, but progress is being made.

## Conclusion

This project demonstrated the challenges of working with real-world medical and environmental datasets. While the machine learning models did not perform at the desired level, the project offered valuable insights into the relationships between weather conditions and patient health.

The ongoing development of an interactive app will extend this work by offering practical, symptom-based disease prediction and treatment recommendations to users.
