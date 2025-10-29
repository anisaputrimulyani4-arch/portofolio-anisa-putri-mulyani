# Portofolio - Anisa Putri Mulyani (Siap untuk GitHub Pages)

Folder ini berisi situs portofolio satu halaman (Bahasa Indonesia) yang siap diunggah ke **GitHub Pages**.

## Cara cepat deploy ke GitHub Pages
1. Buat repository baru di GitHub (mis. `portofolio-anisa-putri-mulyani`) dan **unggah semua file** dari folder ini ke branch `main`.
2. Di halaman repository -> Settings -> Pages, pilih Source: `main` branch, `/ (root)` lalu simpan.
3. Setelah beberapa menit, situs akan tersedia di `https://<username>.github.io/<repo-name>`.

## Form Kontak (kirim ke email)
Form di situs menggunakan layanan pihak ketiga (Formspree) untuk mengirim pesan ke email. Agar formulir mengirim ke `anisaputrimulyani4@gmail.com`, ikuti langkah singkat ini:

1. Buka https://formspree.io dan daftar (gratis untuk rencana dasar).  
2. Buat form baru, lalu salin `form ID` (mis. format: `f/xxxxx`).  
3. Buka file `script.js` dan ganti nilai `FORM_ENDPOINT` pada baris atas dengan endpoint Formspree lengkap, misalnya:  
   `https://formspree.io/f/your_form_id_here`  
4. Commit & push perubahan ke GitHub. Setelah pengaturan Formspree benar, pesan dari formulir akan otomatis diteruskan ke email kamu (`anisaputrimulyani4@gmail.com`).

**Fallback:** Jika kamu tidak ingin mendaftar layanan, formulir akan otomatis membuka email client pengguna (mailto:) sebagai cadangan sehingga pesan tetap bisa dikirimkan secara manual.

## File penting
- `index.html` - Halaman utama
- `style.css` - Styling (tema beige elegan)
- `script.js` - Logika formulir & pengiriman
- `Portofolio_Anisa_Putri_Mulyani.pdf` - Versi PDF portofolio (tersedia untuk diunduh)

Jika kamu mau, aku bisa juga bantu langkah demi langkah push file ini ke GitHub dari awal (panduan lengkap dengan perintah git), atau aku bisa langsung mengunggah ke GitHub jika kamu berikan akses token — tapi itu opsional.