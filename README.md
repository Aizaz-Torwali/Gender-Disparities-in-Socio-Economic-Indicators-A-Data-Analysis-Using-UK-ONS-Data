# Gender-Disparities-in-Socio-Economic-Indicators-A-Data-Analysis-Using-UK-ONS-Data
Analyzes gender-based socio-economic disparities in the UK using ONS data. Includes data cleaning, clustering (KMeans &amp; Hierarchical), PCA, and Random Forest modeling using Python. Focus areas: economic activity, education, marital status, ethnicity, and unpaid care.
🎯 Objectives
Examine gender-based differences in socio-economic factors
Identify patterns using clustering methods
Predict socio-economic classifications using machine learning
Visualize trends and disparities through PCA and graphs
🧩 Dataset
Source: UK Office for National Statistics (ONS)
Variables Used:
Gender identity
Economic activity status
Marital and civil partnership status
Highest level of qualification
Ethnic group
Unpaid care
🛠️ Tools & Libraries
pandas, numpy – data handling
matplotlib, seaborn – visualization
scikit-learn – clustering (KMeans, Hierarchical), PCA, Random Forest
missingno – missing value visualization (optional)
🔍 Methods
Data Cleaning & Preprocessing
Handled missing values and irrelevant fields
Label Encoding & Transformation
Converted codes into descriptive labels
Clustering
KMeans clustering with Elbow method
Hierarchical clustering with Ward's linkage
Dimensionality Reduction
PCA for cluster visualization
Predictive Modeling
Random Forest to classify socio-economic outcomes
📊 Results
Identified four distinct socio-economic clusters
Visualized trends across gender in economic activity, education, etc.
Random Forest achieved high accuracy in classification tasks
PCA provided insightful visual separations across gender and socio-economic features
