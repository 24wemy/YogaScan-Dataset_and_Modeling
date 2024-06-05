# <center> Yoga Pose Recognition using MobileNetV2 </center>

<p align="center">
  <img src="https://img.shields.io/badge/Built%20with-TensorFlow-orange.svg" alt="Built with TensorFlow">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
</p>

## Deskripsi Proyek
Proyek ini adalah sistem pengenalan posisi yoga menggunakan MobileNetV2, sebuah arsitektur jaringan neural yang dioptimalkan untuk tugas-tugas visi komputer. Sistem ini dapat memprediksi posisi yoga yang ditunjukkan dalam gambar dengan tingkat akurasi yang tinggi.

## Fitur Utama
- **Prediksi Posisi Yoga**: Sistem dapat memprediksi posisi yoga yang ditunjukkan dalam gambar menggunakan model MobileNetV2 yang telah dilatih.
- **Tampilan Grafis**: Grafik akurasi dan loss selama pelatihan model disertakan untuk memantau kinerja model.
- **Penggunaan Mudah**: Proyek ini mudah untuk digunakan dengan Google Colab dan dapat diakses dari browser web.

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
- Python 3.6+
- Jupyter Notebook atau Google Colab
- Library Python: TensorFlow, Keras, NumPy, Matplotlib, scikit-learn, Pillow


## Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).
