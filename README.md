# Klasifikasi Gambar Batu-Gunting-Kertas

Proyek ini adalah bagian dari **Submission Proyek Akhir** untuk kelas **Belajar Machine Learning untuk Pemula** di Dicoding. Program ini menggunakan Convolutional Neural Network (CNN) untuk melakukan klasifikasi gambar tangan yang membentuk tiga kategori: batu, gunting, atau kertas. Proyek ini dirancang untuk dijalankan langsung di Jupyter Notebook atau Google Colab.

## Fitur Utama

- **Klasifikasi Gambar**: Mampu mengenali gambar tangan yang membentuk batu, gunting, atau kertas.
- **Model yang Terlatih**: Menggunakan CNN yang dilatih dengan dataset batu-gunting-kertas.
- **Kompatibilitas**: Dirancang untuk dijalankan pada Jupyter Notebook atau Google Colab.

## Teknologi yang Digunakan

- **Bahasa Pemrograman**: Python
- **Framework Machine Learning**: TensorFlow dan Keras
- **Visualisasi**: Matplotlib untuk analisis hasil model
- **Platform**: Google Colab atau Jupyter Notebook

## Dataset

Dataset yang digunakan dalam proyek ini adalah dataset _rock-paper-scissors_ yang disediakan oleh Dicoding. Dataset ini dapat diunduh secara otomatis dengan menggunakan perintah berikut di dalam notebook:

```python
!wget --no-check-certificate \
    https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip \
    -O /tmp/rockpaperscissors.zip
```

````

Dataset ini berisi gambar tangan manusia yang membentuk tiga kategori: batu, gunting, dan kertas.

## Langkah-Langkah Penggunaan

1. **Clone Repository**
   Clone repository ini ke komputer Anda:

   ```bash
   git clone https://github.com/Ysfii-Dev/Image-Classification.git
   cd rock-paper-scissors-classifier
   ```

2. **Buka Google Colab atau Jupyter Notebook**
   Pastikan Anda memiliki akses ke Google Colab atau Jupyter Notebook.

3. **Salin atau Unduh Notebook**
   Salin atau unduh file notebook (.ipynb) proyek ini ke Google Colab atau lokal Anda.

4. **Instal Dependensi (Jika Diperlukan)**
   Pastikan semua dependensi telah terpasang. Jika menggunakan Google Colab, TensorFlow dan dependensi lainnya biasanya sudah tersedia. Anda hanya perlu menjalankan:

   ```python
   !pip install matplotlib seaborn
   ```

5. **Unduh Dataset**
   Unduh dan ekstrak dataset menggunakan perintah berikut di dalam notebook:

   ```python
   import zipfile
   !wget --no-check-certificate \
       https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip \
       -O /tmp/rockpaperscissors.zip
   with zipfile.ZipFile('/tmp/rockpaperscissors.zip', 'r') as zip_ref:
       zip_ref.extractall('/tmp/')
   ```

6. **Latih Model**
   Jalankan semua sel di notebook untuk memuat dataset, melatih model CNN, dan mengevaluasi hasilnya.

7. **Evaluasi dan Visualisasi**
   Analisis akurasi dan loss model dengan grafik yang akan ditampilkan di notebook.

## Evaluasi Model

Model ini berhasil mencapai akurasi pelatihan hingga **95%** dengan loss minimal pada dataset pengujian.

## Kontak

Jika ada pertanyaan atau saran, Anda dapat menghubungi:

- **Nama**: Yusfi
- **Email**: yusfisyawali@gmail.com

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).
````
