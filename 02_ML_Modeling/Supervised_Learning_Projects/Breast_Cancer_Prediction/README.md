<h1> ♀️ Breast Cancer Prediction Model </h1>
A machine learning project focused on predicting whether a breast tumor is malignant or benign using classification models, feature engineering, and a well-known dataset.
<hr>
<h2> 📌 Project Overview </h2> 
This project follows a complete machine learning workflow to predict breast cancer diagnosis. Using a dataset from the sklearn Machine Learning Repository, I performed data preprocessing, feature standardization, logistic regression modeling, and performance evaluation. The goal was to identify key patterns and build a strong predictive model.
<hr>
<h2> 🧰 Tech Stack </h2> 
<ul>    
    <li> Language: Python </li>
    <li> Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn </li>
    <li> Environment: Jupyter Notebook / Google Colab </li>
</ul>
<hr>
<h2> 🔄 Workflow Summary </h2> 
<h3> 1. Data Collection: </h3>
The dataset was sourced from sklearn datasets. Each entry corresponds to a passenger aboard the Titanic. After importing the data, a dataframe was created for analysis.
<hr>
<h3> 2. Feature and Target Separation: </h3>
I separated the dataset into features (X) and the target (Y). This allowed me to focus on predicting the tumor’s diagnosis
<hr>
<h3> 3. Data Standardization: </h3>
I applied standard scaling to the feature set, ensuring all features had a mean of zero and standard deviation of one.
<hr>
<h3> 4. Model Training: </h3>
A logistic regression model was trained using the standardized data. I split the dataset into training and testing sets and evaluated the model’s performance.
<hr>
<h3> 5. Model Evaluation: </h3>
The model was evaluated using accuracy. It achieved 98% accuracy on both the training set and the test set. After hyperparameter tuning with grid search, the accuracy remained stable at 98%.
<hr>
<h2> 📈 Key Findings </h2> 
<li>The standardized features helped the model achieve high accuracy. </li> 
<li> Logistic regression effectively distinguished between malignant and benign tumors, maintaining strong performance. </li>
<hr>
