# ZAV CodeLab

Web belajar coding ringan dan mobile-first untuk anak kelas 6. Anak dapat belajar HTML, CSS, dan JavaScript lewat enam misi kecil, menjalankan kode, dan langsung melihat hasilnya.

## Fitur

- Enam misi dari HTML dasar sampai project profil digital.
- Editor sederhana yang nyaman digunakan dari HP.
- Preview dalam `iframe` terisolasi.
- Tombol simbol cepat untuk keyboard HP.
- Petunjuk dan pemeriksaan jawaban setiap misi.
- Progress dan draft tersimpan lokal di perangkat.
- PWA dan cache offline tanpa backend atau database.
- Tanpa framework, akun, iklan, atau dependency eksternal.

## Menjalankan secara lokal

```bash
python -m http.server 8080
```

Lalu buka `http://localhost:8080`.

## Hosting gratis

Project dapat langsung dipasang di GitHub Pages, Netlify, atau Cloudflare Pages. Tidak diperlukan build command dan folder publikasinya adalah root repository.

## Struktur

- `index.html` — struktur halaman dan editor.
- `styles.css` — tampilan mobile-first.
- `app.js` — materi, preview runner, pemeriksaan misi, dan progress.
- `manifest.webmanifest` — konfigurasi PWA.
- `sw.js` — cache offline.
- `icon.svg` — ikon aplikasi.
