# Cyber-Login-Classification

# 🔐 Kelompok 4 - EAS
## Klasifikasi Aktivitas Login Normal dan Mencurigakan Berdasarkan Pola Waktu, Lokasi, dan Perangkat

## 📖 Deskripsi Proyek

Proyek ini merupakan tugas **Statistika dan Analitika Data Siber Bisnis** yang bertujuan mengklasifikasikan aktivitas login pengguna menjadi **Normal** atau **Mencurigakan (Suspicious)** berdasarkan pola waktu login, lokasi, perangkat yang digunakan, serta atribut autentikasi lainnya.

Model klasifikasi dibangun menggunakan algoritma **Random Forest Classifier** dan dievaluasi menggunakan **Confusion Matrix**, **Accuracy**, **Precision**, **Recall**, dan **F1-Score**.

---

## 🎯 Tujuan

- Mengidentifikasi aktivitas login normal dan mencurigakan.
- Menganalisis pengaruh waktu, lokasi, dan perangkat terhadap aktivitas login.
- Membangun model klasifikasi menggunakan machine learning.

---

## 📂 Dataset

**Authentication & Authorization Failures Dataset**

Dataset terdiri dari sekitar **50.000 data** dengan **25 atribut**, antara lain:

- Timestamp
- Device Type
- Operating System
- Browser
- Location
- Login Method
- Failed Attempts
- Account Status
- MFA Enabled
- Privilege Level
- Suspicious Activity
- Threat Level

---

## 🛠 Tools

- Google Colab
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🤖 Algoritma

- Random Forest Classifier

---

## 📊 Evaluasi Model

Evaluasi dilakukan menggunakan:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📁 Struktur Repository

```
Cyber-Login-Classification/
│
├── auth_authz_failures_dataset.csv
├── Kelompok 4-EAS.ipynb
└── README.md
```

---

## 🚀 Cara Menjalankan

1. Clone atau download repository.
2. Buka file **Kelompok 4-EAS.ipynb** menggunakan Google Colab.
3. Jalankan seluruh cell.
4. Notebook akan mengambil dataset langsung dari repository GitHub.

---

## 📌 Output

Notebook menghasilkan:

- Exploratory Data Analysis (EDA)
- Distribusi Data
- Accuracy
- Classification Report
- Confusion Matrix
- Feature Importance

---

## 👥 Kelompok 4 

Mata Kuliah **Statistika dan Analitika Data Siber Bisnis**

Anggota kelompok :
1. Reva Olinda Primalia (1482400025)
2. Febry Putri Agus Damayanti (1482400038)
3. Mei Maharani (1482400078)
4. Chelsea Sarah Jeanita Panjaitan (1482400094)
