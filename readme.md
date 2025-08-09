# Indian Residential Energy Dashboard

This project is a Streamlit-based web dashboard for analyzing and forecasting household energy consumption across Indian regions. It uses machine learning (Linear Regression) to detect inefficient energy usage and generate actionable recommendations.

## Features

- Visualize daily energy consumption trends
- Detect inefficient energy usage patterns
- Predict energy consumption using a trained Linear Regression model
- Provide practical energy-saving recommendations
- Interactive dashboard for intuitive exploration

## Technologies Used

- Python
- Streamlit
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Joblib

## Folder Structure

Indian_Residential_Energy_Dashboard/
│
├── app.py # Main Streamlit application
├── household_energy.csv # Energy usage dataset
├── forecast_model.pkl # Trained ML model
├── daily_energy_plot.png # Visualization output
├── requirements.txt # Project dependencies
└── README.md # Project documentation

### Install Dependencies

Ensure you have Python installed. Then install required packages:
pip install -r requirements.txt
Run the Dashboard
bash
Copy
Edit
streamlit run app.py
This will launch the dashboard in your default web browser.
