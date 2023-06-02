# Heart-Disease-Analysis

The Heart Disease dataset is a collection of medical data for patients with and without heart disease. It consists of 918 rows and 12 columns. The dataset provides information about the patients' age, sex, chest pain type, resting blood pressure, serum cholesterol level, fasting blood sugar, resting electrocardiogram results, maximum heart rate achieved, exercise-induced angina, oldpeak (ST depression), the slope of the peak exercise ST segment, and heart disease diagnosis.

Age: Measured in years.
Sex: M for male, F for female.
Chest Pain Type: Categorized as Typical Angina, Atypical Angina, Non-Anginal Pain, or Asymptomatic.
Resting Blood Pressure: Measured in mm Hg.
Serum Cholesterol: Measured in mm/dl.
Fasting Blood Sugar: 1 if fasting blood sugar is greater than 120 mg/dl, 0 otherwise.
Resting Electrocardiogram Results: Categorized as Normal, showing ST-T wave abnormality, or showing probable or definite left ventricular hypertrophy.
Maximum Heart Rate Achieved: Numeric value between 60 and 202.
Exercise-Induced Angina: Y for yes, N for no.
Oldpeak: Numeric value measured in depression.
Slope of Peak Exercise ST Segment: Categorized as Up, Flat, or Down.
Heart Disease Diagnosis: 1 for patients diagnosed with heart disease, 0 for patients with a normal diagnosis.
The dataset contains no missing values and is suitable for exploratory data analysis and machine learning modeling. It underwent preprocessing steps including count plot, histogram plot, null value check, data scaling, label encoding, feature correlation analysis, and modeling.

Several machine learning models were trained on the dataset, including Logistic Regression, SVM, SVM Kernel rbf, Decision Tree Classifier, Random Forest, and KNN. The evaluation results showed accuracy ranging from 83% to 88%, with the Random Forest and KNN models achieving the highest accuracy of 88%. The recall rate ranged from 82% to 88%, and the precision rate ranged from 88% to 92%. The F1-Score, a measure of the models' overall performance, ranged from 85% to 89%.

These results demonstrate the accuracy of machine learning models in predicting the presence of heart disease based on patient attributes. The Random Forest and KNN models performed exceptionally well on this dataset, providing valuable insights for healthcare professionals in patient diagnosis and treatment decisions. Further studies on larger and more diverse datasets are warranted to validate these findings.
