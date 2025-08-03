# Predictive-Maintenance

# 🔧 Predictive Maintenance of Industrial Machinery

## 🚀 Problem Statement

Develop a predictive maintenance model for a fleet of industrial machines to anticipate failures before they occur. Using real-time sensor data, this model predicts the type of failure (e.g., tool wear, heat dissipation, power failure), enabling proactive maintenance and reducing downtime.

## 💡 Proposed Solution

A machine learning classification model was built using Python and trained on a Kaggle dataset. The model identifies patterns in sensor data leading to machine failures. It leverages Random Forest for high accuracy and integrates with IBM Cloud Watsonx.ai Studio for scalable deployment.

## 📁 Dataset Description

Dataset Source: [Kaggle – Machine Predictive Maintenance Classification](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)

| Column Name               | Description                              |
|---------------------------|------------------------------------------|
| UDI                       | Unique identifier                        |
| Product ID                | Machine product ID                       |
| Type                      | Type of machine                          |
| Air temperature [K]       | Sensor reading                           |
| Process temperature [K]   | Sensor reading                           |
| Rotational speed [rpm]    | Machine RPM                              |
| Torque [Nm]               | Torque applied                           |
| Tool wear [min]           | Wear time of tool                        |
| Target                    | Failure occurred (0 = No, 1 = Yes)       |
| Failure Type              | Type of failure (5 classes + 0 for None) |

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Random Forest, preprocessing, evaluation)
- Imbalanced-learn (SMOTE)
- IBM Watsonx.ai Studio
- Jupyter Notebook
- IBM Cloud API Keys

## 📊 Model Summary

- Model Used: Random Forest Classifier  
- Accuracy Achieved: 99.28%  
- Evaluation: Precision, Recall, F1-Score for all 6 classes  
- Balanced Dataset: SMOTE used to balance class distribution

## 📡 IBM Watsonx.ai Integration

- Model developed and executed using Jupyter Notebook in IBM Watsonx.ai Studio  
- API Keys used to authenticate and run notebooks in IBM Cloud environment  
- Scalable for future deployment and integration into real-time systems

## 🎯 End Users

- Maintenance Engineers  
- Factory Managers  
- Operations Teams  
- IoT Solution Providers  
- Industrial Automation Companies

## 🌟 Wow Factors

- Predicts specific types of machine failures, not just binary outcomes  
- High accuracy and reliability for industrial use  
- Integrates with IBM Watsonx.ai for cloud-scale performance  

## 🔍 Unique Features

- Real-time failure prediction based on sensor metrics  
- Handles imbalanced data with SMOTE  
- Robust model performance across all failure categories  
- Ready for deployment as API/microservice  

## 🔮 Future Scope

1. Integrate live data streaming via IoT devices  
2. Deploy model as REST API in IBM Cloud  
3. Experiment with LSTM/CNN models for time-series  
4. Build visualization dashboards for operators  
5. Enable real-time alert systems for maintenance teams  
6. Extend to other industrial domains (e.g., aerospace, oil & gas)

## ✅ Conclusion

- Achieved excellent model performance in predicting failure types  
- Ready for real-world industrial use with IBM Watsonx.ai  
- Proactively minimizes machine downtime and reduces operational costs

## 📌 How to Run

1. Clone the repository or upload `.ipynb` to IBM Watsonx.ai Studio  
2. Upload dataset (`.csv`) to your IBM Cloud project  
3. Run all cells in Jupyter Notebook  
4. Authenticate using your IBM Cloud API key  
5. View results, classification metrics, and save/export the model

## 🧾 License

This project is open-source for academic and demonstration purposes.
