# Klasifikasi Penyakit Diabetes Menggunakan Metode Support Vector Machine (SVM) dan Extreme Gradient Boosting (XGBoost)

# Pendahuluan
Diabetes mellitus adalah penyakit kronis yang terus meningkat secara global dan dapat menyebabkan komplikasi serius seperti penyakit jantung dan stroke. Diagnosis dini sangat penting, tetapi metode konvensional seperti tes gula darah sering kurang sensitif pada tahap awal.

# Metode yang Digunakan
1. Support Vector Machine (SVM): Mencari hyperplane optimal untuk memisahkan kelas data.
2. XGBoost: Algoritma berbasis pohon keputusan yang meningkatkan akurasi prediksi.

# Dataset
Dataset "Diabetes Prediction Dataset" dari Kaggle berisi informasi kesehatan pasien untuk memprediksi kemungkinan diabetes. Dataset ini terdiri dari 100.000 baris dan 9 fitur utama, seperti usia, jenis kelamin, BMI, hipertensi, penyakit jantung, dan kadar glukosa darah.

# Pengolahan Data
Data diproses menggunakan Google Colab dengan library seperti pandas, numpy, matplotlib, dan seaborn. Langkah utama:
1. Pemeriksaan Statistik: Analisis deskriptif untuk memahami data.
2. Pembersihan Data: Menghapus duplikat untuk menjaga integritas dataset.
3. Eksplorasi Data: Visualisasi distribusi dan hubungan antar variabel.
4. Penyeimbangan Data: Metode sampling untuk distribusi kelas yang lebih merata.
5. Transformasi Fitur: Konversi fitur kategori ke format numerik dengan LabelEncoder.

# Model Machine Learning
Model SVM dan XGBoost digunakan untuk membangun sistem prediksi diabetes, dengan evaluasi model untuk mengukur kinerja klasifikasinya.

Penelitian ini bertujuan untuk meningkatkan akurasi deteksi dini diabetes dan memberikan alat diagnostik yang lebih andal bagi profesional kesehatan.
