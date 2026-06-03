# 📊 VizBiz Analytics

VizBiz Analytics merupakan aplikasi Business Intelligence Dashboard berbasis Streamlit yang digunakan untuk memantau data penjualan berdasarkan kategori produk dan wilayah. Sistem ini dibangun dengan menerapkan konsep Doubly Linked List pada mata kuliah Struktur Data.

## Fitur Utama

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

## Struktur Data yang Digunakan

Aplikasi ini menggunakan:

- Node (`SalesNode`)
- Doubly Linked List (`SalesLinkedList`)

Setiap data penjualan disimpan dalam node yang memiliki:

- next
- prev

sehingga proses traversal, pencarian, dan penghapusan data dapat dilakukan menggunakan konsep Doubly Linked List.

## Struktur Folder

```text
pstrukdat/
│
├── app.py
├── logic.py
└── README.md
```

## Instalasi

Install library yang diperlukan:

```bash
pip install streamlit pandas
```

## Menjalankan Program

Jalankan perintah berikut pada terminal:

```bash
streamlit run app.py
```

## Teknologi yang Digunakan

- Python
- Streamlit
- Pandas
- Doubly Linked List

## Author
Ahmad Syarifudin
Hafidz Kahfianka Yusuf
Muhammad Alfin Alfaruq

UAS Struktur Data