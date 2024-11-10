
## Diabetes Prediction and Feature Analysis

### Project Overview:
This project focuses on the analysis and prediction of diabetes based on a set of health-related features. Diabetes is a chronic health condition where the body fails to properly convert food into energy, leading to elevated blood sugar levels. Without proper management, diabetes can lead to serious complications, such as heart disease and stroke. The goal of this project is to predict whether a person is diabetic and identify the most indicative features for diagnosing the condition.

### Objectives:
1. **Diabetes Prediction**: To predict whether a person has diabetes based on a set of health features.
2. **Feature Analysis**: To analyze the most indicative features that contribute to diabetes prediction and determine relationships between these factors.

### Dataset Features:
The dataset used in this analysis contains the following features:
- **Pregnancies**: Number of times the person has been pregnant.
- **Glucose**: Plasma glucose concentration over 2 hours in an oral glucose tolerance test.
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skinfold thickness (mm).
- **Insulin**: 2-hour serum insulin (mu U/ml).
- **BMI**: Body mass index (weight in kg / height in m²).
- **DiabetesPedigreeFunction**: A genetic score of diabetes.
- **Age**: Age in years.
- **Outcome**: Binary classification indicating the presence (1) or absence (0) of diabetes.

### Key Insights:
1. **BMI**: The majority of people in the dataset have a BMI in the range of 25 to 35, which shows a significant correlation with diabetes.
2. **Age Distribution**: The dataset shows a higher number of individuals aged between 21 and 22, with a sharp drop in individuals aged between 47 and 66.
3. **Pregnancy and Diabetes**: The analysis indicates that individuals with zero pregnancies are more likely to have diabetes, with 1-time pregnancies also showing a notable association.
4. **Blood Pressure & Skin Thickness**: People with a blood pressure of 70 mm Hg and a skin thickness of 23 mm are more likely to be diagnosed with diabetes.
5. **Correlations**:
   - **BMI and Skin Thickness**: These features have a strong positive correlation (0.56), suggesting a link between body mass and skinfold thickness.
   - **Pregnancy and Age**: A moderate positive correlation (0.55), highlighting the importance of age and reproductive history in diabetes prediction.
   - **Insulin and Other Features**: Insulin levels have a negative correlation with pregnancies, blood pressure, and age, suggesting that insulin resistance may be more pronounced in individuals with certain characteristics.

### Visualizations:
- **BMI Distribution**: The BMI distribution ranges from 20 to 70, with a significant number of individuals falling between 25 and 35 BMI, which aligns with higher risk of diabetes.
- **Age vs. Diabetes Outcome**: The age feature reveals that most diabetes cases are seen in people aged 21-22.
- **Pregnancies and Diabetes Outcome**: The highest rates of diabetes are found in individuals who have had zero pregnancies, followed by those who have had 1 pregnancy.

### Conclusion:
This project provides valuable insights into the relationship between various health features and diabetes. The analysis identifies **BMI**, **Age**, **Pregnancies**, and **Skin Thickness** as significant indicators of diabetes risk. Although no predictive models were used in this phase, the statistical analysis and correlation evaluations pave the way for future model development aimed at predicting diabetes based on the identified features.

---
