# Ford GoBike Data Analysis Februari 2019

**Deskripsi Proyek**

Proyek ini merupakan analisis eksploratif terhadap dataset Ford GoBike (Februari 2019), layanan bike-sharing yang beroperasi di wilayah San Francisco Bay Area.
Analisis ini bertujuan untuk memahami pola penggunaan sepeda, mengidentifikasi stasiun dengan tingkat aktivitas tertinggi dan terendah, serta memberikan rekomendasi bisnis berbasis data.

**Tujuan Analisis**

Menentukan stasiun mana yang paling sering digunakan sebagai titik keberangkatan dan tujuan.
Menganalisis pola durasi perjalanan dan waktu penggunaan sepeda.
Mengidentifikasi potensi perbaikan infrastruktur dan strategi bisnis berdasarkan perilaku pengguna.

**Proses Analisis**

Analisis dilakukan menggunakan Python (pandas, matplotlib, seaborn) dalam format Jupyter Notebook (.ipynb).
Tahapan utama meliputi:

1. Data Cleaning
2. Menghapus data kosong dan duplikat.
3. Standarisasi format kolom (lowercase, underscore).
4. Konversi tipe data dan validasi durasi waktu.
5. Eksplorasi Data (EDA)
6. Analisis distribusi durasi perjalanan.
7. Identifikasi stasiun paling ramai dan paling sepi.
8. Visualisasi korelasi antar variabel numerik dan hubungan antar stasiun.
9. Insight dan Rekomendasi
10. Temuan utama divisualisasikan menggunakan bar chart, heatmap, dan histogram.
11. Dihasilkan beberapa peluang bisnis untuk peningkatan operasional dan strategi layanan.

**Hasil Utama**

1. San Francisco Ferry Building menjadi stasiun paling ramai digunakan (baik keberangkatan maupun tujuan).
2. 16th St Depot dan Palm St at Willow St merupakan stasiun dengan tingkat aktivitas terendah.
3. Mayoritas perjalanan berdurasi kurang dari 15 menit, sesuai karakteristik transportasi jarak pendek.
4. Tidak ditemukan korelasi linear langsung antara start_time/end_time dengan duration_sec, namun terdapat pola jam sibuk tertentu yang menarik untuk dianalisis lebih lanjut.

**Rekomendasi Bisnis**

1. Tambah kapasitas sepeda dan docking station di area dengan permintaan tinggi.
2. Evaluasi lokasi stasiun dengan aktivitas rendah untuk efisiensi operasional.
3. Terapkan redistribusi sepeda otomatis di jam sibuk.
4. Buat strategi promosi berbeda bagi pengguna subscriber (komuter) dan customer kasual (rekreasi).
5. Kembangkan kerja sama dengan bisnis lokal di sekitar stasiun populer untuk memperluas ekosistem layanan.

**Tools dan Teknologi**

1. Python (pandas, matplotlib, seaborn, numpy)
2. Jupyter Notebook (.ipynb)
3. Excel (.xlsx) untuk eksplorasi tambahan
4. PDF Report (.pdf) untuk dokumentasi hasil analisis
