# SmartSuperMarket
🛒 Smart Retail Automation System (Graduation Project) An AI-powered supermarket system that uses RFID technology, real-time data processing, and machine learning to automate the shopping experience for customers and optimize inventory and sales analytics for administrators.
📌 Project Overview
This project aims to modernize traditional supermarket workflows by integrating:

RFID-based product detection

Mobile applications for customers and administrators (Flutter)

Python backend with REST APIs (FastAPI/Flask)

AI modules for customer behavior analysis, product bundling, and demand forecasting

🧩 Key Features
🔹 RFID Integration
Automatically detects products added/removed from shopping carts using RFID readers.

Real-time cart updates sent to the mobile app.

🔹 Customer App
View scanned items, total bill, and product details.

Complete in-app payment without checkout queues.

🔹 Admin App
Monitor inventory levels, sales reports, and product analytics.

View top-selling products, peak shopping times, and AI-generated recommendations.

🔹 AI & Data Analytics
Customer Segmentation: K-Means clustering groups customers by behavior.

Product Bundling: Apriori / FP-Growth finds frequently purchased product sets.

Time-Series Forecasting: ARIMA / LSTM predict demand and peak hours.

Anomaly Detection: Identifies unusual or suspicious purchase behavior.

🛠️ Tech Stack
Area	Technology
Frontend (App)	Flutter(Dart)
Backend API	Python (FastAPI / Flask)
Database	Mongodb
Machine Learning	Scikit-learn, TensorFlow, Statsmodels
Data Handling	Pandas, NumPy
Design	Figma
Hardware	RFID Reader, RFID Tags
