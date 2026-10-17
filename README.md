# achclip — Static Web App (Vercel)

Aplikasi 100% di browser (tanpa server). Video diproses di perangkat kamu,
analisis AI dipanggil langsung dari browser ke Gemini API memakai API Key milikmu.

## Struktur
- `public/index.html` — seluruh aplikasi
- `vercel.json` — konfigurasi deploy (static, output dir `public`)

## Deploy ke Vercel
1. Upload semua file ini ke repo GitHub (root repo = isi folder ini).
2. Vercel → Add New → Project → Import repo.
3. Framework Preset: **Other**. Build/Install Command: kosong. Output Directory: `public`
   (sudah diatur otomatis lewat `vercel.json`).
4. Deploy. Tidak ada Environment Variable yang dibutuhkan.

## Cara pakai
Masukkan API Key Gemini → upload brief → upload video (maks 30 menit) → atur gaya → proses.
