# Slide BHP Medan

Situs statis untuk slide presentasi Balai Harta Peninggalan (BHP) Medan, di-hosting lewat GitHub Pages.

## Alamat online

https://embamtaufik13-collab.github.io/Slide-bhp-medan/

## Cara memperbarui slide

1. Letakkan file slide (HTML) di root repo dengan nama `index.html`.
   File pendukung (gambar, CSS, JS) boleh ditaruh di folder mana saja, misalnya `assets/`.
2. Commit dan push ke branch utama.
3. GitHub Actions (`.github/workflows/deploy.yml`) akan otomatis mendeploy ulang
   dalam 1 sampai 2 menit.

## Pengaturan sekali saja

Di GitHub: **Settings > Pages > Build and deployment > Source** pilih **GitHub Actions**.
Tanpa langkah ini workflow deploy tidak akan bisa mempublikasikan situs.
