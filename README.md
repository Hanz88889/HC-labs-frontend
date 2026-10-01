# HC Labs Frontend

Frontend HC Labs berupa single-page application statis pada `index.html`.

## Struktur aktif

| File | Fungsi |
|---|---|
| `index.html` | Layout, styling, state UI, license gate, API calls, generator, history, diagnostics, Conversation Brain |
| `assets/brand/hc-labs-logo.png` | Satu-satunya sumber logo brand yang dipakai sidebar |
| `assets/brand/README.md` | Panduan mengganti logo tanpa mengubah kode |

## Konfigurasi

Ubah `WORKER_URL` pada bagian konfigurasi frontend jika endpoint Worker berpindah. API key provider dan admin secret tidak boleh diletakkan di repository frontend.

## Deployment

Push branch `main` ke repository yang terhubung deployment Pages. Untuk mengganti logo, cukup replace `assets/brand/hc-labs-logo.png`, commit, lalu push.
