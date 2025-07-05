

# Netflix Titles Exploratory Data Analysis

Proyek ini dibuat karena Netflix merupakan salah satu platform streaming terbesar di dunia, dan dataset ini mencerminkan tren hiburan global yang relevan dengan minat saya di bidang data analitik.

Analisis data eksploratif untuk mengeksplorasi dataset judul Netflix, dengan tujuan menemukan pola dalam produksi konten, tren rilis tahunan, distribusi negara, serta genre yang populer.

Proyek ini menyajikan berbagai visualisasi data untuk membantu pengguna memahami perkembangan konten Netflix dari waktu ke waktu, perbedaan film dan serial, serta kontribusi berbagai negara dalam produksi.

Dibuat oleh: Davina Olivia

---

🎯 Fitur Analisis

=> Distribusi Film vs Serial TV 
Perbandingan jumlah judul film dan serial TV dalam platform Netflix.

=> Tren Produksi Berdasarkan Negara
Negara-negara yang paling banyak menghasilkan judul untuk Netflix.

=> Tren Tahun Rilis
Visualisasi jumlah judul yang dirilis setiap tahun dalam dataset.

=> Genre Populer
Identifikasi genre yang paling sering muncul pada konten Netflix.



📂 Struktur Folder
netflix_titles_project/
│
├── notebook/
│   └── Netflix_EDA_Portfolio.ipynb    # Notebook analisis utama
│
├── data/
│   └── netflix_titles.csv             # Dataset judul Netflix
│
└── README.md                          # Dokumentasi proyek
```



🗂️ Dataset
Dataset diambil dari [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows).
Data mencakup kolom-kolom berikut:

* show_id – ID unik setiap judul
* type – Jenis konten (Movie atau TV Show)
* title – Judul konten
* director – Nama sutradara
* cast – Pemeran utama
* country – Negara asal produksi
* date_added – Tanggal konten ditambahkan ke Netflix
* release_year – Tahun rilis resmi
* rating – Klasifikasi usia penonton
* duration – Durasi (menit atau jumlah season)
* listed_in – Genre atau kategori
* description – Deskripsi singkat konten



✨ Temuan Utama

* Mayoritas judul di Netflix adalah film.
* Amerika Serikat menjadi negara yang paling banyak memproduksi konten.
* Produksi konten mengalami peningkatan pesat setelah tahun 2015.
* Genre Drama dan Komedi mendominasi kategori konten.







