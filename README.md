# Optimasi Model Prediksi Harga Saham PT Bank Negara Indonesia Tbk Menggunakan Support Vector Regression (SVR) dengan Tuning Hyperparameter

Pasar saham merupakan instrumen investasi yang menjanjikan namun memiliki tingkat risiko yang tinggi karena fluktuasi harga yang tidak dapat diprediksi dengan mudah. Dalam konteks ini, investor membutuhkan model prediksi yang andal untuk meminimalkan risiko dan memaksimalkan keuntungan. Salah satu perusahaan yang sahamnya aktif diperdagangkan di Bursa Efek Indonesia adalah PT Bank Negara Indonesia (Persero) Tbk (BBNI).

Support Vector Regression (SVR) merupakan salah satu metode machine learning yang efektif untuk menangani masalah regresi, terutama pada data yang memiliki hubungan non-linear. Dalam penggunaannya, performa SVR sangat dipengaruhi oleh pemilihan hyperparameter yang tepat. Oleh karena itu, penelitian ini mengusulkan pendekatan optimasi model SVR melalui tuning hyperparameter untuk meningkatkan akurasi prediksi harga saham BBNI.

## Sumber Data
Data diperoleh dari situs Kaggle melalui tautan https://www.kaggle.com/datasets/caesarmario/bank-negara-indonesia-stock-historical-price. 

## Modeling dan Evaluasi
1. Model SVR dilatih dengan data latih (train set).
2. Evaluasi awal dilakukan menggunakan MAE, RMSE, dan R².
3. Tuning hyperparameter dilakukan dengan GridSearchCV.

## Hasil 
Model awal SVR menunjukkan performa yang rendah dengan R² negatif. Setelah dilakukan tuning hyperparameter (C=100, epsilon=0.01, gamma=0.01), model menunjukkan peningkatan performa signifikan:
- MAE: 15.54
- RMSE: 26.67
- R²: 0.9969

Hal ini menunjukkan bahwa tuning hyperparameter sangat penting dalam meningkatkan akurasi model SVR untuk prediksi harga saham.
