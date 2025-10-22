# Responsi-modul-1-cuci-sepatu-
## Deskripsi Umum
REST API ini merupakan proyek responsi yang berfungsi untuk mengelola data pesanan layanan cuci sepatu. API ini menyediakan endpoint untuk menambahkan, membaca, memperbarui, dan menghapus data pesanan. Proyek ini dikembangkan menggunakan Node.js, Express, dan PostgreSQL.

## Tujuan dan Fitur Utama
Tujuan:
- Membuat sistem pencatatan pesanan cuci sepatu secara digital.
- Mempermudah pengelolaan data pelanggan dan status pengerjaan.
  
Fitur Utama:
- Tambah pesanan baru.
- Lihat semua pesanan.
- Perbarui status pesanan.
- Hapus pesanan.
- Validasi otomatis untuk tipe layanan dan status pesanan.

## Struktur Data
```
 {
  "id": 9f956dcc-c5a0-4733-a07d-e7cabe3b9dd9",
  "nama_pelanggan": "Devarlo",
  "nomor_telepon": "081284200975",
  "nama_sepatu": "New Balance 550 Black White",
  "tipe_layanan": "Deep Clean",
  "status": "Menunggu",
  "tanggal_masuk": "2025-10-20",
  "tanggal_selesai": "null",
  "harga": 60000
}
```
Keterangan:
- id = Nomor unik pesanan
- nama_pelanggan = Nama pelanggan yang memesan layanan
- nomor_telepon = Nomor kontak pelanggan
- nama_sepatu = Nama atau jenis sepatu yang dicuci
- tipe_layanan = Jenis layanan
- status = Status pengerjaan sepatu (Menunggu, Sedang Dicuci, Selesai)
- tanggal_masuk = Tanggal sepatu diterima untuk dicuci
- tanggal_selesai = Tanggal sepatu selesai dicuci
- harga = Biaya layanan cuci sepatu
