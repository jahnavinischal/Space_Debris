# 🚀 Space Debris Classification and Collision Risk Assessment

## Overview

Space debris (or space junk) poses a growing threat to satellites, spacecraft and future space missions. Understanding the orbital behavior and physical characteristics of debris is essential for collision avoidance and space traffic management.

This project leverages Machine Learning to:

- Predict the **Orbit Type** of a space object.
- Estimate its **Radar Cross Section (RCS) Size**.
- Assess potential collision risk by analyzing its trajectory-related characteristics.

The web app is deployed using **Render** to provide an interactive prediction platform.

---

## Problem Statement

Thousands of inactive satellites, rocket fragments and debris pieces orbit Earth at high speeds. Even small objects can cause catastrophic damage during collisions.

This project aims to assist in:

- Identifying the orbital category of space debris.
- Estimating object size through Radar Cross Section classification.
- Supporting collision risk assessment and orbital monitoring.

---

## Features

- Orbit Type Prediction

- Radar Cross Section (RCS) Size Classification

- Collision Risk Assessment Support

- Interactive Web Deployment

---

## Tech Stack

### Machine Learning
- Python
- Scikit-learn
- Pandas
- NumPy

### Visualization
- Matplotlib
- Seaborn

### Deployment
- Flask
- Render

---

## Dataset

The dataset was taken from Kaggle, it contains orbital and physical characteristics of space objects, including:

- Orbital parameters
- Velocity-related features etc.

These features are used to train machine learning models for multi-target prediction.

---

## Model Performance

Overall system accuracy achieved:

**90.4%**

---

## Project Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Performance Evaluation
7. Deployment on Render

---

## Screenshots
The screenshot of the web app is attached below:

```md
![Explore Page](<img width="1857" height="933" alt="image" src="https://github.com/user-attachments/assets/2dda4c7f-0cec-49d1-b4ca-fff827b80c08" />
)
![Prediction Page](<img width="1811" height="890" alt="image" src="https://github.com/user-attachments/assets/53356fc3-b160-48f6-b8de-bf058a450eb0" />
)
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/jahnavinischal/Space_Debris.git
cd Space_Debris
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

---

## Deployment

The application is deployed on Render for public access and interactive predictions.

The deployed app can be accessed from here:
```text
https://space-debris.onrender.com/
```

---

## Future Improvements

- Deep Learning-based classification models
- Real-time satellite tracking integration
- Collision probability estimation
- 3D orbital visualization
- Space debris trajectory forecasting
