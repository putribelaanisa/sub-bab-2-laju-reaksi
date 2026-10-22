# Media Pembelajaran Interaktif: Faktor-Faktor yang Memengaruhi Laju Reaksi

Situs statis satu halaman (HTML, CSS, JavaScript tanpa dependensi) untuk kimia kelas XI.

## Struktur
- `index.html` : seluruh media (simulasi konsentrasi, simulasi suhu, penerapan, latihan soal)
- `vercel.json` : konfigurasi Vercel (opsional)

## Deploy ke Vercel lewat GitHub
1. Buat repositori baru di GitHub, lalu unggah ketiga file ini (atau jalankan perintah di bawah).
2. Buka https://vercel.com/new, pilih **Import Git Repository**, lalu pilih repositori tersebut.
3. Pengaturan: **Framework Preset = Other**, kosongkan Build Command dan Output Directory (root `./`).
4. Klik **Deploy**. Setiap `git push` ke branch utama akan otomatis memperbarui situs.

```bash
git init
git add .
git commit -m "Media laju reaksi"
git branch -M main
git remote add origin https://github.com/USERNAME/NAMA-REPO.git
git push -u origin main
```

## Uji lokal
Buka `index.html` di peramban, atau jalankan `npx serve .`
