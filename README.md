# Proyek Capstone Modul 2

Repositori ini berisi Jupyter Notebook untuk Proyek Capstone Modul 2, yang berfokus pada analisis data. Proyek ini mencakup SQL, manipulasi data, visualisasi data, dan analisis statistik. Temuan didokumentasikan dalam notebook, dan dashboard Tableau Public dibuat untuk representasi visual.

## Gambaran Proyek
## Proyek Overview

Proyek ini bertujuan untuk menganalisis demografi pengguna, perilaku pembayaran, dan pola perjalanan pengguna TransJakarta untuk memberikan wawasan dan rekomendasi strategi bisnis.
Tujuan dari proyek ini adalah untuk menerapkan materi yang telah dipelajari dari kursus untuk membuat serangkaian analisis. Proyek ini melibatkan:
- Ekstraksi dan manipulasi data
- Visualisasi data
- Analisis statistik
- Pembuatan dashboard
- Penyampaian wawasan

## Analisis Data Transjakarta

### Pendahuluan

#### Latar Belakang
Transjakarta adalah perusahaan transportasi umum dari Indonesia yang berbasis di Jakarta. Moda transportasi yang tersedia adalah bus besar (BRT), bus sedang dan bus besar (non-BRT), bus mini (Mikrotrans). Mekanisme di Transjakarta adalah dengan Tap-In dan Tap-Out menggunakan kartu pembayaran sebagai tiket Anda. Layanan ini dirancang untuk menyediakan transportasi publik yang efisien dan nyaman bagi penduduk Jakarta. Dalam upaya untuk meningkatkan pelayanan dan efisiensi operasional, analisis data perjalanan Transjakarta dapat memberikan wawasan berharga yang dapat membantu dalam pengambilan keputusan bisnis.

#### Rumusan Masalah
1. Bagaimana distribusi demografi pengguna Transjakarta?
2. Apa saja pola perjalanan pengguna Transjakarta?
3. Bagaimana rata-rata pembayaran pengguna berdasarkan jenis kelamin dan kelompok usia?

#### Tujuan Analisis
Tujuan dari analisis ini adalah untuk memahami berbagai aspek dari data perjalanan Transjakarta, termasuk:
- Demografi pengguna (jenis kelamin, usia, dan bank penerbit kartu).
- Pola perjalanan (jumlah perjalanan per koridor dan durasi perjalanan).
- Analisis pembayaran (rata-rata pembayaran per koridor).

Analisis ini mencakup pembersihan data, analisis deskriptif, dan analisis statistik inferensial untuk memberikan wawasan yang dapat membantu pengambilan keputusan bisnis.

## Isi

- `capstone_project_modul2_ Marcia.ipynb`: Jupyter Notebook utama yang berisi seluruh analisis dan dokumentasi proyek.
- `ANALISIS_TJ.pptx`: Presentasi yang menjelaskan analisis dan temuan proyek.
- `Transjakarta.csv`: Dataset yang digunakan untuk analisis.
- `Transjakarta.docx`: Dokumen yang mendukung analisis.
- `dataTJBersih.csv`: Dataset hasil pembersihan yang digunakan untuk Tableau.

## Persyaratan

Untuk menjalankan Jupyter Notebook, Anda memerlukan pustaka berikut:
- pandas
- numpy
- matplotlib
- seaborn
- sqlalchemy
- sqlite3
- plotly
- tableau_api_lib

# Cara Menjalankan

1. Clone repositori ini ke komputer lokal Anda:

    ```bash
    git clone https://github.com/marciadevana/CapstoneProjectModule02.git
    ```

2. Arahkan ke direktori proyek:

    ```bash
    cd CapstoneProjectModule02
    ```

3. Instal pustaka yang diperlukan (lihat bagian persyaratan).

4. Buka Jupyter Notebook:

    ```bash
    jupyter notebook capstone_project_modul2_Marcia.ipynb
    ```

5. Jalankan sel-sel dalam notebook untuk melihat analisis.

# Dashboard Tableau

Dashboard Tableau Public dapat diakses [di sini]((https://public.tableau.com/app/profile/marcia.devana/viz/Capstone_Project_Modul2_chia/Dashboard1)).

# Struktur Proyek

- **Pendahuluan**: Gambaran umum proyek dan tujuan.
- **Ekstraksi Data**: Kuery SQL dan teknik ekstraksi data.
- **Manipulasi Data**: Pembersihan dan transformasi data.
- **Visualisasi Data**: Representasi visual data menggunakan berbagai pustaka plot.
- **Analisis Statistik**: Penerapan metode statistik untuk mendapatkan wawasan.
- **Dashboard**: Pembuatan dashboard menggunakan Tableau Public.
- **Kesimpulan**: Ringkasan temuan dan wawasan.

# Kontak

Untuk pertanyaan atau umpan balik, silakan hubungi saya di marciadevana20@gmail.com

# Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT - lihat file LICENSE untuk detailnya.



