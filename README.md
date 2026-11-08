# `JADWAL-KERJA // AUTO-SCAN AI`

```text
┌──────────────────────────────────────────────────────────────┐
│  STATUS: ONLINE        MODE: SCHEDULE PARSER                 │
│  TARGET: JADWAL KERJA  FILTER: NAMA PENGGUNA                │
└──────────────────────────────────────────────────────────────┘
```

Aplikasi web satu file untuk membaca foto jadwal kerja, mengambil jadwal berdasarkan nama, lalu menampilkannya dalam tampilan terminal hijau bergaya matrix.

## `> FEATURES`

- **OCR otomatis** menggunakan Tesseract.js untuk membaca foto atau screenshot jadwal.
- **Filter nama** agar hanya jadwal pengguna yang dipilih yang ditampilkan.
- **Editor jadwal langsung** untuk tanggal, hari, shift, jam, dan seragam.
- **Penyimpanan lokal** melalui `localStorage`, sehingga data tetap tersimpan di browser.
- **Pencarian jadwal**, statistik hari kerja/jam/libur, dan mode print atau simpan PDF.
- **Tampilan responsive** dengan nuansa terminal, matrix rain, dan status online.

## `> QUICK START`

1. Buka [`index.html`](./index.html) di browser.
2. Isi nama, bulan, dan tahun.
3. Upload foto jadwal, lalu jalankan **SCAN OTOMATIS**.
4. Periksa atau edit hasilnya langsung di tabel.
5. Gunakan **PRINT / SAVE PDF** untuk menyimpan jadwal.

> Untuk OCR yang lebih akurat, gunakan foto yang terang, lurus, dan tidak buram.

## `> SHIFT CODES`

| Kode | Keterangan |
| --- | --- |
| `P` | Pagi, 08:00 - 16:00 |
| `S` | Siang, 14:00 - 22:00 |
| `SP` | Split, 10:00 - 14:00 dan 17:00 - 22:00 |
| `LIBUR` | Hari libur |

## `> TECH STACK`

- HTML, CSS, dan JavaScript vanilla
- [Tesseract.js](https://github.com/naptha/tesseract.js) untuk OCR
- `localStorage` untuk menyimpan data jadwal di browser
- Google Fonts: Share Tech Mono

## `> PRIVACY`

Foto jadwal diproses di browser oleh Tesseract.js. Data editan disimpan lokal di browser melalui `localStorage`; aplikasi ini tidak menyediakan backend atau database server.

## `> LICENSE`

Gunakan dan modifikasi sesuai kebutuhan pribadi.

```text
> SYSTEM READY...
> UPLOAD YOUR SCHEDULE.
> FILTER. PARSE. ORGANIZE.
```
