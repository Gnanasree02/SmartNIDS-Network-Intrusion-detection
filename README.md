# 🚨 SmartNIDS – Hybrid Network Intrusion Detection System

## 📌 Overview
SmartNIDS is a Machine Learning-based **Network Intrusion Detection System (NIDS)** designed to detect and classify malicious network traffic in real time.

It uses a **hybrid model combining Random Forest and XGBoost** to improve detection accuracy and provide insights such as attack severity, confidence score, and repeated attack patterns.

The system also features a **web-based dashboard** for monitoring and visualization.

---

## 🎯 Features
- Hybrid prediction using Random Forest & XGBoost  
- Real-time intrusion detection  
- Attack severity classification (Low / Medium / High)  
- Detection of repeated attack patterns  
- Confidence score generation  
- Interactive dashboard visualization  
- Log storage in MSSQL database  
- User-friendly Flask web interface  

---

## 🛠️ Tech Stack

**Frontend**
- HTML, CSS, JavaScript  
- Chart.js  

**Backend**
- Flask (Python)  

**Machine Learning**
- Random Forest  
- XGBoost  

**Database**
- Microsoft SQL Server (MSSQL)  

**Libraries**
- pandas  
- numpy  
- scikit-learn  
- xgboost  
- joblib  

---

## 📊 Dataset
- NSL-KDD Dataset  
- Standard dataset for intrusion detection systems  
- Contains 41 features for network traffic classification  

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Gnanasree02/SmartNIDS-Network-Intrusion-detection.git
cd SmartNIDS-Network-Intrusion-detection
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Application
```bash
python app.py
```

### 4. Open in Browser
```
http://127.0.0.1:5000/
```

---

## 🧠 Working of the System
1. Input network traffic data (41 features)  
2. Data preprocessing and scaling  
3. Prediction using:
   - Random Forest  
   - XGBoost  
4. Hybrid logic combines results  
5. Output includes:
   - Attack type  
   - Severity level  
   - Confidence score  
6. Results displayed on dashboard  
7. Logs stored in database  

---

## 📁 Project Structure
```
SmartNIDS/
│── static/              # Frontend files (CSS, JS)
│── templates/           # HTML pages
│── models/              # Trained ML models
│── dataset/             # NSL-KDD dataset
│── app.py               # Main Flask application
│── requirements.txt     # Dependencies
│── README.md            # Documentation
```

---

## 📊 Output
- Real-time attack detection  
- Severity-based alerts  
- Graphical visualization using charts  
- Stored logs for future analysis  

---

## 🚀 Future Enhancements
- Real-time packet capture integration  
- Cloud deployment (AWS / Azure)  
- Deep Learning models (LSTM, CNN)  
- Advanced analytics dashboard  
- API integration for external systems  

---

## 👩‍💻 Author
**Gnanasree Arigala**  
B.Tech Computer Science Engineering  

---

## 📜 License
This project is developed for academic and research purposes.
