# Intrusion-Detection-System-
This project analyzes intrusion detection using the **NSL KDD dataset** with six machine learning algorithms, reporting each method’s accuracy for practical network security applications.[1]

## Project Overview
The goal is to detect network intrusions — actions that threaten the **integrity**, **confidentiality**, or **availability** of network systems. The project uses the NSL KDD dataset, a benchmark in intrusion detection studies that contains TCP/IP connection records labeled as either normal or one of four types of attacks.[1]

## Dataset Details
- **NSL KDD**: Derived from KDD 99, focused on intrusion events.[1]
- **Features**: 41 attributes per record.[1]
- **Total Records**: 148,517 (Train: 125,973, Test: 22,544).[1]

## Algorithms Used
- **Random Forest**: Aggregates results from multiple decision trees for robust classification.[1]


## Data Preprocessing
- **Min-Max Scaling** is applied to normalize feature values, helping improve model performance.[1]

## Results: Accuracy Comparison

| Algorithm                   | Accuracy (%)      |
|-----------------------------|------------------|
| Random Forest               | 75.62[1]      |
