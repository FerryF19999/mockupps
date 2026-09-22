# Nemu Seller — Mockup Promosi

Single-page mockup untuk Kelola Sosial Media (mulai Rp6 juta/bulan), Collab Posting, dan Iklan lewat Nemu.

## Jalankan lokal

```sh
python -m http.server 8765
```

Buka http://localhost:8765. Tidak memerlukan build atau instalasi dependensi.

## Fitur

- Form dinamis sesuai layanan, ringkasan, dan validasi input.
- Dua jalur Collab: konten dibuat Nemu atau disediakan seller.
- Brief awal kebutuhan seller untuk diskusi dengan agency.
- Brief eksekusi iklan yang bisa diunduh sebagai teks.
- Riwayat simulasi beserta salinan brief selama halaman terbuka.

## Batasan

Prototipe frontend; tidak mengirim permintaan, membuat iklan, atau memproses pembayaran. Produk dan riwayat awal adalah data contoh. Riwayat simulasi hilang saat halaman dimuat ulang. Belum terhubung ke katalog, database, atau akun iklan. Google Fonts membutuhkan koneksi internet.

## Berkas

- `index.html`: struktur dan formulir
- `style.css`: tampilan responsif
- `app.js`: interaksi, validasi, dan brief
