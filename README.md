# Proyek Data Analytics

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
    git clone https://github.com/username/repo.git
    ```

2. Instalasi Kaggle dan konfigurasi Kaggle diperlukan sebelum menggunakan dataset. Langkah-langkahnya dapat ditemukan di dokumentasi Kaggle.

## Cara Menjalankan Aplikasi
1. Buka terminal atau command prompt.
2. Arahkan ke direktori proyek.
3. Jalankan perintah: 
    ```
    streamlit run main.py
    ```
4. Buka browser dan akses alamat `http://localhost:8501`.
