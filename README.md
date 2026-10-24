# DEMARA — Athleisure Style Consultant

Website front-end satu halaman bertema **Fashion dan Style Consultant** dengan konsep **Athleisure Style**. Dibuat sebagai Mini Project **Trial Study Club Frontend** (KSM Veterantech UPNVJ 2026), dikerjakan secara individu.

DEMARA membantu pengunjung menemukan gaya athleisure yang cocok untuk aktivitas sehari-hari, lalu memesan jasa konsultasi styling lewat form sederhana.

## Fitur dan Section

| Section | ID | Isi |
|---|---|---|
| Header | - | Logo DEMARA dan navigasi ke semua section |
| Hero | `#home` | Judul konsep "Athleisure Style", tagline, deskripsi, tombol ajakan, dan gambar utama |
| Explore Your Style | `#styles` | 4 kartu gaya: Sporty Layers, Everyday Athleisure, Gym-to-Street, Running Essentials |
| Styling Tips | `#tips` | Daftar tips styling (unordered list) |
| Style Guide | `#guide` | Tabel color palette, material, jenis pakaian, dan occasion tiap gaya |
| Style Inspiration | `#inspiration` | Link Pinterest bergambar dan rekomendasi orang dengan style serupa (link Instagram) |
| Book a Consultant | `#consultation` | Langkah konsultasi (ordered list) dan form: nama, email, pesan, kirim |
| Footer | - | Copyright dan link email (`mailto:`) |

## Kesesuaian dengan Ketentuan Tugas

**Elemen layout wajib**

- Header berisi nama/logo website
- Gambar model, pakaian, dan aksesoris pendukung
- Judul utama (nama konsep fashion)
- Deskripsi website
- Tabel (color palette, material, jenis pakaian, occasion)
- List styling tip
- Link eksternal (Pinterest dan media sosial)
- Link internal (navigasi antar section)
- Form (nama, email, pesan, kirim)
- Rekomendasi orang dengan style yang sama
- Footer

**Materi yang dicakup**

- Semantic HTML: `header`, `nav`, `main`, `section`, `article`, `footer`
- CSS layouting: Flexbox (header, nav, hero, form) dan Grid (kartu, tips, galeri)
- Teks: `h1` sampai `h4` dan `p`
- List: ordered list (`ol`) dan unordered list (`ul`)
- Table: `caption`, `thead`, `tbody`, `th scope`
- Media: gambar dengan atribut `alt`
- Link: intra-page (`#id`), eksternal (`target="_blank"`), dan email (`mailto:`)
- Form sederhana dengan `label`, `input`, `textarea`, dan validasi `required`

## Teknologi

- HTML5
- CSS3 (Flexbox, Grid, transition, media query)

Tidak memakai framework maupun JavaScript.

## Struktur Folder

```
MP_Demas/
├── Source Code_Demas.html
├── Source Code_Demas.css
└── images/
    ├── hero1.jpg
    ├── model1.jpg ... model4.jpg
    ├── pin1.jpg ... pin3.jpg
    ├── dara.jpg
    ├── zharif.jpg
    ├── densu.jpg
    ├── ayudiac.jpg
    └── dav.jpg
```

## Cara Menjalankan

1. Pastikan file HTML, file CSS, dan folder `images/` berada dalam satu folder.
2. Buka `Source Code_Demas.html` di browser (Chrome, Edge, Firefox, dan sejenisnya).

Nama file CSS harus persis `Source Code_Demas.css`, karena dipanggil dengan nama itu di dalam HTML.

## Responsif

Tampilan menyesuaikan ukuran layar lewat media query:

- **Maks. 768px:** header dan nav bertumpuk, hero menjadi satu kolom, kartu gaya dan tips menjadi 2 kolom
- **Maks. 480px:** kartu gaya dan tips menjadi 1 kolom

## Palet Warna Website

| Warna | Kode | Penggunaan |
|---|---|---|
| Cream | `#F4F1EA` | Latar halaman |
| Charcoal | `#292B2D` | Teks, tombol, footer |
| Terracotta | `#A36F4F` | Aksen link dan hover |
| Sage | `#657B60` | Judul kartu dan aksen form |

## Catatan

- Form konsultasi masih berupa tampilan front-end (belum terhubung ke server), sehingga tombol kirim belum mengirim data.
- Link eksternal (Pinterest dan Instagram) membuka tab baru.

## Pembuat

**Demas** — Mini Project Trial Study Club Frontend, KSM Veterantech UPNVJ 2026