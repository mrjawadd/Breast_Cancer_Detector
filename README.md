# Breast Cancer Prediction Web App

A **machine learning-powered web application** that predicts the likelihood of breast cancer based on user-provided medical data. The app uses **logistic regression** to provide real-time predictions and displays both the probability and predicted outcome. It is designed to be user-friendly and accessible for anyone interested in quick risk assessment.

## Features

* **Real-Time Prediction:** Enter relevant features (like tumor size, cell characteristics) and instantly get a prediction.
* **Probability Output:** Displays the probability of cancer along with the final prediction, giving more insight into risk.
* **User-Friendly Interface:** Simple and intuitive web interface requiring no prior technical knowledge.
* **Quick Diagnosis:** Designed to provide results rapidly for demonstration or educational purposes.
* **Lightweight & Efficient:** Runs locally without heavy system requirements.

## How It Works

The app collects input features from the user via a web form. These inputs are then fed into a **logistic regression model** trained on the Breast Cancer Wisconsin dataset. The model outputs a prediction of whether the input indicates benign or malignant cancer, along with a probability score.

## Tech Stack

* **Backend:** Python with Flask framework
* **Machine Learning:** Scikit-learn (Logistic Regression)
* **Frontend:** HTML, CSS, Bootstrap for responsive design
* **Data:** Breast Cancer Wisconsin dataset

## Installation and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/mrjawadd/Breast_Cancer_Detector.git
   cd Breast_Cancer_Detector
   ```
2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:

   ```bash
   python app.py
   ```
4. Open your browser and navigate to:

   ```
   http://127.0.0.1:5000
   ```
5. Fill in the input fields with the patient’s data and click **Predict**.
6. View the prediction and probability score.

## Potential Improvements

* **Additional Models:** Integrate Random Forest, Neural Networks, or XGBoost for higher accuracy.
* **Feature Importance Visualization:** Show which features most influence the prediction.
* **User Accounts:** Allow users to save predictions securely.
* **Deployment:** Host the app online for wider accessibility.
* **Data Validation:** Add checks for invalid or missing input values.

## Use Cases

* Educational purposes to learn about machine learning in healthcare.
* Demonstration of predictive modeling and web deployment.
* Quick experimental tool for understanding risk assessment based on data.

## GitHub

[Breast Cancer Detector](https://github.com/mrjawadd/Breast_Cancer_Detector)
