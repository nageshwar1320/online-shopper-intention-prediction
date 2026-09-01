# Online Shopper Intention Prediction

A machine learning project that predicts whether an online shopper will complete a purchase based on their browsing behavior and session data.

## Overview

This project analyzes customer behavior data collected from an e-commerce website and predicts purchase intention using machine learning algorithms. The goal is to help businesses understand customer behavior, optimize marketing strategies, and improve conversion rates.

---

## Features

- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- Customer behavior visualization
- Model training and evaluation
- Purchase intention prediction
- Interactive web interface for predictions

---

## Dataset

The dataset contains user session information, including:

- Administrative pages visited
- Informational pages visited
- Product-related pages visited
- Bounce rates
- Exit rates
- Page values
- Special day scores
- Operating systems
- Browser types
- Traffic types
- Visitor type
- Weekend activity

Target variable:

- Revenue (Purchase: Yes/No)

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Flask
- HTML, CSS

---

## Machine Learning Models

- Logistic Regression
- Random Forest
- XGBoost

---

## Project Workflow

```text
Dataset Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Prediction
```

---

## Results

| Model | Accuracy |
|--------|--------|
| Logistic Regression | 87% |
| Random Forest | 90% |
| XGBoost | 92% |

---

## Key Insights

- Product-related pages strongly influence purchase decisions.
- Returning visitors have a higher probability of making purchases.
- Page value and exit rates significantly impact customer behavior.
- Weekend sessions show different purchasing patterns.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/online-shopper-intention-prediction.git
```

Move into the project directory:

```bash
cd online-shopper-intention-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

---

## Folder Structure

```text
online-shopper-intention-prediction/

├── dataset/
├── notebooks/
├── models/
├── static/
├── templates/
├── app.py
├── requirements.txt
└── README.md
```

---

## Future Improvements

- Deploy the model using Docker.
- Add real-time predictions.
- Improve model accuracy using deep learning.
- Integrate recommendation systems.

---

## Author

**Nageshwar Tiwari**

- LinkedIn: https://www.linkedin.com/in/nageshwartiwari/
- GitHub: https://github.com/nageshwar1320
