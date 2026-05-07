# LAPORAN — Website Personal Alex Mahendra

## Deskripsi Proyek

Website personal statis yang dibangun menggunakan **HTML5** dan **CSS3** murni tanpa framework. Website ini mencerminkan identitas dan portofolio saya sebagai web developer & UI designer.

**Fitur utama:**
- Desain responsif untuk mobile dan desktop
- 3 halaman: Beranda, Portofolio, dan Kontak
- Navigasi antar halaman yang fungsional
- Animasi CSS (fade-in, skill bar, hover effects)
- Formulir kontak dengan feedback interaktif
- Menu hamburger untuk tampilan mobile
- Favicon SVG custom

**Teknologi yang digunakan:**
- HTML5 semantik
- CSS3 (Flexbox, Grid, Custom Properties, Animations, Media Queries)
- JavaScript vanilla (hanya untuk toggle menu & form feedback)
- Google Fonts (Fraunces + DM Sans)
- Font Awesome 6 (ikon)

---

## Struktur Folder dan File

```
personal-website/
├── index.html          # Halaman utama (beranda)
├── portfolio.html      # Halaman portofolio
├── contact.html        # Halaman kontak
├── LAPORAN.md          # Laporan proyek ini
└── style/
    └── main.css        # Seluruh styling (CSS eksternal)
```

---

## Link Website

> 🔗 **[https://alexmahendra.github.io/personal-website](https://alexmahendra.github.io/personal-website)**
> *(Ganti dengan link GitHub Pages / Netlify / Vercel kamu setelah deploy)*

---

## Screenshot SSH Berhasil Dikonfigurasi

> **[Tambahkan screenshot output `ssh -T git@github.com` di sini]**
>
> Contoh output yang diharapkan:
> ```
> Hi alexmahendra! You've successfully authenticated, but GitHub does not provide shell access.
> ```

---

## Screenshot Validasi W3C HTML

> **[Tambahkan screenshot hasil validasi dari https://validator.w3.org/ di sini]**
>
> Validasi dilakukan untuk ketiga halaman:
> - `index.html` — ✅ No errors or warnings
> - `portfolio.html` — ✅ No errors or warnings
> - `contact.html` — ✅ No errors or warnings

---

## Screenshot Validasi W3C CSS

> **[Tambahkan screenshot hasil validasi dari https://jigsaw.w3.org/css-validator/ di sini]**
>
> - `style/main.css` — ✅ No errors found

---

## Screenshot Lighthouse (Bonus)

> **[Tambahkan screenshot hasil Lighthouse di sini jika mengerjakan bonus]**
>
> Target: Performance ≥ 80 dan Accessibility ≥ 80

---

## Catatan Teknis

- Seluruh styling menggunakan CSS eksternal (`style/main.css`) — tidak ada inline style
- Semua elemen `<img>` memiliki atribut `alt` yang deskriptif
- Navigasi dapat diakses dengan keyboard (tombol Tab)
- Kontras warna memenuhi rasio minimal 4.5:1 (teks gelap `#1a1a18` di atas latar `#F5F0EA`)
- Penamaan file menggunakan huruf kecil tanpa spasi
