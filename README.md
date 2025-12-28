# 🏏 IPL Score Prediction Web App

The **IPL Score Prediction Web App** is a machine learning–based web application that predicts the **final score range of an IPL match** based on real-time match conditions. The project uses historical IPL data and a trained ML regression model to provide accurate score predictions through an interactive web interface.

This application is built using **Python**, **Streamlit**, and **scikit-learn**, making it simple, fast, and user-friendly.

---

## 🚀 Features

- Predicts IPL final score range in real time
- Interactive Streamlit-based UI
- Supports all major IPL teams
- Uses match context such as:
  - Batting team
  - Bowling team
  - Current runs
  - Overs completed
  - Wickets fallen
  - Runs scored in last 5 overs
  - Wickets fallen in last 5 overs
- Displays predicted score as a range for better reliability

---

## 🧠 Machine Learning Model

- Trained on historical IPL match data
- Regression-based model
- Model stored using `pickle` for fast loading
- Outputs a predicted score range instead of a single value

---

## 🛠️ Tech Stack

- Python 3
- Streamlit (Web Framework)
- NumPy & Pandas (Data Processing)
- Scikit-learn (Machine Learning)
- Pickle (Model Serialization)

---



🔹 Steps to Run the Project

Step 1: Clone the GitHub repository
Clone the project to your local system.

Step 2: Install required Python libraries
Install Streamlit, NumPy, Pandas, and Scikit-learn.

Step 3: Generate the ML model
Open the file IPL Score Prediction.ipynb in Google Colab and run all cells to train the model. Save the trained model as ml_model.pkl.

Step 4: Place the model file
Download ml_model.pkl from Colab and place it inside the ipl_score_prediction folder.

Step 5: Run the Streamlit application
Run the command streamlit run ipl_score_prediction/ipl_score_predictor.py.

Step 6: Open the web app
Open the browser and go to http://localhost:8501
 to view the predictions.

## 📊 Sample Output

PREDICTED MATCH SCORE: 165 to 175

---

## 🎯 Future Enhancements

- Integrate live IPL match data
- Improve model accuracy with additional features
- Enhance UI with team logos and charts
- Deploy application on Streamlit Cloud

---

## 📄 License

This project is created for educational and learning purposes.
