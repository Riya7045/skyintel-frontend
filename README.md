# ✈️ SkyIntel – AI-Powered Flight Delay Intelligence Platform

SkyIntel is an AI-powered aviation analytics platform that predicts flight delays, benchmarks airline and airport performance, recommends optimal departure windows, and provides explainable machine learning insights for operational decision-making.

Built using historical flight data (5.2M+ flights), SkyIntel enables airlines, operations teams, and travelers to make data-driven decisions through predictive analytics and interactive dashboards.

> **Frontend Repository (This Repo)**  
> React + Vite dashboard with interactive visualizations.

> **Backend Repository**  
> [SkyIntel ML Backend](https://github.com/Riya7045/Skyintel-ML-backend)

---

# 🏗️ Architecture

SkyIntel is organized into two independent repositories.

| Repository | Description |
|------------|-------------|
| **SkyIntel Frontend (This Repo)** | React + Vite dashboard with interactive analytics, prediction UI, and visualizations |
| **SkyIntel ML Backend** | Python backend exposing REST APIs for ML inference, feature engineering, explainable AI, and recommendation engine |

---

# 🔄 Workflow

```text
Historical Flight Data (5.2M+ Flights)
                │
                ▼
     Data Cleaning & Feature Engineering
                │
                ▼
      Machine Learning Models (XGBoost)
                │
                ▼
          Flask REST API Backend
                │
                ▼
        React + Vite Frontend Dashboard
                │
                ▼
 Flight Predictions • Recommendations
 Airline Analytics • Airport Analytics
 Route Analytics • Model Insights
```

---

# 📷 Application Screenshots

## 🏠 Dashboard

<img width="1920" height="1360" alt="Dashboard-—-SkyIntel-Flight-Delay-Intelligence" src="https://github.com/user-attachments/assets/267b6684-4ec3-4974-9572-072e3e6f5282" />

---

## ✈️ Flight Predictor

<img width="1920" height="897" alt="Flight-Predictor-—-SkyIntel" src="https://github.com/user-attachments/assets/b3e73b2a-b03a-4d5e-9a5b-b97e283802c7" />

---

## ⚖️ Compare Scenarios

<img width="1920" height="1633" alt="Compare-Scenarios-—-SkyIntel" src="https://github.com/user-attachments/assets/716b939b-d923-486e-926d-36a3988da2ef" />

---

## 💡 Recommendations

<img width="1920" height="948" alt="Recommendations-—-SkyIntel" src="https://github.com/user-attachments/assets/13536a03-6850-4f3f-bc00-6979b85ceae5" />

---

## ✈️ Airline Analytics

<img width="1920" height="2198" alt="Airline-Analytics-—-SkyIntel" src="https://github.com/user-attachments/assets/37c539ca-e8dc-4420-81d1-4cb64fdbf8ad" />

---

## 🛫 Airport Analytics

<img width="1920" height="4156" alt="Airport-Analytics-—-SkyIntel" src="https://github.com/user-attachments/assets/1341138f-9340-4a15-a354-d0991e1fcf6a" />

---

## 🛣️ Route Analytics

<img width="1920" height="1475" alt="Route-Analytics-—-SkyIntel" src="https://github.com/user-attachments/assets/48e2f82a-f7e8-4e88-b5f3-1c512d7bfedf" />

---

## 🧠 Model Insights

<img width="1920" height="1250" alt="Model-Insights-—-SkyIntel" src="https://github.com/user-attachments/assets/bee51a8e-67bf-4d7d-9962-3812bd103014" />

---

## ⚙️ Settings

<img width="1920" height="1278" alt="Settings-—-SkyIntel" src="https://github.com/user-attachments/assets/c4db97f8-c244-4388-a519-53dfc11d065d" />

---

# 🚀 Features

### 🔹 Flight Delay Prediction
- Predict delay probability for any flight
- Expected delay estimation
- Risk classification (Low / Medium / High)
- Explainable AI using SHAP feature importance

### 🔹 Compare Flight Scenarios
- Side-by-side comparison of two flight schedules
- Delay probability comparison
- Expected delay analysis
- Best departure recommendation

### 🔹 Smart Departure Recommendations
- Lowest-risk departure windows
- Hourly and weekly recommendations
- Ranked by predicted delay probability

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
- Route risk scores
- Historical route performance
- Trend visualization

### 🔹 Model Insights
- Feature importance
- Confusion Matrix
- ROC Curve
- Model performance trends

### 🔹 Interactive Dashboard
- Operational KPIs
- Delay trends
- Top delayed airlines
- Top delayed airports
- Real-time monitoring

---

# 🛠️ Tech Stack

## Frontend

- React.js
- Vite
- Tailwind CSS
- Recharts
- Axios
- Lucide Icons

## Backend

- Python
- Flask

## Machine Learning

- XGBoost
- Scikit-Learn
- SHAP
- Pandas
- NumPy

## Dataset

- US Flight Delay Dataset
- 5.2 Million Historical Flights

---

# 📊 Machine Learning Pipeline

1. Data Cleaning
2. Feature Engineering
3. Encoding & Scaling
4. Model Training
5. Hyperparameter Tuning
6. REST API Deployment
7. SHAP Explainability
8. Dashboard Visualization

---

# 📈 Prediction Features

The prediction engine uses:

- Airline
- Origin Airport
- Destination Airport
- Scheduled Departure Time
- Day of Week
- Month
- Route Historical Delay
- Airline Historical Delay
- Airport Delay Rate
- Flight Distance

---

# 📂 Project Structure

```text
skyintel-frontend/
│
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── layouts/
│   ├── charts/
│   ├── hooks/
│   ├── services/
│   └── utils/
│
├── package.json
├── vite.config.js
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

# 🚀 Running Locally

```bash
git clone https://github.com/Riya7045/skyintel-frontend.git

cd skyintel-frontend

npm install

npm run dev
```

---

# 🔗 Backend

This frontend communicates with the **SkyIntel ML Backend** for all machine learning inference and analytics APIs.

Backend Repository:

https://github.com/Riya7045/Skyintel-ML-backend

Configure the backend API URL in your environment variables before running the application.

---

# 🔮 Future Improvements

- Live Flight API Integration
- Weather-aware delay prediction
- Aircraft-level analytics
- Crew scheduling optimization
- Delay cause classification
- Multi-airport comparison
- Real-time streaming dashboard
- Flight notifications
- Mobile application
- Cloud deployment with CI/CD

---

# 📄 License

This project is developed for educational and research purposes.

---

# 👩‍💻 Author

**Riya Kumari**

AI • Machine Learning • Full Stack Development • Data Analytics

GitHub: https://github.com/Riya7045
