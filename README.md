# Praktikum Pemrograman Web II — Pertemuan 5

## Pengelolaan Data Produk dan Keranjang Belanja Menggunakan Array PHP

### Identitas Mahasiswa

- **Nama:** Rafael Damanik
- **NIM:** 25110127
- **Kelas:** TK Grup D
- **Program Studi:** D3 Teknik Komputer
- **Mata Kuliah:** Praktek Pemrograman WEB II
- **Dosen Pengampu:** Juni Ismail, S.Kom., M.Kom.
- **Pertemuan:** 5

---

## Deskripsi Proyek

**Kasir Array Lab** adalah aplikasi sederhana berbasis PHP yang digunakan untuk mengelola katalog produk dan keranjang belanja menggunakan array asosiatif dan array multidimensi.

Aplikasi ini dibuat untuk memenuhi tugas Praktikum Pemrograman Web II Pertemuan 5 di Politeknik Bisnis Indonesia.

## Tujuan Praktikum

- Memahami penggunaan array asosiatif dan multidimensi.
- Mengakses data menggunakan indeks dan key.
- Menampilkan data menggunakan perulangan `foreach`.
- Mengurutkan produk berdasarkan harga.
- Menghitung subtotal, jumlah barang, dan total belanja.
- Memahami perubahan data array menggunakan beberapa fungsi PHP.

## Fitur Aplikasi

1. Menampilkan katalog produk beserta kode, harga, dan stok.
2. Mengurutkan katalog berdasarkan harga termurah.
3. Menampilkan keranjang belanja.
4. Menghitung subtotal setiap produk dan total belanja.
5. Menampilkan ringkasan jumlah produk dan barang yang dibeli.
6. Menampilkan latihan perubahan array.
7. Memeriksa versi PHP yang digunakan.

## Teknologi yang Digunakan

- PHP 8.0 atau lebih tinggi
- HTML5
- CSS3
- XAMPP
- Visual Studio Code
- Web browser
- GitHub Desktop (opsional)

## Struktur Folder

```text
kasir_array_p05_nama/
├── cek_php.php
├── data.php
├── functions.php
├── index.php
├── latihan.php
├── style.css
└── README.md
```

## Penjelasan File

| File | Fungsi |
|---|---|
| `cek_php.php` | Memeriksa versi PHP. |
| `data.php` | Menyimpan identitas mahasiswa, data produk, dan keranjang. |
| `functions.php` | Menyimpan fungsi pendukung perhitungan dan pengurutan. |
| `index.php` | Menampilkan katalog, pengurutan produk, dan keranjang belanja. |
| `latihan.php` | Menampilkan contoh perubahan dan pengolahan array. |
| `style.css` | Mengatur tampilan aplikasi. |

## Cara Menjalankan Aplikasi

1. Pastikan XAMPP dan Visual Studio Code sudah terpasang.
2. Simpan folder proyek di dalam direktori `htdocs`.
3. Buka XAMPP Control Panel.
4. Jalankan **Apache**. MySQL tidak diperlukan karena data disimpan menggunakan array PHP.
5. Buka folder proyek melalui Visual Studio Code.
6. Sesuaikan identitas mahasiswa pada file `data.php`.
7. Buka browser dan akses alamat berikut:

   ```text
   http://localhost/kasir_array_p05_nama/
   ```

8. Untuk membuka halaman latihan, gunakan:

   ```text
   http://localhost/kasir_array_p05_nama/latihan.php
   ```

9. Untuk memeriksa versi PHP, gunakan:

   ```text
   http://localhost/kasir_array_p05_nama/cek_php.php
   ```

**Catatan:** Ganti `kasir_array_p05_nama` dengan nama folder proyek yang sebenarnya.

## Konsep PHP yang Dipelajari

- **Array asosiatif:** menyimpan data menggunakan pasangan key dan value.
- **Array multidimensi:** menyimpan kumpulan data produk dan keranjang.
- **`foreach`:** melakukan perulangan untuk membaca data array.
- **`count()`:** menghitung jumlah elemen array.
- **`usort()`:** mengurutkan produk berdasarkan harga.
- **`array_column()`:** mengambil nilai dari kolom tertentu.
- **`array_values()`:** menyusun ulang indeks array numerik.
- **`unset()`:** menghapus elemen array.
- **Fungsi PHP:** memisahkan proses perhitungan menjadi bagian yang dapat digunakan kembali.

## Hasil yang Diharapkan

Dengan data awal dari modul praktikum, aplikasi menampilkan:

| Komponen | Hasil |
|---|---:|
| Jenis produk | 5 |
| Jenis produk dalam keranjang | 3 |
| Jumlah barang dibeli | 7 |
| Total belanja | Rp41.000 |

Produk dalam keranjang terdiri dari Buku Tulis, Pulpen, dan Penghapus.

## Batasan Aplikasi

- Data produk ditulis langsung dalam file PHP.
- Keranjang belum menggunakan session atau database.
- Belum tersedia formulir input produk.
- Perubahan data dilakukan melalui Visual Studio Code.
- Stok produk belum berkurang secara otomatis saat pembelian.

## Kesimpulan

Melalui praktikum ini, mahasiswa mempelajari pengelolaan data menggunakan array PHP, penerapan perulangan, pengurutan data, serta perhitungan subtotal dan total belanja. Pemisahan data, fungsi, tampilan PHP, dan CSS juga membantu membuat struktur program lebih terorganisasi dan mudah dipahami.
