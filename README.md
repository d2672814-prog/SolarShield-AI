# SolarShield AI

SolarShield AI is a machine learning system that predicts solar storms 
to protect satellites from space weather risks.

## Problem
Solar storms can damage satellites and disrupt GPS systems.

## Solution
We use a Random Forest model trained on solar activity parameters:
- Solar flux
- Magnetic index
- Solar wind speed

## MVP
The model predicts probability of solar storms with ~97% accuracy.

## Technologies
- Python
- Scikit-learn
- Machine Learning
## Run
pip install -r requirements.txt
python main.py
