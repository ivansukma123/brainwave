# Dynamic Brainwave & Synthesized Ambient Generator

Aplikasi PWA berbasis HTML5, CSS3, Vanilla JavaScript, dan Web Audio API. Seluruh suara dibuat secara prosedural tanpa file audio eksternal.

## Fitur

- Binaural, monaural, isochronic, dan hybrid
- Ambient prosedural: ombak, hujan, angin, pink noise, brown noise
- Timeline sequencer preset
- Soft fade-in/fade-out
- Master compressor/limiter
- Real-time visualizer
- Sleep timer
- Tes stereo kiri/kanan
- Media Session API
- Penyimpanan localStorage
- Ekspor dan impor preset JSON
- PWA offline untuk GitHub Pages

## Menjalankan secara lokal

Service Worker membutuhkan HTTP/HTTPS. Jalankan melalui server lokal, misalnya:

```bash
python -m http.server 8080
```

Lalu buka `http://localhost:8080`.

## Unggah ke GitHub Pages

1. Buat repositori baru.
2. Unggah seluruh isi folder ini ke root repositori.
3. Buka Settings → Pages.
4. Pilih Deploy from a branch.
5. Pilih branch `main` dan folder `/root`.
6. Simpan dan buka URL GitHub Pages Anda.

## Catatan keselamatan

Aplikasi ini bukan alat medis. Jangan digunakan saat mengemudi atau mengoperasikan mesin. Mulai dari volume rendah dan hentikan penggunaan jika muncul ketidaknyamanan.
