# 🕵️ Anomaly Detection in Transactions using Python

This project demonstrates how to detect anomalies in financial transactions using **Machine Learning** techniques, particularly the **Isolation Forest** algorithm. It identifies unusual transaction patterns that could indicate fraud or irregular behavior.

---

## 📌 Features

- Exploratory Data Analysis (EDA) and visualization of transaction patterns
- Manual outlier detection using statistical thresholds
- Machine Learning-based anomaly detection using **Isolation Forest**
- User input interface for real-time anomaly prediction
- Evaluation using classification metrics
- Visualization of anomalies with scatter plots and histograms

---

## 🧠 Tech Stack

- Python (Pandas, NumPy, Scikit-learn)
- Plotly (for interactive visualizations)
- Isolation Forest (for unsupervised anomaly detection)

---

## 📁 Dataset Overview

The dataset contains synthetic but realistic transaction data with the following features:

| Feature | Description |
|---------|-------------|
| `Transaction_ID` | Unique identifier for each transaction |
| `Transaction_Amount` | The amount involved in the transaction |
| `Transaction_Volume` | Number of items/actions in the transaction |
| `Average_Transaction_Amount` | Historical average amount per transaction |
| `Frequency_of_Transactions` | How often transactions occur |
| `Time_Since_Last_Transaction` | Time gap since previous transaction |
| `Day_of_Week`, `Time_of_Day` | Temporal context |
| `Age`, `Gender`, `Income` | User demographic data |
| `Account_Type` | Type of account (e.g., savings, current) |

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/arn897/Anomaly-Detection-Transactions-using-Isolation-Forest.git
cd Anomalies-Detection-in-Transactions-using-Isolation-Forest

Install dependencies
pip install -r requirements.txt


Sample Test

Enter the value for 'Transaction_Amount': 10000
Enter the value for 'Average_Transaction_Amount': 900
Enter the value for 'Frequency_of_Transactions': 6

output
⚠️ Anomaly detected: This transaction is flagged as an anomaly.


📊 Results
Achieved 100% precision/recall on the test set using Isolation Forest (with contamination=0.02)

Detected rare patterns such as unusually high transaction values or low-frequency spikes


📌 Future Improvements
Add scaling and PCA visualization

Deploy using Streamlit for real-time web interface

Integrate alerts or logs to external services (Slack, Email, etc.)

👨‍💻 Author
Arnav Rana
