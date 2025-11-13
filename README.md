The complete work, including all code notebooks, will be uploaded after the official defense of the engineering thesis.

This repository (will) contains the code and analysis for my engineering thesis, which focuses on predicting football player transfer prices using machine learning models.
The goal of the project is to build a data-driven predictive tool capable of estimating a player’s market value based on performance statistics and club information.

Project Overview

The project uses real Bundesliga data combining player statistics, club performance, and individual attributes.
Several machine learning models were trained and compared:

1. Random Forest

2. XGBoost

3. CatBoost

4. Support Vector Regression (SVR)

XGBoost achieved the best results, explaining ~68% of player price variance (R² = 0.68) with a Mean Absolute Error ~ €5M.

Methodology

1. Data preprocessing: cleaning, handling missing values, statistical exploration.

2. Feature engineering: creation and selection of key features (e.g., xG, goals, age, club).

3. Model training: hyperparameter tuning via grid search.

4. Model evaluation: metrics such as R² and MAE.

5. Model interpretability: feature importance, SHAP, PDP, ICE, and ALE analyses.

Tech Stack

Python 3.12

pandas, NumPy, scikit-learn, XGBoost, CatBoost, SHAP, Matplotlib

<img width="1540" height="502" alt="new_tab1" src="https://github.com/user-attachments/assets/edafcf6c-b98c-49c1-8f88-6e0200f17e80" />
<img width="358" height="382" alt="tabela2" src="https://github.com/user-attachments/assets/12e7f32b-444b-4659-a2c0-a83f6722220c" />
<img width="2789" height="1990" alt="general statsv2" src="https://github.com/user-attachments/assets/7acf4cc6-762b-4b0b-940b-2c956f98ce8e" />
<img width="2390" height="1389" alt="histplot pricev2" src="https://github.com/user-attachments/assets/db5cb2d5-bb7d-47da-82d1-e2c6f48d1363" />
<img width="874" height="778" alt="heatmap" src="https://github.com/user-attachments/assets/23b46694-de89-4d7b-aa58-0f91ed4cdbf2" />
<img width="630" height="470" alt="exai" src="https://github.com/user-attachments/assets/61aff0e6-1fd2-4120-a978-e6a55c224bcb" />
<img width="762" height="579" alt="summary" src="https://github.com/user-attachments/assets/77c29f7d-d31b-46d0-8d25-8f737067d7e4" />
<img width="848" height="607" alt="shap_abs_mean" src="https://github.com/user-attachments/assets/975dc63c-6c31-4a4e-8ab2-efb2ee95b732" />
<img width="1232" height="447" alt="winspdp" src="https://github.com/user-attachments/assets/b91381b5-3634-45e8-9551-af0a461ef51e" />
<img width="989" height="390" alt="winale" src="https://github.com/user-attachments/assets/55394633-08fd-4488-9ef0-265a3f8711bc" />


