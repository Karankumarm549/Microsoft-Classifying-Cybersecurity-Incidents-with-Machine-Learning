# Microsoft-Classifying-Cybersecurity-Incidents-with-Machine-Learning

# Introduction:
Cybersecurity incidents are becoming more frequent and sophisticated. The goal of this project is to classify cybersecurity incidents into specific types using machine learning models. This classification helps enhance the efficiency of Security Operation Centers (SOCs) by enabling faster incident detection and response.

# Objective:
- Develop a machine learning model to classify cybersecurity incidents based on a labeled dataset.
- Optimize for imbalanced data by applying data balancing techniques like SMOTE.
- Deploy the model using a Streamlit app for easy accessibility and real-time predictions.

#  Dataset Overview:
- **Cybersecurity Incidents Dataset**: The dataset contains several features, such as incident categories, source IP, destination IP, protocols, timestamps, and other network-related data that capture incident patterns.
- **Target Variable**: incident_category, which includes categories such as malware, phishing, and network attacks.

# Business Use Cases:
- Incident Response: Enable SOC teams to classify incidents quickly and respond effectively.
- Threat Intelligence: Identify trends and common attack types over time.
- Automated Reporting: Use predictions to generate real-time incident reports.
# Model Comparison with Accuracy Score:
The table below provides an overview of the performance of various models, summarized through their Accuracy scores. The comparison highlights the ranking and effectiveness of each model in predicting sales.
| **Model Name**          | **Accuracy Score** |
|--------------------------|--------------------|
| Logistic Regression      | 0.6503            |
| Decision Tree            | 0.6737            |
| Random Forest            | 0.6741            |
| Gradient Boosting        | 0.6712            |
| K-Nearest Neighbors (KNN)| 0.6694            |
| Support Vector Machine (SVM)| **0.6952**     |

# Result:
