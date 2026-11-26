# Lapau Digital – VR Showroom UMKM Minang

Media pembelajaran interaktif MK Bisnis Digital (AR + VR + Generative AI).

- `index.html` : VR showroom (A-Frame/WebXR), 4 titik interaksi, persona pembeli & umpan balik dari GenAI
- `ar.html` : Mode AR studio foto produk (model-viewer) + GenAI copywriting marketplace
- `models/` : model 3D produk (.glb)
- `vendor/` : library A-Frame 1.6.0 dan model-viewer 3.5.0 (disimpan lokal)

## Cara publikasi di GitHub Pages
1. Buat repository baru (Public) di github.com, misalnya `lapau-digital`.
2. Klik **Add file → Upload files**, lalu unggah SEMUA isi folder ini (termasuk folder `models` dan `vendor`). Klik **Commit changes**.
3. Buka **Settings → Pages**, pada *Branch* pilih `main` dan folder `/ (root)`, klik **Save**.
4. Tunggu 1–2 menit. Tautan publik: `https://<username>.github.io/lapau-digital/`

## Catatan
- Generative AI memakai Puter.js (gratis, tanpa API key). Saat pertama kali, pengguna mungkin diminta login akun Puter.
- Bila AI tidak terhubung, aplikasi otomatis memakai skenario bawaan (mode offline) agar tetap bisa dipakai.
- AR membutuhkan ponsel yang mendukung AR (Android Chrome / iPhone Safari) dan halaman yang dibuka lewat HTTPS (GitHub Pages sudah HTTPS).
