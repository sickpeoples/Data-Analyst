🚴‍♀️ Ford GoBike Data Analysis Februari 2019

📄 Deskripsi Proyek
Proyek ini merupakan analisis eksploratif terhadap dataset Ford GoBike (Februari 2019), layanan bike-sharing yang beroperasi di wilayah San Francisco Bay Area.
Analisis ini bertujuan untuk memahami pola penggunaan sepeda, mengidentifikasi stasiun dengan tingkat aktivitas tertinggi dan terendah, serta memberikan rekomendasi bisnis berbasis data.

🎯 Tujuan Analisis
Menentukan stasiun mana yang paling sering digunakan sebagai titik keberangkatan dan tujuan.
Menganalisis pola durasi perjalanan dan waktu penggunaan sepeda.
Mengidentifikasi potensi perbaikan infrastruktur dan strategi bisnis berdasarkan perilaku pengguna.

🧩 Proses Analisis
Analisis dilakukan menggunakan Python (pandas, matplotlib, seaborn) dalam format Jupyter Notebook (.ipynb).
Tahapan utama meliputi:

Data Cleaning
Menghapus data kosong dan duplikat.
Standarisasi format kolom (lowercase, underscore).
Konversi tipe data dan validasi durasi waktu.
Eksplorasi Data (EDA)
Analisis distribusi durasi perjalanan.
Identifikasi stasiun paling ramai dan paling sepi.
Visualisasi korelasi antar variabel numerik dan hubungan antar stasiun.
Insight dan Rekomendasi
Temuan utama divisualisasikan menggunakan bar chart, heatmap, dan histogram.
Dihasilkan beberapa peluang bisnis untuk peningkatan operasional dan strategi layanan.

🔍 Hasil Utama
San Francisco Ferry Building menjadi stasiun paling ramai digunakan (baik keberangkatan maupun tujuan).
16th St Depot dan Palm St at Willow St merupakan stasiun dengan tingkat aktivitas terendah.
Mayoritas perjalanan berdurasi kurang dari 15 menit, sesuai karakteristik transportasi jarak pendek.
Tidak ditemukan korelasi linear langsung antara start_time/end_time dengan duration_sec, namun terdapat pola jam sibuk tertentu yang menarik untuk dianalisis lebih lanjut.

💡 Rekomendasi Bisnis
Tambah kapasitas sepeda dan docking station di area dengan permintaan tinggi.
Evaluasi lokasi stasiun dengan aktivitas rendah untuk efisiensi operasional.
Terapkan redistribusi sepeda otomatis di jam sibuk.
Buat strategi promosi berbeda bagi pengguna subscriber (komuter) dan customer kasual (rekreasi).
Kembangkan kerja sama dengan bisnis lokal di sekitar stasiun populer untuk memperluas ekosistem layanan.

🧠 Tools dan Teknologi
Python (pandas, matplotlib, seaborn, numpy)
Jupyter Notebook (.ipynb)
Excel (.xlsx) untuk eksplorasi tambahan
PDF Report (.pdf) untuk dokumentasi hasil analisis
