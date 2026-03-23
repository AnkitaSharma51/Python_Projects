<h1> 🚢 Titanic Survival Model </h1>
A machine learning project focused on predicting passenger survival on the Titanic using classification models, feature engineering, and demographic and travel-related data.
<hr>
<h2> 📌 Project Overview </h2> 
This project builds a complete end-to-end machine learning workflow for predicting passenger survival on the Titanic, including data cleaning, exploratory data analysis, feature engineering, model training, and performance evaluation. The goal is to understand the key factors influencing survival and develop a robust classification model with strong predictive accuracy.
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
The dataset was sourced from Kaggle’s Titanic competition. It includes passenger details such as age, class, gender, fare, and cabin information. Each entry corresponds to a passenger aboard the Titanic, along with a binary label indicating survival.
<hr>
<h3> 2. Data Preprocessing: </h3>
Missing values in the age feature were addressed by imputing class-specific medians. For each passenger class, the missing age values were replaced by the median age of that class. Additionally, categorical variables such as sex, class, and embarked were converted into numerical form using one-hot encoding.
<hr>
<h3> 3. Exploratory Data Analysis (EDA): </h3>
The EDA phase involved visualizing relationships between key features and survival rates. For example, we plotted age distributions by class and gender, examined survival rates across different ticket classes, and used heatmaps to identify correlations between features and survival.
<hr>
<h3> 4. Feature Engineering: </h3>
Although no entirely new features were created, we engineered the data by handling missing values systematically. The age imputations ensured that each class was treated independently. These refined features, along with encoded categorical variables, provided a solid foundation for modeling.
<hr>
<h3> 5. Modeling and Evaluation: </h3>
We applied a logistic regression model to predict survival. The dataset was split into training and testing sets. Model performance was evaluated using accuracy as the primary metric. Based on these results, we generated predictions on unseen data.
<hr>
<h2> 📈 Key Findings </h2> 
<ul>    
    <li> After class-specific median imputation, survival rates still differed significantly by class, with first-class passengers having the highest survival. </li>
    <li> EDA showed that age was a key factor; children were far more likely to survive than adults, and women also had a higher survival rate compared to men. </li>
</ul>
<hr>















