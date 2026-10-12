# Hi, I'm Faris Alzahrani

Computer Science student at King Abdulaziz University in Jeddah, Saudi Arabia (graduating December 2026).

I like taking a model through the whole workflow, from raw data to something reproducible: preprocessing, feature engineering, training, honest evaluation and deployment.

## Current focus

- Building end-to-end ML pipelines in Python with PyTorch and TensorFlow
- Time-series forecasting, tabular modeling and computer vision
- Evaluation that holds up: proper splits, leakage checks, and reporting what the code actually shows

## Tech stack

- **Languages:** Python
- **Deep learning:** PyTorch, TensorFlow
- **Machine learning:** scikit-learn, LightGBM, XGBoost, CatBoost
- **Experimentation and explainability:** MLflow, Optuna, SHAP
- **Data:** Pandas, NumPy, MySQL, MongoDB
- **Tooling:** Docker, Git

## Projects

### [energy-forecasting](https://github.com/Faris-z/energy-forecasting)
Hourly household energy forecasting on the UCI dataset (2M+ rows). Compares XGBoost, LightGBM, CatBoost, an LSTM and an ensemble against ARIMA and Prophet baselines, using 51 engineered features (lags, rolling stats, Fourier terms). Optuna tuning with walk-forward RMSE, MLflow tracking, Docker. Results: TODO, pending fixes to the evaluation setup documented in the README.

### [pneumonia-xray-detector](https://github.com/Faris-z/pneumonia-xray-detector)
Fine-tuned EfficientNet-B4 (PyTorch, transfer learning) to classify chest X-rays as Normal or Pneumonia. On the 624-image test set: 94.71% accuracy and 0.958 F1 (from a 1-epoch run; details and caveats in the README).

### [spotify-hit-predictor](https://github.com/Faris-z/spotify-hit-predictor)
Hit prediction on 89,740 Spotify tracks with 6 engineered audio features. Tuned XGBoost reaches 0.8375 ROC-AUC and 0.5933 F1 on a held-out test set. SHAP for explanations, and K-Means with PCA and t-SNE to find 5 song archetypes.

## Contact

- LinkedIn: https://www.linkedin.com/in/faris-alzahrani-dev
- Email: fys.alzahrani@gmail.com
  
