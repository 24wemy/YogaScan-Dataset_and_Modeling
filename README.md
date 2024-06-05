# <center> Yoga Pose Recognition using Transfer Learning MobileNetV2 </center>

<p align="center">
  <img src="https://img.shields.io/badge/Built%20with-TensorFlow-orange.svg" alt="Built with TensorFlow">
</p>

## Deskripsi 
Inilah proses bagaimana kami melatih model machine learning kami untuk memprediksi gerakan yoga dengan menggunakan metode transfer learning pada Pre-Trained model MobileNetV2

## Proses Transfer Learning menggunakan MobileNetV2
Proses transfer learning menggunakan MobileNetV2 melibatkan langkah-langkah berikut:
1. **Memuat Model MobileNetV2**: Memuat model MobileNetV2 yang telah dilatih sebelumnya tanpa lapisan teratas.
2. **Menambahkan Lapisan Kustom**: Menambahkan lapisan kustom di atas model MobileNetV2 untuk pengenalan posisi yoga.
3. **Pembekuan Lapisan Awal**: Membekukan semua lapisan pada model MobileNetV2 untuk menjaga bobotnya tetap stabil selama pelatihan lapisan kustom.
4. **Pelatihan Model**: Melatih model dengan dataset posisi yoga menggunakan pelatihan lapisan kustom.

## Dataset
Dataset yang digunakan terdiri dari lima kelas posisi yoga yang berbeda:
1. **Boat Pose**
2. **Corpse Pose**
3. **Tree Pose**
4. **Plank Pose**
5. **Updog Pose**

Dataset tersedia di direktori "dataset" dalam repositori ini.

## Persyaratan
- <img src="https://img.shields.io/badge/Python-3.6+-blue.svg" alt="Python version">
- <img src="https://img.shields.io/badge/Jupyter-Notebook-orange.svg" alt="Jupyter Notebook">
- <img src="https://img.shields.io/badge/Library-TensorFlow-blue.svg" alt="TensorFlow">
- <img src="https://img.shields.io/badge/Library-Keras-blue.svg" alt="Keras">
- <img src="https://img.shields.io/badge/Library-NumPy-blue.svg" alt="NumPy">
- <img src="https://img.shields.io/badge/Library-Matplotlib-blue.svg" alt="Matplotlib">
- <img src="https://img.shields.io/badge/Library-scikit--learn-blue.svg" alt="scikit-learn">
- <img src="https://img.shields.io/badge/Library-Pillow-blue.svg" alt="Pillow">

