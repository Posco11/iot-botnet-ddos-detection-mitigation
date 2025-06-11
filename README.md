# IoT Botnet Detection and DDoS Mitigation using Machine Learning

This project applies machine learning and ensemble models to detect botnet activity and mitigate DDoS attacks in IoT networks. It integrates techniques like Random Forest, XGBoost, CNN, and optimization with Recurrent Bat Algorithm and GT-AS (Game Theory-based Adaptive Security).

## Project Files

- `notebooks/Botnet.ipynb` – Handles botnet detection using supervised and ensemble learning techniques.
- `notebooks/DDoS.ipynb` – Focuses on DDoS mitigation using advanced techniques like Bat Optimization and GT-AS.
- `data/iot_network_analysis_dataset_10000.csv` – Dataset for training and testing.

## Key Features

- Preprocessing and feature selection
- ML models: Random Forest, XGBoost, CNN
- Ensemble learning (stacking, boosting)
- Recurrent Bat Optimization (RBO)
- GT-AS for DDoS mitigation
- Performance evaluation with accuracy, precision, recall, F1-score

## Dataset

- Contains network traffic statistics and attack labels (Benign, Mirai, Qbot, Kaiten, Normal, DDoS)

## Setup

### 1. Install Requirements

```bash
pip install -r requirements.txt
