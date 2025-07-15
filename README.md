Aplikasi web lokal yang mengimplementasikan model machine learning untuk memprediksi kelayakan kredit nasabah berdasarkan data personal dan finansial. Proyek ini mendemonstrasikan alur kerja end-to-end, mulai dari pengembangan model, pembuatan API, hingga antarmuka pengguna yang interaktif.

Deskripsi Proyek
Proyek ini bertujuan untuk membangun sebuah sistem prediktif menggunakan model klasifikasi Random Forest. Model dilatih menggunakan dataset dari Kaggle di dalam lingkungan Jupyter Notebook.
Untuk membuat model ini fungsional, sebuah API sederhana dibangun menggunakan Flask (Python) untuk melayani permintaan prediksi. Antarmuka pengguna (front-end) dibuat menggunakan HTML, CSS, dan JavaScript, yang memungkinkan pengguna memasukkan data dan menerima hasil prediksi secara langsung di browser.
Seluruh arsitektur proyek ini dirancang untuk berjalan sepenuhnya secara lokal, memastikan tidak ada data yang dikirim ke server eksternal dan menjaga privasi pengguna.

Fitur Utama
Prediksi Real-Time Lokal: Memberikan prediksi kelayakan kredit secara instan melalui API Flask yang berjalan di lingkungan lokal.
Arsitektur Lokal (Local-First): Seluruh aplikasi, dari antarmuka web hingga API machine learning, dirancang untuk dijalankan secara mandiri di komputer lokal.
Antarmuka Interaktif: Desain web yang sederhana dan bersih memudahkan pengguna untuk memasukkan data dan memahami hasil prediksi.

Teknologi yang Digunakan
Machine Learning & Analisis Data:
Python
Scikit-learn (Implementasi Random Forest)
Pandas (Manipulasi Data)
Jupyter Notebook (Eksplorasi & Pengembangan Model)

Back-End (API):
Flask
Front-End:
HTML
CSS
JavaScript

Arsitektur & Alur Kerja
Back-End: Sebuah server Flask (app.py) berjalan dan memuat model machine learning yang telah dilatih (misalnya, file .pkl).
Front-End: Pengguna membuka file index.html di browser.
Interaksi: Pengguna mengisi formulir dengan data yang dibutuhkan.\
Request: JavaScript pada front-end mengirimkan data dari formulir ke endpoint API Flask yang berjalan di localhost.
Prediksi: Server Flask menerima data, memprosesnya, dan memberikannya ke model untuk mendapatkan hasil prediksi.
Response: API mengembalikan hasil prediksi (misalnya, "Layak" atau "Tidak Layak") ke front-end.
Tampilan Hasil: JavaScript menampilkan hasil prediksi kepada pengguna di halaman web.
