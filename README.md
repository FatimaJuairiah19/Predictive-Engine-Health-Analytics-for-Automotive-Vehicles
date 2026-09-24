# Predictive-Engine-Health-Analytics-for-Automotive-Vehicles
A machine learning project focused on predictive maintenance in the automotive domain by predicting engine health conditions from sensor data.

## Overview

Traditional vehicle maintenance strategies are commonly based on reactive repairs or fixed maintenance intervals. These approaches can result in unexpected breakdowns, unnecessary servicing, increased operational costs, and vehicle downtime.

This project explores a data-driven predictive maintenance approach for detecting engine health conditions from sensor measurements. The objective is to classify engines as normal or faulty, enabling earlier identification of potential engine problems.

### Business Objective

The main objective is to develop a predictive model that can identify faulty engine conditions using sensor data.

Early fault detection can potentially help:

Reduce unexpected breakdowns
Reduce maintenance costs
Improve vehicle safety
Minimize operational downtime
Support fleet maintenance decisions
Dataset

The project uses a publicly available automotive engine dataset from Kaggle containing engine sensor measurements and corresponding engine condition labels.

## Dataset Characteristics
Samples: Approximately 19,500

Target: Engine Condition

Target Type: Binary classification

0: Normal,
1: Fault

## Features
The dataset contains the following engine sensor measurements:

Engine RPM
Lubrication Oil Pressure
Fuel Pressure
Coolant Pressure
Oil Temperature
Coolant Temperature

## Models
Logistic Regression
MLP
Random Forest
