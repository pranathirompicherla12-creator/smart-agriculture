# 🌱 OptiCrop – Smart Agricultural Crop Recommendation

## Overview

OptiCrop is a Machine Learning-based web application that recommends the most suitable crop for cultivation based on soil nutrients and environmental conditions. The application helps farmers and agricultural professionals make informed decisions by analyzing parameters such as Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall.

The project is developed using Flask for the backend, HTML/CSS/JavaScript for the frontend, and a Random Forest Machine Learning model for crop prediction.

---

## Features

- Crop recommendation based on soil and weather parameters
- User-friendly web interface
- Machine Learning model using Random Forest Classifier
- Displays the predicted crop
- Shows Top 3 crop recommendations with confidence scores
- Responsive website design
- Error handling using try-except
- Fast prediction using a pre-trained model

---

## Technologies Used

### Programming Language
- Python

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Flask

### Machine Learning
- Scikit-learn
- Random Forest Classifier

### Libraries
- Pandas
- NumPy
- Joblib

### Tools
- Visual Studio Code
- Git
- GitHub
- Postman
- Google Chrome

---

## Project Structure

```
OptiCrop/
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
│
├── data/
│   └── Crop_recommendation.csv
│
├── model/
│   ├── crop_model.pkl
│   └── scaler.pkl
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
└── templates/
    ├── index.html
    ├── about.html
    ├── findyourcrop.html
    ├── result.html
    └── contact.html
```

---

## Dataset

The project uses the **Crop Recommendation Dataset**, which contains soil nutrients and environmental parameters for various crops.

### Input Parameters

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall

### Output

- Recommended Crop

---

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/OptiCrop.git
```

### Move to the project directory

```bash
cd OptiCrop
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate the virtual environment

Windows

```bash
venv\Scripts\activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## Train the Machine Learning Model

```bash
python train_model.py
```

This generates:

- crop_model.pkl
- scaler.pkl

inside the **model** folder.

---

## Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000/
```

---

## How to Use

1. Open the application.
2. Navigate to **Find Your Crop**.
3. Enter all required soil and weather parameters.
4. Click **Predict Crop**.
5. View the recommended crop and confidence scores.

---

## Expected Output

The application predicts the most suitable crop based on the provided soil and environmental parameters and displays the prediction along with the top three recommended crops.

---

## Future Enhancements

- Fertilizer Recommendation
- Disease Prediction
- Weather Forecast Integration
- Yield Prediction
- Multi-language Support
- Farmer Dashboard
- Mobile Application

---

## Authors

Developed as an academic Machine Learning and Web Development project.

---

## License

This project is intended for educational purposes.
