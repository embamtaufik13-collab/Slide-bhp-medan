# Slide BHP Medan

Situs statis untuk slide presentasi Balai Harta Peninggalan (BHP) Medan, di-hosting lewat GitHub Pages.

## Alamat online

https://embamtaufik13-collab.github.io/Slide-bhp-medan/

## File paparan

Slide paparan (PowerPoint) tersedia di `BHP-Medan-Paparan-Klaster-1.pptx` dan dapat
diunduh dari situs lewat tombol **Unduh PPTX** di bagian bawah halaman:

https://embamtaufik13-collab.github.io/Slide-bhp-medan/BHP-Medan-Paparan-Klaster-1.pptx

## Halaman data lengkap

`data-lengkap.html` memuat data lengkap kepailitan BHP Medan (tagihan, harta, kreditor, debitor).
Halaman ini dibuka lewat kartu kecil "Data lengkap kepailitan BHP Medan" di tab Perkara BHP:

https://embamtaufik13-collab.github.io/Slide-bhp-medan/data-lengkap.html

`fonts.css` dan `logo.png` adalah aset pendukung halaman tersebut.

## Cara memperbarui slide

1. Letakkan file slide (HTML) di root repo dengan nama `index.html`.
   File pendukung (gambar, CSS, JS) boleh ditaruh di folder mana saja, misalnya `assets/`.
2. Commit dan push ke branch utama.
3. GitHub Actions (`.github/workflows/deploy.yml`) akan otomatis mendeploy ulang
   dalam 1 sampai 2 menit.

## Pengaturan sekali saja

Di GitHub: **Settings > Pages > Build and deployment > Source** pilih **GitHub Actions**.
Tanpa langkah ini workflow deploy tidak akan bisa mempublikasikan situs.
