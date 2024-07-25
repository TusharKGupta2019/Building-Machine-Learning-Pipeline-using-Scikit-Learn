# Building-Machine-Learning-Pipeline-using-Scikit-Learn

Building Machine Learning Pipeline using Scikit-Learn



In this project, I learned how to effectively build a machine learning pipeline using Scikit-Learn, which significantly enhanced my understanding of data preprocessing, model training, and evaluation.



Key Highlights:



Data Preparation: I started by importing essential libraries such as Pandas and NumPy for data manipulation. After loading the dataset, I dropped unnecessary columns and handled missing values using the SimpleImputer.



Feature Engineering: I implemented both numerical and categorical pipelines. The numerical pipeline included steps for imputation, feature scaling with MinMaxScaler, and dimensionality reduction using PCA. For categorical data, I used OneHotEncoder to convert categorical variables into a format suitable for model training.



Pipeline Integration: By utilizing ColumnTransformer, I combined both pipelines into a single preprocessing step, ensuring a seamless workflow.



Model Selection and Training: I chose a RandomForestClassifier for the classification task. The dataset was split into training and testing sets, allowing for accurate model evaluation.



Hyperparameter Tuning: To optimize the model's performance, I employed GridSearchCV to fine-tune hyperparameters, which led to a model accuracy of 86.25% on the test set.



This project not only solidified my technical skills but also highlighted the importance of a structured approach in machine learning. 




