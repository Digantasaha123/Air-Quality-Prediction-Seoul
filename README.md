# Spatio-Temporal Air Quality Prediction Using Spectral GCN and LSTM

##  Project Overview
This project implements a novel Deep Learning framework to forecast air quality (PM2.5 and NO2) in Seoul, South Korea. It addresses the limitations of traditional models by integrating a **Second-Order Spectral Graph Convolutional Network (GCN)** with an **Attention-based LSTM**.

The model effectively captures:
- **Spatial Dependencies:** Using graph topology of monitoring stations.
- **Temporal Patterns:** Using LSTM with attention to focus on critical time steps.

## Key Features
- **Algorithm:** Second-Order Spectral GCN + Attention LSTM.
- **Performance:** Achieved an **R² score of ~0.98**, outperforming 8 baseline models (including S2GNN-BiLSTM, GRU).
- **Dataset:** Air Quality measurements from 25 districts in Seoul (2017-2019).
- **Tech Stack:** Python, PyTorch, NumPy, Pandas.

## Results
| Model | RMSE | MAE | R² Score |
|-------|------|-----|----------|
| **Proposed Model** | **Low** | **Low** | **0.98** |


*(Detailed comparison graphs and ablation study results are included in the notebook)*

## 🛠️ How to Run
1. Clone the repository.
2. Open `Copy_of_d_air_Quality.ipynb` in Google Colab or Jupyter Notebook.
3. Install dependencies: `pip install torch numpy pandas matplotlib`.
4. Run the cells to train the model.
