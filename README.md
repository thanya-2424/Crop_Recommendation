🌾 Crop Recommendation System

An intelligent ML-powered system that recommends the most suitable crop for cultivation based on soil and environmental parameters.






📖 Overview

The Crop Recommendation System leverages data science and machine learning to suggest the best crop for farmers based on factors such as:

🌱 Nitrogen, Phosphorus, Potassium content in the soil

🌡️ Temperature

💧 Humidity

🌧️ Rainfall

🌍 Soil pH

This project aims to increase agricultural productivity by guiding farmers with data-driven decisions.

✨ Features

✅ User-friendly interface for crop recommendation
✅ Accurate ML predictions trained on agricultural datasets
✅ Easy-to-run web app (Flask/Streamlit)
✅ Lightweight, fast, and customizable

🛠️ Tech Stack

Python 🐍

Pandas, NumPy, Scikit-learn for data handling & ML

Matplotlib, Seaborn for visualization

Flask / Streamlit for the web interface

Pickle/Joblib for model deployment

⚙️ Installation

Clone the repository:

git clone https://github.com/thanya-2424/Crop_Recommendation.git
cd Crop_Recommendation


Run the app:

The app is built with Streamlit:

streamlit run app.py


It’s built with Flask:

python app.py


Then, open the local server link shown in the terminal (e.g., http://127.0.0.1:5000/).

📊 Dataset

The dataset contains soil and climate parameters:

N : Nitrogen

P : Phosphorus

K : Potassium

temperature : Temperature in °C

humidity : Relative Humidity %

ph : Soil pH value

rainfall : Rainfall in mm

label : Suitable crop

🔮 Future Enhancements

📌 Integrate real-time weather API data for more accurate recommendations

📌 Build a mobile-friendly interface for farmers

📌 Add multilingual support for wider accessibility

📌 Implement advanced deep learning models for higher accuracy

📌 Provide fertilizer and irrigation suggestions alongside crop prediction