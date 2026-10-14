📊 Facebook Live K-Means Clustering Dashboard

📌 Project Overview

The Facebook Live K-Means Clustering Dashboard is a machine learning project that uses the K-Means Clustering algorithm to group 
Facebook Live posts based on their features.

The project provides an interactive dashboard built using Streamlit to visualize cluster distributions, analyze status types, explore numerical features, 
and predict the cluster of a new record.

🎯 Objectives

Analyze Facebook Live post data.

Group similar records using K-Means clustering.

Visualize cluster distributions and percentages.

Compare status types across different clusters.

Predict the cluster for new input records.

Provide an interactive dashboard for data analysis.

🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Streamlit

Matplotlib

Joblib

Jupyter Notebook

🤖 Machine Learning Algorithm

K-Means Clustering

Number of clusters: 4

Random state: 0

Feature scaling is applied before clustering.

Label encoding is used to convert categorical status types into numerical values.

📊 Dashboard Features

Total records and cluster count.

Cluster distribution bar chart.

Cluster percentage summary.

Status type distribution.

Numerical feature summary.

Interactive cluster filtering.

Prediction of clusters for new records.

Filtered dataset display.

📁 Project Structure

facebook-live-kmeans-dashboard/
│
├── app.py
├── Live.csv
├── kmeans_clustering_artifacts.pkl
├── Day 71_K means Clustering_Project.ipynb
├── requirements.txt
└── README.md

Note: Keep Live.csv and kmeans_clustering_artifacts.pkl in the same directory as app.py. The notebook is included for reference.

⚙️ Installation and Setup

1. Clone the Repository

git clone https://github.com/YOUR-USERNAME/facebook-live-kmeans-dashboard.git

2. Open the Project Folder

cd facebook-live-kmeans-dashboard

3. Install Dependencies

pip install streamlit pandas numpy scikit-learn joblib matplotlib

4. Run the Application

streamlit run app.py

The dashboard will open in your web browser, usually at:

http://localhost:8501

📈 Expected Output

The application displays an interactive dashboard with:

Cluster distribution visualizations.

Cluster percentage tables.

Status type comparisons.

Numerical statistics.

New-record cluster predictions.

🔮 Future Scope

Add real-time Facebook engagement data.

Improve cluster interpretation and visualization.

Deploy the dashboard to a cloud platform.

Add more interactive analytics and reporting features.

👩‍💻 Author

Apeksha Dhokare

📄 License

This project is intended for educational and learning purposes.
