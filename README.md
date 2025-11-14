# Smart Energy Grid

A Machine Learning Capstone Project focused on forecasting hourly energy consumption of an electric power station using statistical, neural, and hybrid models.

---

## 📌 Project Overview

This project predicts the hourly energy consumption of a power station based on one full year of historical data.  
Three different modelling approaches are implemented and compared:

- **ARIMA** – Statistical time-series forecasting  
- **MLP (Multi-Layer Perceptron)** – Neural-network-based regression  
- **ANFIS (Adaptive Neuro-Fuzzy Inference System)** – Hybrid neuro-fuzzy modelling  

The objective is to analyze which model gives the most accurate predictions and understand the underlying consumption patterns.

---

## 📂 Repository Structure
  - Capstone_Review_3.ipynb: "Main notebook containing preprocessing, modeling, and evaluation"
  - Dataset.csv: "Hourly energy consumption dataset"
  - PROJECT_DOCUMENTATION.md: "Detailed project documentation"
  - Quick_Reference_Cheat_Sheet.md: "Quick guide to important concepts"
  - Visual_Architecture_Guide.md: "Model and system architecture diagrams"
  - CAPSTONE_REPORT-3.pptx: "Presentation summarizing the entire project work"

---

## 🎯 Problem Statement

Electric power stations require precise short-term energy consumption forecasting for:

- Load balancing  
- Cost optimization  
- Resource management  
- Grid stability

This project aims to build a reliable model that predicts **next-hour energy consumption**, providing insights that can help optimize power station operations.

---

## 🧠 Models Implemented

### 🔹 1. ARIMA
- Captures temporal structure and autocorrelation.
- Provides a statistical baseline for prediction.

### 🔹 2. MLP (Neural Network)
- Learns non-linear relationships in the time-series.
- Uses dense layers to predict future consumption.

### 🔹 3. ANFIS (Hybrid Model)
- Combines fuzzy logic with neural network learning.
- Effective for modelling uncertainty and non-linearity.

---

## 📊 Results Summary

*(You can update this section with actual accuracy metrics)*

- Comparative results (MAE / RMSE / MAPE) for ARIMA, MLP, and ANFIS  
- Visual plots: prediction vs actual  
- Analysis of pattern trends (seasonality, peaks, daily cycles)  
- Key factors driving energy consumption  

---





---

# ✅ How to run:

```yaml
how_to_run:
  - step: "Clone the repository"
    command: git clone https://github.com/Rupeshmund04/Smart_Energy_Grid.git

  - step: "Install required libraries"
    command: pip install -r requirements.txt

  - step: "Open the notebook"
    command: jupyter notebook Capstone_Review_3.ipynb

  - step: "Run all sections"
    includes:
      - Data Preprocessing
      - ARIMA Model
      - MLP Neural Network
      - ANFIS Hybrid Model
      - Model Comparison
      - Visualization

  - step: "Review documentation"
    files:
      - PROJECT_DOCUMENTATION.md
      - Visual_Architecture_Guide.md
      - CAPSTONE_REPORT-3.pptx
```


TEAM_MEMBERS:
  - "⭐ Rupesh Kumar Mund"
  - "⭐ Shubhranshu Sudeepta Panda"
  - "⭐ Akshit Verma"

FUTURE_IMPROVEMENTS:
  - "🔮 Implement multi-step forecasting (e.g., next 24 hours)"
  - "🌦️ Integrate weather and external factors"
  - "⚡ Deploy as a real-time forecasting API"
  - "🤖 Try advanced models: LSTM, GRU, Transformers"
  - "🎯 Apply hyperparameter tuning techniques like Grid Search or Optuna"


CONTACT:
  github: "https://github.com/Rupeshmund04"

how_to_run:
  - step: "Clone the repository"
    command: |
      git clone https://github.com/Rupeshmund04/Smart_Energy_Grid.git


