# ✈️ SkyIntel – Flight Delay Intelligence Platform

SkyIntel is an AI-powered flight delay intelligence platform that predicts flight delays, analyzes airline and airport performance, recommends optimal departure windows, and provides explainable machine learning insights for operational decision-making.

Built using historical flight data (5.2M+ flights), SkyIntel enables airlines, operations teams, and travelers to minimize delays through predictive analytics and interactive dashboards.

---

## 🚀 Features

### 🔹 Flight Delay Prediction
- Predict delay probability for any flight
- Expected delay estimation
- Risk classification (Low / Medium / High)
- Explainable AI using feature importance (SHAP)

### 🔹 Compare Flight Scenarios
- Compare two different flight schedules
- Side-by-side delay probability
- Expected delay comparison
- Risk reduction summary
- Best departure recommendation

### 🔹 Smart Departure Recommendations
- Finds lowest-risk departure windows
- Ranks departure hours by delay probability
- Uses predictions across all 24 hours × 7 days

### 🔹 Airline Analytics
- Airline rankings
- Delay rate analysis
- Average delay comparison
- Monthly airline trends

### 🔹 Airport Analytics
- Airport delay statistics
- Airport performance comparison
- Historical delay trends

### 🔹 Route Analytics
- Highest-risk routes
- Route delay scores
- Historical route performance
- Route trend visualization

### 🔹 Model Insights
- Model evaluation metrics
- Feature importance
- Confusion Matrix
- ROC Curve
- Performance over time

### 🔹 Interactive Dashboard
- Live operational KPIs
- Delay trends
- Top delayed airlines
- Top delayed airports
- Real-time monitoring

---

# 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Recharts
- Lucide Icons

### Backend
- Python
- Flask

### Machine Learning
- XGBoost
- Scikit-Learn
- SHAP
- Pandas
- NumPy

### Dataset
- US Flight Delay Dataset
- 5.2 Million Historical Flights

---

# 📊 Machine Learning Pipeline

1. Data Cleaning
2. Feature Engineering
3. Encoding & Scaling
4. Model Training
5. Hyperparameter Tuning
6. Prediction API
7. SHAP Explainability
8. Dashboard Visualization

---

# 📈 Prediction Features

The model uses features including:

- Airline
- Origin Airport
- Destination Airport
- Scheduled Departure Time
- Day of Week
- Month
- Route Historical Delay
- Airline Historical Delay
- Airport Delay Rate
- Distance

---

# 📊 Model Performance

| Metric | Score |
|---------|-------|
| Accuracy | 63.6% |
| Precision | 28.6% |
| Recall | 66.5% |
| F1 Score | 40.0% |
| ROC-AUC | 0.704 |

---

# 📂 Project Structure

```text
SkyIntel/
│
├── backend/
│   ├── app.py
│   ├── model.pkl
│   ├── routes/
│   └── utils/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── charts/
│   └── assets/
│
├── dataset/
│
├── notebooks/
│
├── screenshots/
│
└── README.md
```

---

# 🎯 Modules

- Dashboard
- Flight Predictor
- Compare Scenarios
- Recommendations
- Airline Analytics
- Airport Analytics
- Route Analytics
- Model Insights
- Settings

---

# 📷 Application Screenshots

## 🏠 Dashboard

![Dashboard](screenshots/Dashboard-—-SkyIntel-Flight-Delay-Intelligence.png)

---

## ✈️ Flight Predictor

![Flight Predictor](screenshots/Flight-Predictor-—-SkyIntel.png)

---

## ⚖️ Compare Scenarios

![Compare Scenarios](screenshots/Compare-Scenarios-—-SkyIntel.png)

---

## 💡 Recommendations

![Recommendations](screenshots/Recommendations-—-SkyIntel.png)

---

## ✈️ Airline Analytics

![Airline Analytics](screenshots/Airline-Analytics-—-SkyIntel(1).png)

---

## 🛫 Airport Analytics

> *(Add Airport Analytics screenshot here.)*

```md
![Airport Analytics](screenshots/Airport-Analytics.png)
```

---

## 🛣️ Route Analytics

![Route Analytics](screenshots/Route-Analytics-—-SkyIntel.png)

---

## 🧠 Model Insights

![Model Insights](screenshots/Model-Insights-—-SkyIntel.png)

---

## ⚙️ Settings

![Settings](screenshots/Settings-—-SkyIntel.png)

---

# 🔮 Future Improvements

- Live Flight API Integration
- Weather-based delay prediction
- Aircraft-level analytics
- Crew scheduling optimization
- Delay cause classification
- Multi-airport comparisons
- Real-time streaming dashboard
- Flight notification system
- Mobile application
- Cloud deployment with CI/CD

---

# 📄 License

This project is developed for educational and research purposes.

---

# 👨‍💻 Author

**Ashish Singh**

Software Engineer • IIT Delhi Graduate

AI | Machine Learning | Full Stack Development | Data Analytics
