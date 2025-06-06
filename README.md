# Klasifikasi Penyakit Daun Kentang Menggunakan CNN

Proyek ini merupakan implementasi model Convolutional Neural Network (CNN) untuk mendeteksi kondisi daun kentang ke dalam tiga kategori: Early Blight, Late Blight, dan Healthy. Model dikembangkan menggunakan TensorFlow dan Keras.

## Deskripsi

Model ini menerima input berupa gambar daun berukuran 256x256 piksel dan memprosesnya melalui beberapa lapisan konvolusi dan pooling untuk mengklasifikasikan jenis penyakit. Gambar diuji secara langsung melalui proses prediksi tanpa pelatihan ulang, sehingga model perlu dilatih terlebih dahulu sebelum digunakan secara optimal.

## Struktur File

| File                   | Deskripsi                                                                 |
|------------------------|--------------------------------------------------------------------------|
| `main.py`              | Berisi arsitektur CNN, proses pemuatan gambar, prediksi, dan visualisasi |
| `GambarDaun.jpg`       | Contoh gambar yang digunakan untuk proses prediksi                       |

## Teknologi

- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
