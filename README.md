# Soil Health Assessment using Machine Learning and Federated Learning

This repository contains implementations for soil health assessment using machine learning, statistical analysis, and federated learning. The project focuses on preprocessing soil datasets, computing Soil Quality Index (SQI), predictive modeling, and privacy-preserving distributed learning.

## Features

* Soil dataset preprocessing and cleaning
* Soil Quality Index (SQI) computation
* Temperature and environmental factor regression
* Soil quality classification
* Principal Component Analysis (PCA)
* Federated Learning for distributed soil health prediction

## Project Structure

```text
Soil_helath_assessment/
│
├── Federated_Learning/
│   └── Federated_learning.py
│
├── Preprocessing/
│   ├── Dataset1/
│   └── Dataset2/
│       ├── Dataset2_preprocessing.py
│       ├── Dataset2_SQI_calculation.py
│       ├── Dataset2_SQI_classification.py
│       ├── Dataset2_temprature_regression.py
│       └── PCA__dataset_2.py
│
└── data/
```

## Methodology

1. Data preprocessing and feature cleaning
2. Soil Quality Index (SQI) calculation
3. Feature reduction using PCA
4. Regression analysis for environmental factors
5. Soil quality classification
6. Federated learning for distributed model training

## Requirements

```bash
pip install numpy pandas scikit-learn matplotlib seaborn tensorflow
```

## Usage

### Data Preprocessing

```bash
python Dataset2_preprocessing.py
```

### Soil Quality Index Calculation

```bash
python Dataset2_SQI_calculation.py
```

### Soil Quality Classification

```bash
python Dataset2_SQI_classification.py
```

### PCA Analysis

```bash
python PCA__dataset_2.py
```

### Federated Learning

```bash
python Federated_learning.py
```

## Applications

* Precision Agriculture
* Soil Health Monitoring
* Sustainable Farming
* Environmental Assessment
* Distributed Agricultural Analytics

