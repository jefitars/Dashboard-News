# Eksplorasi dan Visualisasi Data - Project Dashboard
# Indonesia News
<img width="1438" height="824" alt="Image" src="https://github.com/user-attachments/assets/0dfdc833-4bf2-4446-b625-f61b74b83de0" />

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
  
  <img width="954" height="288" alt="Image" src="https://github.com/user-attachments/assets/45892733-a038-4836-a0d6-ae9110963fb7" />

  
- Ringkasan Kata Kunci Utama
  Menyajikan daftar kata kunci paling representatif pada setiap topik. Ringkasan ini membantu memahami karakteristik konten dari masing-masing kategori berita.

    <p align="center">
  <img width="713" height="187" alt="Image" src="https://github.com/user-attachments/assets/86133ea4-e12d-4f6e-b60a-c1a468358843" />
</p>

  
- Top Terms per Topik (LDA + Lexicon)
  Menggambarkan kata-kata teratas yang memiliki kontribusi terbesar dalam pembentukan topik tertentu. Fitur ini dapat disesuaikan jumlah kata yang ditampilkan.
  
 <p align="center">
  <img width="707" height="212" alt="Image" src="https://github.com/user-attachments/assets/331e6a28-ef9c-43dc-87fc-e56c76206a2e" />
</p>

  
- WordCloud per Topik
  Visualisasi awan kata untuk setiap topik, sehingga kata paling menonjol mudah dilihat secara intuitif.

<p align="center">
  <img width="281" height="177" alt="Image" src="https://github.com/user-attachments/assets/5bba84d5-ace1-439a-862a-773bf83ba727" />
</p>

  
- Tren Kekuatan Topik dari Waktu ke Waktu
  Menampilkan bagaimana proporsi topik tertentu berubah sepanjang periode analisis. Grafik ini membantu memahami dinamika isu yang naik atau turun trennya.
  
  <p align="center">
  <img width="704" height="270" alt="Image" src="https://github.com/user-attachments/assets/d207cf72-3a3e-42cc-84d4-d53ecec7efa1" />
</p>


  
- Contoh Judul Berita per Topik
  Berisi daftar contoh judul berita yang termasuk dalam topik yang dipilih, lengkap dengan sumber dan tautan asli. Ditampilkan dalam tabel yang interaktif.
  
  <img width="1425" height="331" alt="Image" src="https://github.com/user-attachments/assets/f467ca1d-7e02-4577-9cfc-5ce6b5902120" />

------

# 👥 Team 

<img width="1444" height="323" alt="Image" src="https://github.com/user-attachments/assets/7dd220d6-1e50-47a4-aaf2-c2bcae46cb41" />










