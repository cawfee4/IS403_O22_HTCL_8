<!-- Banner -->
<p align="center">
  <a href="https://www.uit.edu.vn/" title="Trường Đại học Công nghệ Thông tin" style="border: none;">
    <img src="https://i.imgur.com/WmMnSRt.png" alt="Trường Đại học Công nghệ Thông tin | University of Information Technology">
  </a>
</p>

# Leveraging Statistical and Machine Learning models to forecast stock prices of Vietnamese tech companies

## 1. INTRODUCTION
This repository is created for the final project of the course `IS403.HTCL` - Data Analysis in Business at [University of Information Technology](https://www.uit.edu.vn/). The project aims to forecast stock prices of Vietnamese tech companies using statistical and machine learning models. The project is implemented by **Group 8**, including 3 members: Ninh Thien Bao (L), Dao Tien Dat, Dao Minh Huy.

## 2. DATASETS
- The datasets collected by [Vnstock3](https://vnstocks.com/). The datasets contain stock prices of 3 Vietnamese tech companies, spanning from **March 1, 2019**, to **March 1, 2024**: 
  - **FPT Corporation** - FPT
  - **CMC Corporation** - CMG
  - **Innovative Technology Development Corporation** - ITD
- Data is collected daily, including the following fetures: date, open price, high price, low price, close price, volume, and ticket token. The datasets stored in the `Dataset` folder.

## 3. MODEL
The models used in this project:
- Linear Regression
- ARIMA
- SARIMAX
- LSTM
- Gradient Boosting Regressor
- Long Short-Term Memory (LSTM)
- Recurrent Neural Network (RNN)
- Gate Recurrent Unit (GRU)
- Decomposition Linear (DLinear)

The implementation of each model is stored in the `Model` folder.

## 4. EVALUATION
Dataset splited into training and testing sets with a ratio of 80:20, 90:10, and 70:30. The models are evaluated using the following metrics: 
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## 5. WORK DISTRIBUTION
Name | Role | Work |
| --- | --- | --- |
| Ninh Thien Bao | Leader | Data preprocessing and implemented LR, LSTM model. Contributed edit the project document. |
| Dao Tien Dat |  | Implemented GBR, RNN and DLinear models. Contribued edit the project document and literature review. |
| Dao Minh Huy |  | Implemented ARIMA, SARIMAX and GRU model. Contributed edit the project document. |

### FOLDER STRUCTURE
```
└── 📁Dataset
    └── CMG_stock.csv
    └── FPT_stock.csv
    └── ITD_stock.csv
└── 📁Latex
    └── TemplatePaper.pdf
    └── TemplatePaper.tex
    └── ...
└── 📁Model
    └── 📁ARIMA
        └── ARIMA_CMG_73.ipynb
        └── ...
    └── 📁DescriptiveStatistics
        └── CMG.ipynb
        └── FPT.ipynb
        └── ITD.ipynb
    └── 📁DLinear
        └── DLinear_CMG_73.ipynb
        └── ...
    └── 📁GradientBoostingRegressor
        └── GradientBoostingRegressor_CMG_73.ipynb
        └── ...
    └── 📁GRU
        └── GRU_CMG_73.ipynb
        └── ...
    └── 📁LinearRegression
        └── LinearRegression_CMG_73.ipynb
        └── ...
    └── 📁LSTM
        └── LSTM_CMG_73.ipynb
        └── ...
    └── 📁RNN
        └── RNN_CMG_73.ipynb
        └── ...
    └── 📁SARIMAX
        └── SARIMAX_CMG_73.ipynb
        └── ...
└── README.md
```
## 6. REFERENCES

1. Pai, P.-F., & Lin, C.H. (2005). A hybrid ARIMA and support vector machines model in stock price forecasting.
2. Vijh, M., et al. (2020). Stock Closing Price Prediction using Machine Learning Techniques.
3. Nelson, D.M., Pereira, A.C.M., & Oliveira, R.A. de (2017). Stock market’s price movement prediction with LSTM neural networks.
4. Zhou, T., et al. (2022). Are Transformers Effective for Time Series Forecasting?. arXiv:2205.13504v3 [cs.AI] 17 Aug 2022.
5. Other references as listed in the provided document.

## 7. AUTHORS

- Ninh Thien Bao, Faculty of Information Systems, University of Information Technology (21520621@gm.uit.edu.vn)
- Dao Tien Dat, Faculty of Information Systems, University of Information Technology (21521930@gm.uit.edu.vn)
- Dao Minh Huy, Faculty of Information Systems, University of Information Technology (21520912@gm.uit.edu.vn)
