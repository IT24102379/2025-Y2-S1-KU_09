# 2025-Y2-S1-KU-09-
 **Overview of the project**
 
 This project involves the use of machine learning (ML) to predict and improve sleep quality based on lifestyle, health, and demographic factors. Sleep quality is a significant predictor of well-being, which influences physical and emotional stability. Physical activity, BMI, blood pressure, heart rate, levels of stress, and daily activities all play significant roles in influencing sleep patterns. The project addresses real public health issues such as insomnia, sleep apnea, obesity, and chronic illness, which are largely related to abandoned lifestyle factors.
The field of application is lifestyle and health-focused sleep disorder testing. By analyzing correlations in the data, the ML model is able to identify risk factors for bad sleep, enable early diagnosis, and provide personalized recommendations. This would be integrated into wellness apps, mHealth platforms, or company wellness initiatives to enhance well-being and reduce healthcare costs. The variables included in the data are age, gender, occupation, stress, physical activity, number of working hours, BMI, blood pressure, heart rate, and sleep duration, with the variable of interest being sleep quality (score categorization).

**Dataset Details**
The project justifies the choice of the dataset for the corresponding AI/ML component (sleep quality prediction) due to its size (over 15,000 records), variety of relevant features (e.g., age, BMI, stress level, physical activity, heart rate, sleep duration), and organized structure, minimizing preprocessing needs. Data is sourced from Kaggle (URL: [https://www.kaggle.com/imaginecoder/sleep-activity-level-bmi](https://www.kaggle.com/datasets/imaginativecoder/sleep-health-data-sampled)) and includes significant variables such as Sleep Duration, Physical Activity Level, Heart Rate, Blood Pressure, and BMI Category, with Quality of Sleep as the target for predictive modeling


**Group Member Role**
 Mohamed M. U - IT2410050: 
 Handles Data Cleaning (Part 1 – Missing & Duplicates), including managing missing values, removing duplicates, and fixing invalid entries.
 
 Kariyasam G.K.A.L - IT24100103: 
 Responsible for Data Cleaning (Part 2 – Outliers & Consistency Check), detecting outliers, ensuring data consistency, and correcting formatting.
 
 Dhararathne S.P.H. P - IT24101328:
 Manages Data Preprocessing – Transformation & Encoding, applying scaling/normalization and encoding categorical variables.
 
 Ekanayake E.M.R. T - IT24102102:
 Oversees Feature Engineering & Data Splitting, creating new features, reducing dimensions if needed (e.g., PCA), and splitting data into train/test sets.
 
 Abeykoon D.M.D. N - IT24102379:
 Conducts Exploratory Data Analysis (EDA), generating descriptive statistics, analyzing correlations, and detecting trends/patterns.
 
 Disanayake M.A.T. D - IT24100927:
 Focuses on Visualization, creating plots like histograms, scatter plots, heatmaps, and final charts for presentation.

 **How to Run the Code**
!pip install pandas numpy seaborn matplotlib category_encoders scikit-learn scipy

**Required Libraries**
 pandas (data manipulation)
numpy (numerical operations)
seaborn (visualization)
matplotlib (plotting)
category_encoders (categorical encoding)
scikit-learn (preprocessing, splitting, modeling)
scipy.stats (statistical transformations)
