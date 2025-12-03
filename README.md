# Eksplorasi dan Visualisasi Data - Project Dashboard
# Indonesia News
<img width="1070" height="2000" alt="Image" src="https://github.com/user-attachments/assets/dfb3fa50-6318-4baf-9c8a-38853387f830" />

# 📰 Analisis Topik Pemberitaan Media Online Indonesia 2024–2025

<img width="1426" height="152" alt="Image" src="https://github.com/user-attachments/assets/b0cfdeaf-1cf5-480e-8f93-5c41fac3fb1e" />

Proyek ini berisi dashboard interaktif yang menganalisis berita online dari beberapa portal media nasional Indonesia seperti Detik, Kompas, dan Tempo sepanjang tahun 2024–2025. Dashboard dibangun menggunakan metode Latent Dirichlet Allocation (LDA) dan pendekatan lexicon sederhana untuk mengelompokkan topik-topik utama dalam pemberitaan nasional.



# 🎯 Tujuan Dashboard

### Dashboard ini dirancang untuk memberikan gambaran menyeluruh mengenai:
- Tren jumlah berita dan portal yang paling aktif dari waktu ke waktu.
- Kata-kata kunci (keywords) yang paling sering muncul pada judul berita.
- Distribusi topik utama seperti Politik, Ekonomi, Sosial, beserta kata kunci dominannya.
- Contoh judul berita pada setiap topik, lengkap dengan sumber dan tautan artikelnya.

Dashboard memudahkan pengguna memahami arah pemberitaan nasional melalui visualisasi yang ringkas dan interaktif.


# 🗂️ Sumber Data

Data didapat dari Kaggle dengan cara dikumpulkan dari portal berita nasional melalui proses web scraping dan pembaruan berkala:
- detik.com
- kompas.com
- tempo.co


Setiap artikel diproses melalui tahapan:

- ekstraksi judul dan metadata,
- pembersihan teks,
- tokenisasi dan preprocessing NLP,
- pemodelan topik menggunakan LDA.


Proyek ini menampilkan rangkuman umum terkait aktivitas pemberitaan dari tiga portal media online Indonesia. Informasi yang disajikan meliputi total jumlah berita, jumlah sumber berita, rentang waktu data, serta rata-rata berita per hari.
Selain itu, juga memuat visualisasi tren jumlah berita per bulan, daftar kata yang paling sering muncul pada judul berita, serta portal berita yang paling aktif selama periode analisis. Visualisasi ini bertujuan memberikan gambaran awal mengenai pola publikasi berita sebelum dilakukan analisis topik pada bagian berikutnya.

# 🔎 Topic Modeling

Pada bagian Topic Modeling, proyek ini menampilkan hasil pengelompokan berita menjadi beberapa topik utama menggunakan metode Latent Dirichlet Allocation (LDA) yang dipadukan dengan pendekatan lexicon sederhana. Analisis ini digunakan untuk melihat struktur tema besar dalam pemberitaan media online Indonesia sepanjang 2024–2025.

- Distribusi Proporsi Topik
  Menunjukkan persentase berita yang termasuk dalam masing-masing topik utama (misalnya: Politik, Ekonomi, dan Sosial). Grafik ini memberikan gambaran topik apa yang paling dominan
  dalam pemberitaan.
- Ringkasan Kata Kunci Utama
  Menyajikan daftar kata kunci paling representatif pada setiap topik. Ringkasan ini membantu memahami karakteristik konten dari masing-masing kategori berita.
- Top Terms per Topik (LDA + Lexicon)
  Menggambarkan kata-kata teratas yang memiliki kontribusi terbesar dalam pembentukan topik tertentu. Fitur ini dapat disesuaikan jumlah kata yang ditampilkan.
- WordCloud per Topik
  Visualisasi awan kata untuk setiap topik, sehingga kata paling menonjol mudah dilihat secara intuitif.
- Tren Kekuatan Topik dari Waktu ke Waktu
  Menampilkan bagaimana proporsi topik tertentu berubah sepanjang periode analisis. Grafik ini membantu memahami dinamika isu yang naik atau turun trennya.
- Contoh Judul Berita per Topik
  Berisi daftar contoh judul berita yang termasuk dalam topik yang dipilih, lengkap dengan sumber dan tautan asli. Ditampilkan dalam tabel yang interaktif.

------

# 👥 Team 










