# Project Data Analytics
Projek ini menggunakan Streamlit sebagai alat untuk membuat visualisasi data yang interaktif dan dinamis. Dengan Streamlit, pengguna dapat dengan mudah menjelajahi dan menganalisis data dari Brazilian E-Commerce melalui antarmuka web yang ramah pengguna.
![Streamlit Logo](https://user-images.githubusercontent.com/7164864/217935870-c0bc60a3-6fc0-4047-b011-7b4c59488c91.png)

## Deskripsi

Repositori ini berisi proyek analisis data terhadap Brazilian E-Commerce yang divisualisasikan secara cloud melalui sebuah website. Tujuannya adalah untuk memberikan insight dan pemahaman mengenai informasi data.

## Sumber Data
Data yang digunakan berasal dari Kaggle Dataset brazilian-e-commerce, yang dapat diunduh [di sini](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## Struktur Direktori
- `/dataset`: Direktori yang berisi dataset dalam format .csv.
- `/streamlit`: Berisi file `main.py` yang merupakan kode utama dalam pembuatan visualisasi website.
- `notebook.ipynb`: File yang digunakan untuk melakukan analisis data.

## Instalasi
1. Clone repository ke komputer lokal Anda menggunakan perintah berikut:
    ```
    git clone https://github.com/Rahmanda07/Proyek-Analisis-Data-Dicoding.git
    ```

2. Lakukan Instalasi Kaggle dan Konfigurasi Kaggle API sesuai petunjuk pada dokumentasi Kaggle. Anda dapat mengunjungi [tautan ini](https://github.com/Kaggle/kaggle-api) untuk mendapatkan petunjuk instalasi Kaggle API.

3. Lakukan instalasi library yang diperlukan dengan perintah berikut:
    ```
    pip install streamlit numpy seaborn pandas matplotlib zipfile unidecode
    ```

## Cara Menjalankan Aplikasi
1. Buka terminal atau command prompt.
2. Arahkan ke direktori proyek:
    ```
    cd Proyek-Analisis-Data-Dicoding
    ```

3. Masuk ke direktori `streamlit`:
    ```
    cd streamlit
    ```

4. Jalankan perintah untuk memulai aplikasi Streamlit:
    ```
    streamlit run main.py
    ```
