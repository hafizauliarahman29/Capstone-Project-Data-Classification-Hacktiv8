# Capstone-Project-Data-Hacktiv8

**Hafiz Aulia Rahman**  
**Customer Churn Prediction & Clustering using K-Means**

## 📌 Project Overview
Proyek ini bertujuan untuk menganalisis dan mengelompokkan pelanggan berdasarkan perilaku dan karakteristik mereka dalam dataset **Telco Customer Churn**. Dengan memahami pola-pola tertentu, perusahaan dapat mengidentifikasi pelanggan yang berisiko berhenti (*churn*) dan merancang strategi retensi yang lebih efektif.

## 📂 Dataset
Dataset yang digunakan adalah **[Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)** dari Kaggle.  
Dataset ini berisi informasi **7.043 pelanggan** layanan telekomunikasi, mencakup:
- Data demografis (usia, status pensiun, jenis kelamin, dll.)
- Informasi langganan layanan (jenis kontrak, layanan internet, telepon, dll.)
- Data tagihan (biaya bulanan, total biaya)
- Status churn (Ya/Tidak)

## 📊 Insights & Findings
- Pelanggan dikelompokkan menjadi **tiga klaster utama** berdasarkan variabel numerik seperti `tenure`, `MonthlyCharges`, `TotalCharges`, dan `SeniorCitizen`:
    - **Cluster 0**: Pelanggan baru dengan biaya bulanan sedang, risiko churn tinggi.
    - **Cluster 1**: Pelanggan lama dengan biaya bulanan rendah, risiko churn rendah.
    - **Cluster 2**: Pelanggan lama dengan biaya bulanan tinggi, biasanya pengguna layanan lengkap.
- Visualisasi 3D scatter plot menunjukkan distribusi pelanggan per klaster berdasarkan karakteristik numerik.

## 🤖 AI Support Explanation

**Algoritma:**
- **K-Means Clustering** digunakan untuk mengelompokkan pelanggan berdasarkan kesamaan perilaku tanpa label churn.
- Pendekatan ini membantu mengidentifikasi segmen pelanggan dengan lebih objektif dan cepat.

**Library Python:**
- `pandas` untuk manipulasi data
- `scikit-learn` untuk preprocessing dan clustering
- `matplotlib` dan `seaborn` untuk visualisasi data

Dengan bantuan analisis berbasis AI dan visualisasi, perusahaan telekomunikasi dapat membuat strategi retensi yang lebih efektif untuk mengurangi churn.
