# Daily-Rainfall-Prediction---16-Day-Forecasting
📌 Project Overview

This FastAPI-based Weather Forecasting API integrates real-time weather data using Open-Meteo and predicts rainfall for the next 16 days using a trained Random Forest model. The results are stored in a PostgreSQL database, and the API allows users to query weather forecasts dynamically based on latitude and longitude.

🚀 Features

✅ Dynamic City Forecasting: Fetch weather predictions for any city in Pakistan by specifying latitude & longitude
✅ Real-time Weather Data: Retrieves live weather conditions from Open-Meteo API.
✅ 16-Day Rainfall Prediction: Uses a machine learning model to predict rainfall probability.
✅ PostgreSQL Integration: Stores weather variables and predictions for future reference.
✅ Optimized Queries: API fetches only the latest weather forecast (next 16 days), ignoring past data.
✅ Fully Automated: Weather data updates daily using cron jobs (or Task Scheduler for Windows).
✅ Deployed with Uvicorn: Ensures high performance with ASGI server.
🔹 Project Highlights:
📡 Real-Time Data Integration – Fetching weather data via Open Meteo API
📅 Historical Dataset (2020-2024) – Collected from Open Meteo for Chakwal
📊 Feature Engineering – Aggregated hourly weather variables into daily features
⚖️ Preprocessing – Data normalization & outlier detection
🤖 Model Training & Evaluation – Compared multiple models, Random Forest with Hyperparameter Tuning performed best
⚡ Live Predictions – Normalizing real-time data & forecasting rainfall for 16 days
🌦️ FastAPI Weather Forecasting API

🏗️ Tech Stack

Backend: FastAPI, Uvicorn

Database: PostgreSQL

Machine Learning: Random Forest (Scikit-Learn)

Weather Data: Open-Meteo API

Deployment: Docker / AWS / DigitalOcean (Optional)
![image](https://github.com/user-attachments/assets/41b02a0b-0311-43aa-b6cc-bc4c9e7dca82)

🚨 Note: The code and implementation details are company intellectual property and cannot be shared. However, I'm happy to assist anyone interested in the approach and methodology!
