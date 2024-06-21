# Heart Disease Prediction

## Overview

This project predicts heart disease using a K-Nearest Neighbors (KNN) classifier on a dataset of health metrics.

## Dataset

Columns:
- **Age**: Patient's age
- **Sex**: Gender (M/F)
- **ChestPainType**: Chest pain type (ATA, NAP, ASY, TA)
- **RestingBP**: Resting blood pressure
- **Cholesterol**: Serum cholesterol (mg/dl)
- **FastingBS**: Fasting blood sugar > 120 mg/dl (1=true; 0=false)
- **RestingECG**: Resting electrocardiographic results (Normal, ST, LVH)
- **MaxHR**: Maximum heart rate
- **ExerciseAngina**: Exercise-induced angina (Y/N)
- **Oldpeak**: ST depression
- **ST_Slope**: Slope of the peak exercise ST segment (Up, Flat, Down)
- **HeartDisease**: Target variable (1=heart disease; 0=no heart disease)

## Preprocessing

- Fill missing values with 0.
- Convert categorical columns to numerical using label encoding.
- Normalize features using `MinMaxScaler`.

## Model Training

- **Algorithm**: K-Nearest Neighbors (K=3)
- **Accuracy**: ~87.58%

## Dependencies

- Python 3.x
- pandas
- scikit-learn
- numpy
