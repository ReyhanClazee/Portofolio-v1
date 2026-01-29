# Portfolio Website

Website portfolio modern dan responsif yang dirancang untuk menampilkan karya, keahlian, dan informasi kontak profesional Anda.

![Portfolio Preview](https://img.shields.io/badge/Status-Ready%20to%20Use-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Fitur Utama

- 🎨 **Desain Modern & Elegan** - Typography premium dengan Playfair Display dan DM Sans
- 📱 **Fully Responsive** - Tampilan sempurna di semua device (Mobile, Tablet, Desktop)
- 🚀 **Performance Optimized** - Loading cepat tanpa dependencies eksternal yang berat
- 🎯 **SEO Friendly** - Struktur HTML yang optimal untuk mesin pencari
- 💼 **4 Section Utama:**
  - Hero Section dengan Call-to-Action
  - About Section dengan Skills showcase
  - Projects Portfolio showcase
  - Contact Form dengan informasi kontak
- 🎭 **Animasi Halus** - Fade-in animations dan smooth scrolling
- 🎨 **Logo Berwarna** - Icon skill dan social media dengan warna brand asli
- 🌈 **Color Scheme Profesional** - Kombinasi hitam, putih, dan orange accent

## 🎯 Tujuan

Website portfolio ini dibuat untuk:

1. **Menampilkan Portofolio** - Showcase proyek dan karya terbaik Anda
2. **Branding Profesional** - Membangun personal brand yang kuat
3. **Networking** - Memudahkan klien dan recruiter menghubungi Anda
4. **Career Development** - Meningkatkan peluang karir dengan portfolio online yang menarik

## 📋 Prasyarat

Tidak ada prasyarat khusus! Website ini menggunakan:
- HTML5
- CSS3
- Vanilla JavaScript

Cukup buka file `portfolio-website.html` di browser favorit Anda.

## 🚀 Cara Menggunakan

### 1. Download File
Download file `portfolio-website.html` ke komputer Anda.

### 2. Buka di Browser
Klik dua kali file HTML atau klik kanan → Open with → Browser pilihan Anda.

### 3. Kustomisasi
Edit file HTML sesuai kebutuhan Anda (lihat panduan di bawah).

## ⚙️ Kustomisasi

### 📝 Informasi Pribadi

#### Hero Section
Cari bagian ini dan ganti dengan info Anda:
```html
<h1 class="hero-title">
    Nama Anda
    <span class="accent">Web Developer</span>
</h1>
<p class="hero-description">
    Deskripsi singkat tentang Anda...
</p>
```

#### About Section
Update deskripsi dan skills Anda:
```html
<p>
    Saya adalah seorang web developer...
</p>
```

### 🖼️ Mengganti Gambar

#### Foto Profil
Cari di CSS bagian `.about-image`:
```css
.about-image {
    /* GANTI URL DIBAWAH INI DENGAN FOTO ANDA */
    background-image: url('URL_FOTO_ANDA');
}
```

#### Gambar Project
Cari di CSS:
```css
/* GANTI URL DIBAWAH INI DENGAN GAMBAR PROJECT ANDA */
.project-card:nth-child(1) .project-image {
    background-image: url('URL_PROJECT_1');
}
.project-card:nth-child(2) .project-image {
    background-image: url('URL_PROJECT_2');
}
.project-card:nth-child(3) .project-image {
    background-image: url('URL_PROJECT_3');
}
```

**Tips Upload Gambar:**
- Gunakan [Imgur](https://imgur.com) - Gratis, mudah
- Gunakan [Cloudinary](https://cloudinary.com) - Free tier bagus
- Upload ke hosting Anda sendiri

### 📧 Informasi Kontak

Cari di Contact Section:
```html
<p><a href="mailto:nama.anda@email.com">nama.anda@email.com</a></p>
<p><a href="tel:+6281234567890">+62 812-3456-7890</a></p>
<p>Jakarta, Indonesia</p>
```

### 🔗 Link Media Sosial

Update URL di Footer Section:
```html
<a href="https://github.com/username" ...>GitHub</a>
<a href="https://linkedin.com/in/username" ...>LinkedIn</a>
<a href="https://instagram.com/username" ...>Instagram</a>
<a href="https://twitter.com/username" ...>Twitter</a>
```

### 🎨 Mengubah Warna

Cari bagian CSS Variables dan sesuaikan:
```css
:root {
    --primary: #0a0a0a;      /* Warna hitam utama */
    --secondary: #f5f5f5;    /* Warna abu-abu terang */
    --accent: #ff6b35;       /* Warna accent (orange) */
    --text: #1a1a1a;         /* Warna text */
    --text-light: #666;      /* Warna text abu-abu */
}
```

### 📦 Menambah/Mengurangi Project

Untuk menambah project, copy paste struktur ini:
```html
<div class="project-card">
    <div class="project-image"></div>
    <div class="project-info">
        <h3 class="project-title">Judul Project</h3>
        <p class="project-description">Deskripsi project...</p>
        <div class="project-tags">
            <span class="tag">Tech 1</span>
            <span class="tag">Tech 2</span>
        </div>
    </div>
</div>
```

Dan tambahkan CSS untuk gambarnya:
```css
.project-card:nth-child(4) .project-image {
    background-image: url('URL_PROJECT_4');
}
```

## 🌐 Deploy ke Hosting

### GitHub Pages (Gratis)
1. Buat repository baru di GitHub
2. Upload file `portfolio-website.html` (rename jadi `index.html`)
3. Settings → Pages → Source: main branch
4. Website akan tersedia di `username.github.io`

### Netlify (Gratis)
1. Daftar di [Netlify](https://netlify.com)
2. Drag & drop file HTML
3. Website langsung online!

### Vercel (Gratis)
1. Daftar di [Vercel](https://vercel.com)
2. Import project
3. Deploy otomatis

## 📱 Responsiveness

Website ini dioptimalkan untuk:
- 📱 **Mobile** - 320px ke atas
- 📱 **Tablet** - 640px - 968px
- 💻 **Desktop** - 968px ke atas

## 🎨 Font yang Digunakan

- **Playfair Display** - Untuk heading dan judul (elegant serif)
- **DM Sans** - Untuk body text (modern sans-serif)

Keduanya di-load dari Google Fonts.

## 🛠️ Troubleshooting

### Gambar tidak muncul?
- Pastikan URL gambar benar dan bisa diakses
- Cek apakah ada typo di URL
- Pastikan link gambar menggunakan HTTPS

### Layout berantakan di mobile?
- Clear browser cache
- Cek apakah ada custom CSS yang override
- Pastikan viewport meta tag ada di head

### Form tidak berfungsi?
Form saat ini hanya menampilkan alert. Untuk mengirim email sungguhan, Anda perlu:
- Gunakan service seperti [Formspree](https://formspree.io)
- Atau setup backend sendiri dengan PHP/Node.js

## 📄 Lisensi

Bebas digunakan untuk keperluan pribadi dan komersial. Silakan modifikasi sesuai kebutuhan Anda.

## 🤝 Kontribusi

Jika menemukan bug atau ingin menambah fitur:
1. Fork repository ini
2. Buat branch baru
3. Submit pull request

## 💡 Tips & Best Practices

1. **Optimasi Gambar** - Compress gambar sebelum upload (gunakan TinyPNG)
2. **Konsisten** - Gunakan foto dan konten yang profesional
3. **Update Berkala** - Tambahkan project baru secara rutin
4. **SEO** - Ganti title dan meta description sesuai nama Anda
5. **Performance** - Jangan upload gambar terlalu besar (max 500KB per gambar)

## 📞 Support

Jika ada pertanyaan atau butuh bantuan, jangan ragu untuk bertanya!

## 🎉 Selamat!

Website portfolio Anda siap digunakan! Jangan lupa:
- ✅ Ganti semua informasi dengan data Anda
- ✅ Upload foto dan gambar project
- ✅ Update link social media
- ✅ Deploy ke hosting
- ✅ Share ke network Anda!

---

**Dibuat dengan ❤️ untuk membantu Anda membangun personal brand yang kuat**

*Last Updated: January 2026*
