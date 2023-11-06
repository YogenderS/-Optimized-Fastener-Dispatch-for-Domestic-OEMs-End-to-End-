# -Optimized-Fastener-Dispatch-for-Domestic-OEMs-End-to-End-
# Problem Statement:
🚚 Optimize Dispatches: Streamline the dispatch process to ensure timely and cost-effective deliveries, reducing lead times and improving overall customer satisfaction.

💰 Reduce Cost of Poor Quality: Identify, track, and mitigate the costs associated with poor quality products, including defects, rejections, and rework.

🔍 Major Rejection and Rework Analysis: Identify the root causes of major rejections and rework in the manufacturing process, with the goal of reducing these occurrences and their associated costs.

📈 Sales Trend Analysis: Analyze sales data to understand the trends for both top and bottom customers, enabling better strategic decision-making and customer management.

🧩 Part Clustering for Sorting Cost Reduction: Develop a clustering system for the efficient sorting of a large number of parts, minimizing the costs and time associated with sorting and assembly processes.

By addressing these objectives simultaneously, the goal is to optimize the manufacturing and supply chain operations, reduce costs, and improve overall product quality and customer satisfaction.

# 🛠 Tools Used
# Tools used:

Google Colab (library: Seaborn, Matplotlib, Pandas, Numpy, sklearn and scipy)

Machine Learning Models: Kmeans and DBscan

Excel

# Documentation
# Python Analysis:-
# Table of Contents:
1️⃣ Import Libraries: 📚 Import essential Python libraries such as pandas, numpy, scikit-learn, and matplotlib.

2️⃣ Load Dataset: 📂 Load the dataset into a Pandas DataFrame, using functions like pd.read_excel().

3️⃣ Exploratory Data Analysis: 👁️ Examine the first few rows of the dataset using df.head() to get a sense of the data.

📊 Check data types, statistics, and summary statistics using functions like df.info(), df.describe().

📈 Visualize data with plots (histograms, scatter plots, etc.) to understand the distribution of variables using libraries like Matplotlib and Seaborn.

📊 Identify any trends, patterns, or outliers in the data.

4️⃣ Checking Null, Duplicate, Outliers Values, Cleaning Data, Removing Noise from Data: 🚫 Check for missing values using df.isnull().sum() and handle them by imputing or dropping rows/columns as needed.

♻️ Identify and handle duplicate values using df.duplicated() and df.drop_duplicates().

📈 Detect and address outliers using statistical methods or visualization techniques.

🧹 Clean and preprocess the data by handling categorical variables, scaling features, and addressing any data quality issues.

5️⃣ Feature Engineering and Building ML Models (KMeans & DBscan): 🛠️ Feature engineering involves creating new features or transforming existing ones to improve model performance.

# K-means Clustering vs. DBSCAN
In the field of unsupervised machine learning, there are various clustering algorithms available. Two popular methods are K-means clustering and DBSCAN (Density-Based Spatial Clustering of Applications with Noise). Let's compare and contrast these two clustering techniques.

# K-means Clustering
🔍 Type: Distance-based clustering

🎯 Every observation: Becomes a part of some cluster eventually

🔵 Cluster Shape: Forms clusters that have a shape of a hypersphere (a circle in 2D, a sphere in 3D, etc.)

🎯 Sensitivity to Outliers: Sensitive to outliers

🔢 Number of Clusters: Requires the number of clusters as input

# DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
🌐 Type: Density-based clustering

🎯 Every observation: Clearly separates outliers and clusters observations in high-density areas

🌀 Cluster Shape: Forms clusters that have an arbitrary shape or clusters within clusters

🟢 Sensitivity to Outliers: Robust to outliers

❓ Number of Clusters: Doesn’t require the number of clusters as input

In summary, K-means clustering is distance-based and requires specifying the number of clusters in advance. It forms clusters that are hyperspheres and is sensitive to outliers. On the other hand, DBSCAN is a density-based clustering method that doesn't require specifying the number of clusters, can identify clusters with arbitrary shapes, and is robust to outliers.

# 🔍 Insights and Recommendations:

# 🛠️ Insight 1: Major Rejection and Rework Causes

Major Rejection: The primary issue is the occurrence of cracks.
Major Rework: Non-uniform plating is a significant cause of rework.
# 📌 Recommendation 1: Address Root Causes

Implement measures to prevent crack formation and ensure uniform plating to reduce major rejection and rework.
# 🚀 Recommendation 2: Target 20-80 Rule

Focus on driving improvement projects for the 20% of parts responsible for 80% of the rejections to maximize impact and efficiency.
# 💰 Insight 2: Reduced Sorting Cost

Unnecessary sorting cost from the contractor has been successfully reduced from 3.9 lakhs/month to 1.8 lakhs/month.
# 📊 Recommendation 3: Cost Optimization

Continue efforts to minimize sorting costs by optimizing the sorting process and maintaining cost-effective contractor relationships.
# 📉 Insight 3: Reduction in Rejection

Rejection rates have been significantly reduced from 1975 kg/month to 375 kg/month.
# 🔧 Recommendation 4: Focus on Quality Control

Continue to prioritize quality control measures to further reduce rejection rates and enhance overall product quality.
# 📈 Conclusion:

The company has made substantial progress in reducing major rejections, rework, and sorting costs.
Continued efforts in addressing root causes, targeted projects, and cost optimization will further improve operational efficiency and product quality.

