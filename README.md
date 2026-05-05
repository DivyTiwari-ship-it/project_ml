# NASA Nearest Earth Objects - Hazard Prediction

## Problem
Predict whether a near-earth asteroid is hazardous or not.

## Dataset
- Source: NASA via Kaggle
- 90,000+ asteroids
- Features: diameter, velocity, miss distance, magnitude

## Approach
- Removed missing values
- Encoded target column (True/False → 1/0)
- Used Random Forest Classifier

## Result
- Accuracy: 92%

## Tech Stack
- Python, Pandas, Scikit-learn

## How to Run
1. Download dataset from Kaggle
2. Run notebook cells top to bottom

# Titanic Survival Prediction

## Problem
Predict whether a passenger survived the Titanic disaster or not.

## Dataset
- Source: Kaggle Titanic Competition
- 891 training passengers
- Features: Pclass, Sex, Age, Fare

## Approach
- Encoded Sex column (male/female → 0/1)
- Filled missing Age and Fare with mean
- Used Random Forest Classifier

## Result
- Submitted to Kaggle Competition
- Model trained on full training data

## Tech Stack
- Python, Pandas, Scikit-learn

## How to Run
1. Download dataset from Kaggle Titanic Competition
2. Run notebook cells top to bottom
