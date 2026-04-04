🌌 SCOPE — Planet Habitability Prediction System

An AI-powered system that predicts whether a planet is potentially habitable using real-time data from NASA’s Exoplanet Archive. This project combines machine learning, data analysis, and interactive visualization to generate actionable insights from astronomical data.

⸻

🚀 Features
	•	🔭 Real-time data fetching from NASA Exoplanet API
	•	🤖 Machine Learning model for habitability prediction
	•	📊 Interactive dashboard using Streamlit
	•	📈 Data visualization (mass, radius, orbital trends)
	•	🪐 Custom planet prediction (user input)
	•	📉 Model evaluation (accuracy, confusion matrix, feature importance)

⸻

🛠 Tech Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Streamlit, SQL (PostgreSQL), IBM Watson Studio, Microsoft Azure (basic), REST APIs, Joblib

⸻

⚙️ How It Works
	1.	Fetches real-time exoplanet data from NASA API
	2.	Cleans and preprocesses data (handling missing values, feature engineering)
	3.	Applies machine learning (Random Forest) for classification
	4.	Evaluates model performance
	5.	Provides predictions via interactive dashboard

⸻

📊 Model Details
	•	Algorithm: Random Forest Classifier
	•	Features: Planet mass, orbital period, number of stars, number of planets
	•	Target: Habitability (based on scientific radius criteria)
	•	Approach: Stratified train-test split with balanced class handling

⸻

📌 Results
	•	Achieved high predictive performance with balanced classification
	•	Identified key planetary features influencing habitability
	•	Built scalable pipeline for real-time predictions

⸻

▶️ Run Locally

pip install -r requirements.txt
streamlit run scope_dashboard.py

