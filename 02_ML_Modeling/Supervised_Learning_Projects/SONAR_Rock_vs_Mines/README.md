<h1> ⚓ SONAR: Rock vs Mine Prediction </h1>
A machine learning project focused on predicting sonar signals as either rocks or mines using logistic regression, built with data preprocessing and model evaluation.
<hr>
<h2> 📌 Project Overview </h2> 
This project implements a complete workflow to predict sonar signals. After loading the sonar dataset, I performed basic analysis, created features and targets, split the data, trained a logistic regression model, and evaluated its performance. The model showed strong prediction capabilities.
<hr>
<h2> 🧰 Tech Stack </h2> 
<ul>    
    <li> Language: Python </li>  
    <li> Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn </li>  
    <li> Environment: Jupyter Notebook / Google Colab </li>  
</ul>
<hr>
<h2> 🔄 Workflow Summary </h2> 
<h3> 1. Data Collection and Preprocessing: </h3>
I imported the required libraries and loaded the sonar dataset from a CSV file. After creating a copy of the data, I performed basic analysis: checking shape, data types, value counts, and computed means.
<h3> 2. Feature Preparation: </h3>
I created independent (X) and dependent (Y) variables. Then, I split the data into training and test sets.
<h3> 3. Model Training: </h3>
I used a logistic regression model from scikit-learn. After fitting the model on the training data, I evaluated it using accuracy.
<h3> 4. Model Evaluation: </h3>
The training accuracy was 88%, while the test accuracy was 76%. This shows a decent model fit with some generalization.
<h3> 5. Predictions on New Data: </h3>
I took random input data from the dataset, reshaped it, and applied the model. After prediction, the model correctly identified the classes, showing strong efficiency.
<hr>
<h2> 📈 Key Findings </h2> 
<ul>    
    <li> Logistic regression performed well, with 88% training accuracy and 76% test accuracy. </li>  
    <li> The model successfully differentiated between sonar signals of rocks and mines. </li>  
    <li> Predictions on new data matched expectations, confirming the model’s efficiency. </li>  
</ul>
