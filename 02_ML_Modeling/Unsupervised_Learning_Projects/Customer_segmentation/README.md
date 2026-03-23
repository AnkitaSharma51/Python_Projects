<h1> 🟪 K-Means Customer Segmentation Model </h1>
A machine learning project focused on grouping customers into segments using the K-Means clustering algorithm, feature engineering, and data from a Kaggle dataset.
<hr>
<h2> 📌 Project Overview </h2> 
This project builds a complete end-to-end machine learning workflow for customer segmentation using K-Means. It includes data loading, exploratory data analysis, feature scaling, cluster optimization, and model visualization. The goal is to identify distinct customer groups based on their behavior.
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
The dataset was sourced from Kaggle. It was a CSV file containing customer attributes. After loading the data, I created a copy for analysis.
<hr>
<h3> 2. Data Analysis: </h3>
I performed basic analysis, checking the shape, info, and identifying missing values.
<hr>
<h3> 3. Feature Preparation: </h3>
I separated the data into features (X) and the target (Y). Then, I calculated the number of clusters using the within-cluster sum of squares (WCSS) by looping over different cluster counts.
<hr>
<h3> 4. Optimal Cluster Selection: </h3>
I plotted the elbow graph and determined that the optimal number of clusters was 5.
<hr>
<h3> 5. Model Training: </h3>
I trained the KMeans model with the chosen number of clusters and visualized the results by plotting the clusters and their centroids using matplotlib.
<hr>
<h2> 📈 Key Findings </h2> 
<ul>    
    <li> After analyzing the elbow plot, the optimal number of clusters was identified as 5. </li>  
    <li> The KMeans model successfully grouped customers into distinct segments, each with different behavior patterns. </li>  
</ul>
<hr>
