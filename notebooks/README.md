# Notebooks

Experimental notebooks for the paper:
**ML Anomaly Detection in Cloud Environments using CSE-CIC-IDS2018**

## Execution Order

| Notebook | Description |
|---|---|
| 01_descarga_datos | Download 5 CSV files from AWS S3 |
| 02_preprocesamiento | Cleaning, normalization, feature selection |
| 03_isolation_forest | Isolation Forest training and evaluation |
| 04_autoencoder | Autoencoder with dynamic threshold P95 |
| 05_one_class_svm | One-Class SVM with GridSearch |
| 06_lstm_autoencoder | LSTM Autoencoder on GPU A100 |
| 07_comparacion_resultados | Comparative table of all models |
| 08_figuras_paper | All figures for the paper |

## Requirements

- Google Colab Pro (GPU A100 for notebook 06)
- Google Drive mounted at /content/drive
- Run notebooks in order from 01 to 08
