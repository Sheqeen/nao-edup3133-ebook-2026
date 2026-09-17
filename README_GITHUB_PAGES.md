# EDUP3133 Interactive e-Book 2026 — GitHub Pages v1

Status: LOCKED / APPROVED v1

## Struktur
- `index.html` — aplikasi utama
- `assets/` — muka depan + 80 infografik Topik 1–8
- `asset-manifest.json` — manifest integriti aset
- `.nojekyll` — memastikan GitHub Pages menghidangkan fail statik secara terus

## Routing
Aplikasi menggunakan hash routing, jadi GitHub Pages tidak memerlukan server-side routing:

- `#home`
- `#topik-1/1` ... `#topik-1/10`
- ...
- `#topik-8/1` ... `#topik-8/10`

## Deploy
1. Cipta repositori GitHub baharu.
2. Upload semua kandungan folder ini ke root repositori.
3. Commit.
4. GitHub → Settings → Pages.
5. Source: Deploy from a branch.
6. Branch: `main`, folder `/ (root)`.
7. Save.
8. Tunggu GitHub Pages selesai membina site.
9. Uji URL site dengan `#home`.

## Acceptance Test selepas deploy
- HOME muncul dengan betul.
- Klik Topik 1–8 berfungsi.
- Semua 10 halaman setiap topik boleh dibuka.
- Previous/Next berfungsi.
- Nombor 1–10 berfungsi.
- Butang UTAMA kembali ke HOME.
- Browser Back/Forward selari dengan hash.
- Telefon: butang Topik 1–8 di bawah muka depan berfungsi.
- Tiada imej hilang / 404.
- Tiada perubahan kandungan infografik.

## Prinsip v1
Versi ini LOCKED. Jika mahu menambah ciri baharu, buat versi/branch/repo baharu dan jangan ubah deployment v1 yang telah diluluskan.
