# Weather-App

Weather-App adalah aplikasi sederhana untuk menampilkan informasi cuaca. Proyek ini berfokus pada front-end statis: HTML, CSS, dan aset gambar. Anda bisa memperluasnya dengan menambahkan JavaScript untuk mengambil data dari API cuaca (contoh: OpenWeatherMap) atau membuat versi backend.

## Isi Repository

- `index.html` - halaman utama aplikasi.
- `style.css` - stylesheet untuk tampilan.
- `images/` - folder untuk aset gambar (ikon, background, dsb.).

## Fitur (contoh yang dapat diimplementasikan)

- Menampilkan cuaca terkini berdasarkan kota.
- Menampilkan ikon cuaca dan suhu.
- Mode gelap/terang.

## Cara Menjalankan (lokal)

1. Buka folder proyek di file explorer.
2. Klik dua kali `index.html` atau buka file tersebut di browser favorit Anda.

Atau, untuk pengalaman development yang lebih baik (menyajikan file via server lokal):

Jika Anda punya Node.js terpasang, jalankan server sederhana:

1. Buka terminal di folder `Weather-App`.
2. Jalankan:

```powershell
npx http-server -c-1 -p 8080
# lalu buka http://localhost:8080 di browser
```

Catatan: perintah di atas membutuhkan Node.js dan npm. Jika tidak terpasang, cukup buka `index.html` langsung.

## Menambahkan Integrasi API Cuaca (contoh singkat)

1. Daftar ke layanan seperti OpenWeatherMap dan dapatkan API key.
2. Buat file JavaScript (mis. `app.js`) dan panggil endpoint API menggunakan `fetch`.
3. Tampilkan data di DOM.

Contoh alur data singkat:

- Input: nama kota (string)
- Output: objek cuaca { suhu, kondisi, ikon }
- Error: penanganan saat jaringan/API error atau kota tidak ditemukan

## Kode yang Dibantu AI: IBM Granite

Jika Anda menggunakan AI (termasuk IBM Granite) untuk membantu menulis, memperbaiki, atau mereview kode di proyek ini, mohon sertakan catatan singkat di commit message atau di dokumentasi yang relevan. Berikut contoh penulisan atribusi yang dapat Anda tambahkan pada `README.md` atau file `CONTRIBUTING.md`:

Contoh atribusi singkat:

> Bagian kode X dibuat/dibantu menggunakan AI (IBM Granite). Saya meninjau, menguji, dan menyesuaikan hasil tersebut agar sesuai kebutuhan proyek.

Petunjuk praktis saat menggunakan IBM Granite atau AI lainnya:

- Jelaskan prompt yang Anda pakai secara ringkas (tanpa menyertakan rahasia atau API keys).
- Verifikasi logika dan lakukan testing — AI dapat menghasilkan kode yang tampak benar tetapi mengandung bug atau masalah keamanan.
- Hindari menempelkan kredensial atau data sensitif ke dalam prompt.
- Catat perubahan besar yang dihasilkan AI dalam commit message atau changelog.

Contoh teks lengkap untuk ditambahkan ke commit message:

```
chore: add weather UI

Portions of code generated with assistance from IBM Granite (AI). All changes were reviewed and tested by the author.
```

Jika Anda memutuskan untuk mencantumkan detail penggunaan AI secara lebih formal, pertimbangkan menambahkan file `AI_USAGE.md` atau memperluas `CONTRIBUTING.md` dengan template prompt, checklist review keamanan, dan cara menandai PR yang berisi perubahan yang dibantu AI.
