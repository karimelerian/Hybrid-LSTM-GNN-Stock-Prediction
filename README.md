# 📈 Stock Price Prediction with Hybrid LSTM-GNN Model  

**Predicting multi-stock movements using deep learning and macroeconomic indicators.**  

## 🚀 Key Features  
- **Hybrid Architecture**: Combines LSTM (for time-series) + GNN (for stock correlations).  
- **Macroeconomic Integration**: Uses GDP, CPI, and Fed rates for better context.  
- **Expanding Window Training**: Simulates real-world trading scenarios.  
- **Performance**: Achieves **MSE: 0.0031** on test data.  

## 🔧 Tech Stack  
- **Python**  
- **PyTorch** (LSTM) + **PyTorch Geometric** (GNN)  
- **Pandas** (Data Processing)  
- **scikit-learn** (PCA, Metrics)  

## 📂 Dataset  
- **Stock Data**: Yahoo Finance (AAPL, MSFT, etc.)  
- **Macro Data**: FRED (GDP, Unemployment, CPI).  

## 📊 Results  
![image](https://github.com/user-attachments/assets/3d2a005d-f3cc-4ef6-a1e8-86a05d656af4)
*Test MSE over time with expanding window.*  


