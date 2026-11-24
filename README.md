# Minggu 10 – Menjalankan PHP dan Penerima Form

Nama: Shabira Vikha Setyanto
NIM: A12.2025.07420

## Tujuan
Membuktikan server menjalankan PHP, mencoba variabel/echo/if,
dan mengirim form ke halaman penerima proses.php.

## Cara membuka
1. Jalankan XAMPP, Start Apache.
2. Form: http://localhost/pwebdasar/minggu10/index.php
3. Latihan: http://localhost/pwebdasar/minggu10/latihan.php
4. Cek lingkungan: http://localhost/pwebdasar/minggu10/cek-lingkungan.php

## Daftar berkas
- index.php – form buku tamu
- style.css – tampilan
- latihan.php – latihan variabel dan if
- proses.php – halaman penerima form
- cek-lingkungan.php – cek versi PHP dan mbstring

## Hasil uji
| Uji    | Perubahan                 | Prediksi                       | Hasil aktual |
|--------|---------------------------|--------------------------------|--------------|
| W10-01 | jumlah 1, status aktif    | Jumlah pesan: 1; Form siap     | Jumlah pesan: 1; Form siap |
| W10-02 | jumlah 3                  | Jumlah pesan: 3; Form siap     | Jumlah pesan: 3; Form siap |
| W10-03 | jumlah 3, status tutup    | Jumlah pesan: 3; Form ditutup  | Jumlah pesan: 3; Form ditutup |
| Form   | Kirim nama, email, pesan  | Data tampil di proses.php      | Halaman "Data berhasil diterima" menampilkan nama, email, dan pesan |

Setelah uji, latihan.php dikembalikan ke jumlah 1 dan status aktif.

## Lingkungan
Versi PHP dan status mbstring dapat dilihat di cek-lingkungan.php.