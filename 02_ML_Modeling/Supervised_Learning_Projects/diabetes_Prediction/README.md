<h1> 🟦 Diabetes Prediction with SVM </h1>
A machine learning project focused on predicting diabetes outcomes using a support vector machine (SVM), with data preprocessing and model evaluation.
<hr>
<h2> 📌 Project Overview </h2> 
This project uses an SVM to predict diabetes from a Kaggle dataset. After loading the data, I performed basic analysis, filled missing values, scaled the features, and trained the SVM model. The model was evaluated on both training and test sets, achieving strong accuracy.
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
I imported all necessary libraries (numpy, pandas) and loaded the dataset from Kaggle. I performed basic analysis: checked the shape, data types, null values, and computed means.
<h3> 2. Feature Scaling: </h3>
I created the independent (X) and dependent (Y) variables. Then, I applied a standard scaler to normalize the features.
<h3> 3. Model Selection and Training: </h3>
I imported a linear model (SVM) from scikit-learn and fitted it on the scaled data. Then, I split the data using train-test split.
<h3> 4. Model Evaluation: </h3>
I evaluated accuracy using accuracy_score. The training accuracy was 78%, and the test accuracy was 77%, which is quite good.
<h3> 5. Predictions on New Data: </h3>
I selected random data from the dataset, reshaped it, and applied the model. The predictions were accurate, confirming that the model performs well on new inputs.
<hr>
<h2> 📈 Key Findings </h2> 
<ul>    
    <li> The SVM model achieved 78% accuracy on training data and 77% on test data, indicating a good fit. </li>  
    <li> The model accurately predicted diabetes outcomes on new, unseen data. </li>  
    <li> Data scaling and preprocessing improved model performance, ensuring stability across sets. </li>  
</ul>
<hr>
