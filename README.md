# 🧠 Naive Bayes - Analisis Penyakit Jantung

Ini adalah proyek tugas mata kuliah **Artificial Intelligence** yang bertujuan untuk melakukan analisis dan klasifikasi penyakit jantung menggunakan algoritma **Naive Bayes**.

## 📌 Deskripsi Singkat

Model klasifikasi Naive Bayes digunakan untuk memprediksi apakah seseorang memiliki penyakit jantung berdasarkan sejumlah fitur medis. Proyek ini dibuat di Google Colab menggunakan bahasa pemrograman **Python** dengan bantuan pustaka data science seperti `pandas`, `scikit-learn`, dan `matplotlib`.

## 📊 Dataset

Dataset yang digunakan berisi informasi medis dari 890 pasien dan memiliki 16 fitur:

| No | Fitur       | Deskripsi                                |
|----|-------------|-------------------------------------------|
| 1  | `id`        | ID pasien                                 |
| 2  | `age`       | Usia                                      |
| 3  | `sex`       | Jenis kelamin                             |
| 4  | `cp`        | Tipe nyeri dada                           |
| 5  | `trestbps`  | Tekanan darah istirahat                   |
| 6  | `chol`      | Kadar kolesterol                          |
| 7  | `fbs`       | Gula darah puasa                          |
| 8  | `restecg`   | Hasil elektrokardiografi saat istirahat   |
| 9  | `thalch`    | Detak jantung maksimal                    |
| 10 | `exang`     | Angina yang disebabkan oleh olahraga      |
| 11 | `oldpeak`   | Depresi ST akibat olahraga                |
| 12 | `slope`     | Kemiringan segmen ST                      |
| 13 | `ca`        | Jumlah pembuluh darah besar berwarna      |
| 14 | `thal`      | Thalassemia                               |
| 15 | `num`       | Target (indikator penyakit jantung)       |

Beberapa kolom memiliki missing value dan perlu diproses terlebih dahulu sebelum model training dilakukan.

## 🔍 Metodologi

Langkah-langkah dalam proyek ini:
1. **Pra-pemrosesan data**
   - Menangani missing value
   - Encoding data kategorikal
2. **Split dataset**
   - Training dan testing
3. **Pelatihan model**
   - Menggunakan Naive Bayes dari `scikit-learn`
4. **Evaluasi model**
   - Menggunakan metrik akurasi, confusion matrix, dan visualisasi

## 🛠 Teknologi yang Digunakan

- Python (Google Colab)
- pandas
- numpy
- scikit-learn
- matplotlib

## 📁 File

- `NaiveBayes_Penyakit_Jantung.ipynb` – Notebook utama yang berisi seluruh proses analisis dan model.

## ✍️ Penulis

> Nama: Lisa Kristania
> NIM: 202201058
> Prodi : Sistem Informasi
> Mata kuliah: Artificial Intelligence

---

