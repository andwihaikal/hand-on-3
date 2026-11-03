# 📊 Hands-On 3: Pandas Lanjutan
### Analisis dan Pembersihan Data Student Performance

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Deskripsi Proyek

Proyek ini merupakan tugas **Hands-On 3: Pandas Lanjutan** yang berfokus pada proses pengolahan, pembersihan, dan analisis data menggunakan Python, khususnya library Pandas.

Dataset yang digunakan adalah **Student Performance**, yaitu dataset yang digunakan untuk menganalisis data terkait siswa dan faktor-faktor yang berpotensi berkaitan dengan performa akademik.

Proyek ini mencakup pemeriksaan kualitas data, penanganan nilai yang hilang, pemeriksaan duplikasi, identifikasi pencilan (*outlier*), analisis data menggunakan `groupby`, serta persiapan data untuk pemodelan machine learning.

## 🎯 Tujuan Proyek

Tujuan dari proyek ini adalah:

- Memahami struktur dan karakteristik dataset.
- Mengidentifikasi masalah kualitas data.
- Menangani nilai kosong (*missing values*) dan data duplikat.
- Mengidentifikasi serta menangani pencilan (*outlier*).
- Memperbaiki tipe data agar sesuai dengan kebutuhan analisis.
- Melakukan analisis kelompok menggunakan `groupby`.
- Mempersiapkan data untuk proses pelatihan dan pengujian model.
- Menghindari *data leakage* saat membangun pipeline machine learning.
- Menghasilkan dataset bersih dan dokumentasi kualitas data.

## 🛠️ Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| Python | Bahasa pemrograman utama |
| Pandas | Manipulasi dan pembersihan data |
| NumPy | Operasi numerik |
| Matplotlib | Visualisasi data, jika digunakan |
| Seaborn | Visualisasi statistik, jika digunakan |
| Scikit-learn | Pembagian dataset dan pipeline machine learning |
| Jupyter Notebook / Google Colab | Lingkungan pengolahan dan analisis data |
| Git & GitHub | Pengelolaan versi dan publikasi proyek |

## 📂 Struktur Repository

```text
hand-on-3/
│
├── README.md
├── Tugas_Hands_On_3_Student_Performance.ipynb
│
├── data/
│   └── case9_student_performance.csv
│
├── output/
│   ├── data_bersih.csv
│   ├── kamus_data.csv
│   └── laporan_kualitas.csv
│
└── .gitignore
```

## 🔎 Tahapan Pengerjaan

### 1. Eksplorasi Data

Melakukan pemeriksaan awal untuk memahami isi dataset, meliputi:

- Jumlah baris dan kolom.
- Nama kolom dan tipe data.
- Statistik deskriptif.
- Distribusi nilai pada kolom tertentu.
- Jumlah nilai kosong dan data duplikat.

### 2. Pemeriksaan Kualitas Data

Mengidentifikasi permasalahan pada dataset, seperti:

- Nilai yang hilang (*missing values*).
- Data duplikat.
- Tipe data yang tidak sesuai.
- Nilai yang tidak wajar.
- Pencilan (*outlier*).

### 3. Pembersihan Data

Melakukan proses pembersihan berdasarkan hasil pemeriksaan, termasuk:

- Menangani nilai kosong dengan metode yang sesuai.
- Memeriksa dan menangani data duplikat.
- Memperbaiki tipe data.
- Mengidentifikasi dan menangani pencilan menggunakan metode yang sesuai.
- Memastikan dataset hasil pembersihan siap digunakan untuk analisis lanjutan.

### 4. Analisis Data dengan GroupBy

Mengelompokkan data berdasarkan kategori yang relevan untuk memperoleh ringkasan statistik.

Analisis dapat mencakup perbandingan performa akademik berdasarkan karakteristik siswa atau kategori lain yang tersedia dalam dataset.

Hasil analisis digunakan untuk membantu memahami pola dalam data, bukan untuk menyimpulkan hubungan sebab-akibat secara langsung.

### 5. Persiapan Data untuk Machine Learning

Mempersiapkan dataset untuk pelatihan dan pengujian model menggunakan Scikit-learn.

Tahapan meliputi:

- Memisahkan fitur (*features*) dan target.
- Membagi data menggunakan `train_test_split`.
- Menggunakan `ColumnTransformer` untuk menangani kolom numerik dan kategorikal.
- Menerapkan imputasi dan transformasi melalui pipeline.
- Menghindari *data leakage* dengan mempelajari parameter transformasi hanya dari data pelatihan.

### 6. Ekspor Hasil

## 📁 Output Proyek

| File | Deskripsi |
|---|---|
| `data_bersih.csv` | Dataset yang telah melalui proses pembersihan |
| `kamus_data.csv` | Dokumentasi nama kolom, tipe data, dan keterangan variabel |
| `laporan_kualitas.csv` | Ringkasan pemeriksaan kualitas data |
| `notebook.ipynb` | Notebook berisi kode, proses analisis, dan hasil pengerjaan |


## 📈 Hasil dan Temuan

Bagian ini berisi ringkasan temuan berdasarkan hasil analisis pada notebook.

Beberapa hal yang dapat dijelaskan setelah analisis selesai:

1. **Kualitas data:** jumlah nilai kosong, data duplikat, dan permasalahan data yang ditemukan.
2. **Pembersihan data:** metode yang digunakan untuk menangani permasalahan tersebut.
3. **Hasil analisis:** temuan dari pengelompokan data menggunakan `groupby`.
4. **Persiapan machine learning:** fitur, target, dan tahapan preprocessing yang digunakan.

> Tambahkan angka dan temuan aktual dari notebook setelah seluruh proses analisis selesai. Hindari mencantumkan hasil yang belum diverifikasi.

.

## 👨‍💻 Informasi Proyek

| Keterangan | Detail |
|---|---|
| Nama Proyek | Hands-On 3: Pandas Lanjutan |
| Dataset | Student Performance |
| Bahasa Pemrograman | Python |
| Fokus | Data Cleaning, Data Quality, GroupBy, dan Machine Learning Preprocessing |
| Platform | Jupyter Notebook / Google Colab |
| Repository | [hand-on-3](https://github.com/andwihaikal/hand-on-3) |

## 📝 Kesimpulan

Proyek ini memberikan pengalaman praktis dalam mengolah dataset menggunakan Pandas, mulai dari eksplorasi dan pemeriksaan kualitas data hingga pembersihan, analisis kelompok, serta persiapan data untuk machine learning.

Melalui pengerjaan ini, diharapkan pemahaman mengenai pentingnya kualitas data, dokumentasi yang baik, dan pencegahan *data leakage* dalam proses analisis data dapat meningkat.

---

**Dibuat sebagai bagian dari tugas Hands-On 3: Pandas Lanjutan.**
