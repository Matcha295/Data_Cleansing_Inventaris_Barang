# Data Cleaning Inventaris Barang

Project ini dibuat untuk tugas Data Cleaning. Data yang saya gunakan
adalah data inventaris barang. Data awal masih terdapat beberapa
kesalahan dan penulisan yang berbeda-beda, sehingga perlu dibersihkan
agar datanya lebih rapi.

## Identitas

Nama: Stefania Marsela Koli
NIM: 2418007

## Data yang Digunakan

Data yang digunakan adalah data inventaris barang yang berisi:

- ID
- Nama Barang
- Kategori
- Lokasi
- Jumlah
- Satuan
- Kondisi
- Harga Satuan
- Tanggal Pembelian

## Proses yang Dilakukan

Data dibersihkan menggunakan Python di Google Colab. Beberapa proses
yang dilakukan yaitu:

1. Membaca data awal.
2. Mengecek isi dan struktur data.
3. Memperbaiki nama barang.
4. Memperbaiki kategori dan lokasi.
5. Memperbaiki satuan dan kondisi barang.
6. Memperbaiki harga dan tanggal pembelian.
7. Menghapus data yang sama atau duplikat.
8. Menambahkan kolom Total Nilai.

## Total Nilai

Kolom Total Nilai digunakan untuk mengetahui nilai seluruh barang.

Rumus yang digunakan:

Total Nilai = Jumlah × Harga Satuan

## Tools yang Digunakan

- Python
- Google Colab
- Pandas
- NumPy
- Microsoft Excel

## File

- `2418007_DataCleansing.ipynb` = file yang berisi kode untuk membersihkan data.
- `Data Kotor Inventaris Barang.xlsx` = data sebelum dibersihkan.
- `Data Bersih Inventaris Barang.xlsx` = data setelah dibersihkan.
- `README.md` = penjelasan singkat tentang project.