🌍 SKPU Air Pollution Prediction with SVM

Proyek ini merupakan implementasi Sistem Klasifikasi/Predictive Udara (SKPU) untuk memprediksi tingkat polusi udara menggunakan algoritma Support Vector Machine (SVM).
Dataset yang digunakan berisi indikator kualitas udara seperti konsentrasi gas, partikel, serta parameter lingkungan lain yang relevan.

📌 Tujuan

Mengklasifikasikan kualitas udara berdasarkan data sensor atau dataset publik.

Membandingkan performa model SVM dengan baseline model lain.

Menyediakan insight yang dapat membantu pengambilan keputusan terkait kesehatan lingkungan.

🗂️ Dataset

Dataset yang digunakan:

Air Pollution Dataset (contoh: UCI / Kaggle)

Fitur utama:

PM2.5, PM10, NO2, SO2, CO, O3

Suhu, kelembaban, tekanan udara

Label: kategori kualitas udara (Good, Moderate, Unhealthy, Hazardous).

🛠️ Tech Stack

Python 3.x

Scikit-learn (SVM, preprocessing, metrics)

Pandas & NumPy (data handling)

Matplotlib & Seaborn (visualisasi data)

Jupyter Notebook (eksperimen & dokumentasi)

⚙️ Langkah Analisis

Data Preprocessing

Handling missing values

Normalisasi data

Feature selection

Modeling

Support Vector Machine (SVM)

Hyperparameter tuning (GridSearchCV)

Evaluation

Accuracy, Precision, Recall, F1-Score

Confusion Matrix

Visualisasi hasil prediksi

📊 Hasil (contoh)

SVM Accuracy: 0.87

F1-Score: 0.85

Model menunjukkan performa yang baik dalam mengklasifikasikan kualitas udara.
