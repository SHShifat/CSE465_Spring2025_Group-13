# CSE465_Spring2025_Group-13
In this Project we used two models LSTM & XGBoost. 
We took the dataset from here - https://www.geeksforgeeks.org/sales-forecast-prediction-python/ .
In this hybrid Model Our result was: # MAE   : 0.63 ; # RMSE  : 0.84 ; # R²    : 0.6236 ; # SMAPE : 10.34% .
Our calculated accuracy was 89.73%.


Team Member           | Contribution
Subeb Enan            | Built the initial LSTM-only model. Although the model had low accuracy, it provided a foundation that helped in developing the hybrid       
                        architecture.
Shefaul Hoque Shifat  | Designed and implemented the hybrid model using LSTM and XGBoost, which significantly improved accuracy. Leveraged Enan’s LSTM insights for 
                        the LSTM branch.
Nusrat Zahan          | Experimented with other model architectures. Though those models did not yield optimal results, her exploration helped narrow the focus to 
                        more effective techniques.
                        

Network Architecture (LSTM Model)
Layer (Type) | Output Shape | Parameters | Notes
LSTM (64)    | (None, 64)   | 17,024     | Processes sequence of 30 time steps
Dense (1)    | (None, 1)    | 65         | Single output neuron


Evaluation Metrics:
# MAE   : 0.63
# RMSE  : 0.84
# R²    : 0.6236
# SMAPE : 10.34%
