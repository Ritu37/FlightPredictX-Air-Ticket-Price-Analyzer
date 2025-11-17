# FlightPredictX – Air Ticket Price Analyzer

This project focuses on predicting flight ticket prices using Machine Learning techniques. A real-world airline dataset was processed, cleaned, analyzed, and modeled using advanced regression algorithms. The goal is to understand the factors influencing airfare and build an accurate price prediction system.

## Project Overview

Flight prices vary based on several features such as duration, number of stops, departure time, airline, and route. In this project:

- A real dataset was cleaned and preprocessed.
- Exploratory Data Analysis (EDA) was performed to uncover patterns.
- Multiple ML models were trained and compared.
- Final predictions were generated using the best-performing model.

## Data Processing and Feature Engineering

Key preprocessing steps included:

- Handling missing values  
- Converting date and time columns into numerical features  
- Encoding categorical variables (airline, source, destination, etc.)  
- Creating new derived features such as:
  - Journey day and month  
  - Total stops  
  - Departure and arrival hour  
- Scaling numerical variables  

## Exploratory Data Analysis (EDA)

EDA was performed to understand:

- Distribution of flight prices  
- Relationship between price and number of stops  
- Airline-wise pricing variations  
- Influence of travel duration  
- Seasonal trends  

Visualizations such as boxplots, histograms, and correlation heatmaps were used for insights.

## Machine Learning Models Used

Several regression models were trained and evaluated:

- XGBoost Regressor  
- LightGBM Regressor  
- Random Forest Regressor  

### Model Evaluation Metrics

Models were compared using:

- R² Score  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  

The best-performing model was selected for final prediction.

## Results

- Among the models evaluated, XGBoost or LightGBM (whichever performed best in your notebook) delivered the highest accuracy.
- Feature importance analysis showed major contributing features such as Total Stops, Airline, Journey Month, and Duration.

## Project Structure

├── data/
│ └── flight_data.csv
├── notebooks/
│ └── Code.ipynb
├── src/
│ ├── data_preprocessing.py
│ ├── model_training.py
│ └── prediction.py
├── README.md
└── requirements.txt

## Tech Stack

- Python  
- NumPy, Pandas  
- Scikit-Learn  
- XGBoost  
- LightGBM  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## Future Improvements

- Deployment using Flask or Streamlit  
- Hyperparameter tuning  
- Automated ML pipeline  
- Integration with real-time flight pricing APIs  
