🧠 Diabetes Prediction using Machine Learning in R

This project applies various machine learning algorithms to predict diabetes risk using health metrics. It includes exploratory data analysis, data cleaning, visualizations, and performance evaluation of models like KNN. The project was done using the R programming language.

📁 Dataset Features
The dataset contains the following attributes:
- `hdl_chol` — Good cholesterol
- `systolic_bp`, `diastolic_bp` — Blood pressure readings
- `diabetes` — Target variable

📊 Exploratory Data Analysis (EDA)

Bar Plots: Gender, diabetes status
Histograms: Cholesterol, glucose, BMI, age, blood pressure, etc.
Boxplots: Outlier detection in key metrics
Transformations: Cleaned BMI (converted from text to numeric)
⚙️ Model Building
The dataset was split into 80% training and 20% testing sets.

K-Nearest Neighbors (KNN) was used for classification, with normalization applied to numeric features.

✅ Model Accuracy:92.34%
