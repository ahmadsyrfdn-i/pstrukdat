# 📊 VizBiz Analytics

VizBiz Analytics merupakan aplikasi Business Intelligence Dashboard berbasis Streamlit yang digunakan untuk memantau data penjualan berdasarkan kategori produk dan wilayah. Sistem ini dibangun dengan menerapkan konsep Doubly Linked List pada mata kuliah Struktur Data.

---

## 🎯 Studi Kasus

Perusahaan membutuhkan dashboard sederhana untuk memantau performa penjualan berdasarkan kategori produk dan wilayah secara real-time.

Untuk mengelola data penjualan secara dinamis digunakan struktur data **Doubly Linked List** sehingga data dapat ditambahkan, dicari, ditampilkan, dan dihapus tanpa menggunakan struktur data bawaan Python sebagai penyimpanan utama.

---

## ✨ Fitur Utama

- Menambahkan data penjualan
- Menampilkan seluruh data penjualan
- Pencarian data berdasarkan kategori
- Menghapus data berdasarkan kategori
- KPI Dashboard
  - Total Revenue
  - Total Data
  - Rata-rata Penjualan
  - Rata-rata Pendapatan
- Visualisasi data penjualan
  - Pendapatan per kategori
  - Pendapatan per wilayah

---

## 🏗 Struktur Data yang Digunakan

Aplikasi ini menggunakan:

### SalesNode

Node digunakan untuk menyimpan data penjualan yang terdiri dari:

- Tanggal
- Kategori
- Wilayah
- Jumlah Penjualan
- Pendapatan
- Total Pendapatan

Setiap node memiliki pointer:

- `next`
- `prev`

### SalesLinkedList

Linked List digunakan sebagai struktur penyimpanan utama dengan operasi:

- Insert Data
- Traversal Data
- Search Data
- Delete Data

---

## 📁 Struktur Folder

```text
pstrukdat/
│
├── app.py
├── logic.py
└── README.md
```

---

## 📥 Cara Mendapatkan Project

### Opsi 1 — Clone Repository

Pastikan Git sudah terinstall.

```bash
git clone https://github.com/ahmadsyrfdn-i/pstrukdat.git
```

Masuk ke folder project:

```bash
cd pstrukdat
```

---

### Opsi 2 — Download ZIP

1. Buka repository GitHub.
2. Klik tombol **Code**.
3. Pilih **Download ZIP**.
4. Extract file ZIP.
5. Buka folder project menggunakan VS Code.

---

## ⚙ Instalasi

Install dependency yang diperlukan:

```bash
pip install streamlit pandas
```

Atau:

```bash
pip install -r requirements.txt
```

Jika menggunakan file requirements.txt.

---

## ▶ Menjalankan Program

Jalankan perintah berikut:

```bash
streamlit run app.py
```

Setelah berhasil dijalankan, aplikasi akan terbuka otomatis pada browser.

Biasanya melalui alamat:

```text
http://localhost:8501
```

---

## 📊 Analisis Kompleksitas (Big-O)

| Operasi | Kompleksitas |
|----------|----------|
| Insert | O(1) |
| Traversal | O(n) |
| Search | O(n) |
| Delete | O(n) |

### Kelebihan

- Penambahan data cepat karena menggunakan pointer tail.
- Struktur data bersifat dinamis.
- Mendukung navigasi dua arah (next dan prev).
- Tidak perlu menggeser data saat penghapusan.

### Kekurangan

- Membutuhkan memori lebih besar karena setiap node memiliki dua pointer.
- Pencarian data masih linear (O(n)).
- Kurang optimal untuk data berukuran sangat besar dibanding database modern.

---

## 🛠 Teknologi yang Digunakan

- Python
- Streamlit
- Pandas
- Doubly Linked List

---

## 👨‍💻 Author

- Ahmad Syarifudin
- Hafidz Kahfianka Yusuf
- Muhammad Alfin Alfaruq

---

**UAS Struktur Data — Universitas Islam Negeri Siber Syekh Nurjati Cirebon**