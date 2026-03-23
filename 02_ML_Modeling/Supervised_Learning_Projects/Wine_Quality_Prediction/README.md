<h1> 🍇 Wine Quality Prediction </h1>
A machine learning project focused on predicting wine quality using a random forest classifier, feature engineering, and data analysis from a Kaggle dataset.
<hr>
<h2> 📌 Project Overview </h2> 
This project builds a complete machine learning workflow to predict wine quality. After loading a Kaggle dataset, I performed basic analysis, visualizations, and statistical checks. Then, I trained a random forest classifier and evaluated its performance, achieving 92% accuracy.
<hr>
<h2> 🧰 Tech Stack </h2> 
<ul>    
    <li> Language: Python </li>  
    <li> Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn </li>  
    <li> Environment: Jupyter Notebook / Google Colab </li>  
</ul>
<hr>
<h2> 🔄 Workflow Summary </h2> 
<h3> 1. Data Collection: </h3>
The dataset was sourced from Kaggle. After loading it, I performed basic analysis by checking the shape, missing values, and summary statistics.
<h3> 2. Data Visualization: </h3>
I visualized the data by plotting the number of wines for each quality using a catplot. Then, I plotted volatile acidity versus quality (inverse relation) and citric acid versus quality (direct relation). I also checked correlations between numeric features and plotted a heatmap to observe positive and negative relationships.
<h3> 3. Data Processing: </h3>
I separated the data into features (X) and target (Y). Then, I split the data into training and testing sets using train-test split.
<h3> 4. Model Selection and Training: </h3>
I chose a random forest classifier from scikit-learn. After fitting the model on the training set, I evaluated it using the accuracy score from metrics.
<h3> 5. Model Evaluation: </h3>
The model achieved an accuracy of 92%, which indicates strong performance in predicting wine quality.
<hr>
<h2> 📈 Key Findings </h2> 
<ul>    
    <li> The distribution of wine qualities showed that certain qualities are more frequent. </li>  
    <li> Volatile acidity had an inverse relation to quality, while citric acid had a direct relation </li>  
    <li> Random forest achieved a high accuracy of 92%, showing its effectiveness for this classification task. </li>  
</ul>
