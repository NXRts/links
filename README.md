# 🌐 Link Bio Page

![License](https://img.shields.io/github/license/NXRts/links?style=flat-square)
![Stars](https://img.shields.io/github/stars/NXRts/links?style=flat-square)

Halaman **Link Bio** yang sederhana, elegan, dan *responsive*. Didesain dengan **Glassmorphism**, antarmuka gelap (Dark Mode), dan animasi halus yang memanjakan mata. Cocok digunakan sebagai portofolio personal, kartu nama digital, atau pengganti Linktree.

---

## ✨ Fitur Utama

- **🎨 Modern & Estetik**: Menggunakan gaya Glassmorphism dengan background gradient yang dinamis.
- **🌙 Dark Mode**: Tampilan gelap yang elegan dan nyaman di mata.
- **📱 Responsif**: Tampilan sempurna di berbagai perangkat (Mobile, Tablet, Desktop).
- **⚡ Ringan & Cepat**: Dibangun dengan HTML5 dan CSS3 murni tanpa framework berat.
- **✨ Animasi Halus**: Efek hover dan transisi yang interaktif.
- **🧩 Ikon Lengkap**: Menggunakan **Feather Icons** dan **Simple Icons** (untuk brand).

---

## 🛠️ Teknologi

- **HTML5**: Struktur semantik.
- **CSS3**: Styling, Flexbox, Glassmorphism, Animations.
- **Feather Icons**: Ikon UI minimalis.
- **Simple Icons**: Ikon brand (Spotify, MyAnimeList, dll).

---

## 🚀 Instalasi & Penggunaan

### 1. Clone Repository

Salin proyek ini ke komputer lokal Anda:

```bash
git clone https://github.com/NXRts/links.git
cd links
```

### 2. Jalankan

Cukup buka file `index.html` di browser favorit Anda.
Tidak perlu instalasi `npm` atau server backend.

---

## 🎨 Panduan Kustomisasi

Anda dapat dengan mudah mengubah konten sesuai kebutuhan Anda.

### Mengganti Foto Profil

1. Siapkan foto Anda (rasio 1:1 disarankan).
2. Simpan di folder `assets/img/`.
3. Ubah src di `index.html`:

   ```html
   <img src="assets/img/nama-foto-anda.png" alt="Profile Picture">
   ```

### Menambah/Mengubah Link

Setiap tombol link memiliki struktur berikut di `index.html`:

```html
<a href="URL_TUJUAN" class="glass-btn">
    <i data-feather="NAMA_ICON"></i> Teks Label
</a>
```

- Ganti `URL_TUJUAN` dengan link Anda.
- Ganti `NAMA_ICON` dengan nama ikon dari [Feather Icons](https://feathericons.com/).
- Ganti `Teks Label` dengan nama link.

### Mengubah Warna Background

Buka `style.css` dan edit bagian `body`:

```css
body {
    background: radial-gradient(...); /* Sesuaikan warna di sini */
}
```

---

## 🌐 Deploy (Onlinekan Website)

Cara termudah untuk meng-onlinekan website ini adalah menggunakan **GitHub Pages**, **Vercel**, atau **Netlify**.

### Deploy ke Vercel (Rekomendasi)

1. Push kode ke GitHub.
2. Login ke [Vercel](https://vercel.com/).
3. Klik **"New Project"** dan import repository ini.
4. Klik **"Deploy"**. Selesai!

---

## 🤝 Kontribusi

Ingin berkontribusi? Silakan fork repository ini dan buat Pull Request. Saran dan masukan sangat dihargai!

---

## 📄 Lisensi

Didistribusikan di bawah lisensi MIT. Lihat `LICENSE` untuk informasi lebih lanjut.

---

<p align="center">
  Dibuat dengan ❤️ oleh <a href="https://github.com/NXRts">NXRts</a>
</p>
