# weather-prediction-classification-
A machine learning classification model to predict weather conditions (Sunny, Rainy, Cloudy) using features like temperature, humidity, wind speed, precipitation, cloud cover, pressure, UV index, visibility, season, and location. Useful for forecasting and decision-making.
🌦️ Weather Prediction (Classification)
This project uses machine learning to classify weather conditions such as Sunny, Rainy, and Cloudy based on multiple atmospheric and environmental features. Accurate weather classification helps in better forecasting, planning, and building climate-aware applications.

📊 Project Overview
The goal of this project is to develop a classification model that predicts the type of weather using structured weather data. By analyzing various features like temperature, humidity, UV index, and cloud cover, the model can determine the expected weather condition for a given set of values.

🧠 Features Used
The dataset includes the following features:

Temperature (°C)

Humidity (%)

Wind Speed (km/h)

Precipitation (%)

Cloud Cover (Clear / Partly Cloudy / Overcast)

Atmospheric Pressure (hPa)

UV Index

Season (Winter, Spring, etc.)

Visibility (km)

Location Type (Inland, Coastal, Mountain)

Target Variable: Weather Type (Sunny, Rainy, Cloudy)

🔍 Approach
Data Preprocessing

Handled missing values

Encoded categorical variables

Normalized numeric features

Model Training

Tested multiple classification models (e.g., Random Forest, Decision Tree, KNN)

Performed hyperparameter tuning using GridSearchCV

Evaluation

Used metrics such as Accuracy, Precision, Recall, F1-score

Visualized performance using Confusion Matrix

🛠️ Tools & Technologies
Python

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Visualization

Scikit-learn – Model building and evaluation

✅ Results
The best-performing model achieved high accuracy in predicting weather types, with strong generalization across both training and testing datasets.

📁 Project Structure
Copy
Edit
weather-prediction-classification/
│
├── weather_data.csv
├── weather_prediction.ipynb
├── requirements.txt
├── README.md
└── models/
📌 Future Improvements
Add time-series forecasting features

Deploy the model via a web app

Collect real-time weather data via APIs

🙌 Acknowledgements
This project was developed for educational purposes to demonstrate how machine learning can be applied in environmental and weather-related domains.
