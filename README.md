This project predicts Air Quality Index (AQI) using machine learning models. It consists of a Flask-based web application that accepts air pollution parameters like SO2, NO2, RSPM, and SPM, and predicts the AQI category (e.g., Good, Moderate, Hazardous). The backend uses a trained machine learning model stored in a .pkl file, which applies algorithms like Random Forest Regressor to generate predictions based on the inputs.

The project has key files:


app.py: Flask application logic.

model.py: Machine learning logic.

HTML/CSS for UI and interaction.

It aims to provide a user-friendly platform for AQI prediction based on pollutant data
