# 🚨 911 Calls Data Analysis & Prediction (Capstone Project)

This project analyzes **911 emergency call data** from Kaggle to uncover patterns, trends, and insights that can help improve emergency response planning. Alongside **Exploratory Data Analysis (EDA)**, the project also applies **Machine Learning models** to predict emergency categories.

---

## 📌 Dataset Description  
The dataset contains details of emergency calls with the following fields:
- **lat, lng** – Latitude & Longitude  
- **desc** – Description of the emergency call  
- **zip** – Zipcode  
- **title** – Emergency title/category  
- **timeStamp** – Date & time of the call (YYYY-MM-DD HH:MM:SS)  
- **twp** – Township  
- **addr** – Address  
- **e** – Dummy variable (always 1)  

Dataset link: [911 Calls Dataset on Kaggle](https://www.kaggle.com/mchirico/philadelphia-crime-data)

---

## 🎯 Objectives  
- Perform **data cleaning & preprocessing**  
- Identify **most common call types & locations**  
- Analyze **time-based trends** (daily/weekly/hourly)  
- Conduct **geospatial analysis** for emergency hotspots  
- Build **machine learning models** to predict call category  

---

## 🛠️ Tools & Libraries  
- Python (Pandas, NumPy)  
- Matplotlib, Seaborn (Visualization)  
- Scikit-learn (Machine Learning)  
- Jupyter Notebook  

---

## 📊 Key Insights  
- **Traffic** and **EMS (Medical)** were the most frequent call categories.  
- Strong **time-based patterns** (rush hours & weekends had higher call volume).  
- **Geospatial hotspots** identified for traffic and fire-related emergencies.  
- ML classification models achieved **good accuracy** in predicting call categories.  

---

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/oyerahul/911-calls-capstone.git
   cd 911-calls-capstone

