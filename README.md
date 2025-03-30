# Blood Donation Prediction using Machine Learning

## Description
This project aims to predict whether a person will donate blood based on historical donation data. The dataset is sourced from the "Give Life - Predict Blood Donations" challenge. By utilizing machine learning models, the project provides insights into donation patterns and helps optimize blood donation campaigns.

## Dataset Overview
The dataset contains the following features:
- **Recency (months)**: Number of months since the last blood donation.
- **Frequency (times)**: Total number of blood donations.
- **Monetary (c.c. blood)**: Total amount of blood donated in c.c.
- **Time (months)**: Time in months since the first donation.
- **Target Variable**: Whether the person donated blood in March 2007 (`1` = Yes, `0` = No).

## Features Implemented
- Data loading and preprocessing using `pandas`
- Training and evaluating a **Random Forest Classifier**
- Model evaluation using accuracy metrics

## Model Performance
The Random Forest Classifier was trained with different configurations:
- **Initial Model (100 Trees)**: Achieved an accuracy of **72%**.
- **Optimized Model (200 Trees)**: Improved accuracy to **72.67%**.

## Project Structure 
'''

├── datasets/                 # Contains the blood donation dataset
├── script.py                 # Main Python script for model training
├── README.md                 # Project documentation
└── requirements.txt          # List of dependencies (if required)


## License
This project is licensed under the MIT License - feel free to use and modify it as needed.

## Contact
For any questions or collaborations, feel free to reach out:
- **GitHub**: [nishathafroz08](https://github.com/nishathafroz08)
- **Email**: [nishathafroz08@gmail.com](mailto:nishathafroz08@gmail.com)
