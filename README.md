Digital Twin + AI Powered CO₂ Emission Prediction System

**Overview**
   This project integrates Digital Twin technology, AI-driven predictive modeling, and an interactive web dashboard to forecast and monitor CO₂ emissions in real-time.
The solution is designed for industries, researchers, and policymakers to simulate machine behavior, optimize energy usage, and move towards Net-Zero goals.

**Tech Stack**
Digital Twin → Blender (3D modeling)
Simulation Logics → AnyLogic
AI Model → LightGBM trained model (co2_lgbm_model.pkl)
Dashboard → Django + Bootstrap (mono-color, professional, mobile-responsive)
Dataset → Kaggle (industry-relevant CO₂ emission dataset)

**Features**
Real-time CO₂ emission prediction using AI
Digital Twin simulation for visualizing machine behavior
Interactive, mobile-responsive dashboard
Key performance metrics: MAE, RMSE, R², MAPE
Industry-focused, scalable, and production-ready

**Workflow**
Data Collection → Kaggle dataset on machine operations and energy usage
Model Training → LightGBM trained and saved as co2_lgbm_model.pkl
Simulation → AnyLogic + Blender to replicate machine behavior
Prediction Dashboard → Django backend + Bootstrap frontend
Real-Time Monitoring → Live looping predictions until user stops

**Installation**
git clone https://github.com/your-username/CO2-Prediction-DigitalTwin.git
cd CO2-Prediction-DigitalTwin
pip install -r requirements.txt
python manage.py runserver

**Impact**
   This project goes beyond monitoring.
It predicts, simulates, and advises industries on reducing CO₂ emissions, supporting ESG compliance and Net Zero targets.
