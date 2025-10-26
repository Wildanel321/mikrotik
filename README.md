# Mikrotik Products Landing Page

Website landing page elegan dan responsif untuk mempromosikan produk-produk Mikrotik. Dibangun menggunakan HTML, CSS, dan JavaScript murni tanpa framework eksternal.

## Fitur Utama

### 🎨 Desain Modern
- Desain clean dan profesional dengan skema warna biru-abu corporate
- Font Poppins dari Google Fonts untuk tampilan modern
- Layout responsif yang kompatibel dengan desktop, tablet, dan mobile

### 📱 Navigasi Responsif
- Header fixed dengan logo Mikrotik
- Menu navigasi: Home, Produk, Tentang, Kontak
- Menu hamburger untuk perangkat mobile

### 🏠 Hero Section
- Banner besar dengan gambar latar belakang
- Slogan "Power Your Network with Mikrotik"
- Tombol call-to-action yang mengarah ke bagian Home

### 🏡 Bagian Home
- Judul "Solusi Jaringan Terdepan"
- Deskripsi singkat tentang Mikrotik
- Grid fitur utama: RouterOS, Perangkat Keras Berkualitas, Dukungan Komunitas
- Statistik perusahaan: 25+ Tahun Pengalaman, 100M+ Perangkat Terpasang, 150+ Negara Pengguna

### 🛍️ Bagian Produk
- Grid produk dengan 3 produk utama:
  - RouterBoard
  - hAP ac²
  - CRS Series
- Setiap kartu produk memiliki gambar, nama, deskripsi singkat, dan tombol "Lihat Detail"

### 🔍 Modal Detail Produk
- Popup modal untuk detail produk
- Gambar produk yang lebih besar
- Deskripsi lengkap
- Tabel spesifikasi teknis
- Tombol close dan klik di luar modal untuk menutup

### ℹ️ Bagian Tentang
- Sejarah singkat Mikrotik (didirikan 1996)
- Fokus pada perangkat keras dan perangkat lunak jaringan
- Keunggulan: Inovasi, komunitas, kustomisasi

### 📞 Bagian Kontak
- Formulir kontak sederhana (nama, email, pesan)
- Tombol WhatsApp untuk chat langsung dengan sales
- Nomor WhatsApp placeholder yang dapat diganti

### ✨ Animasi dan Interaktivitas
- Animasi fade-in pada hero section
- Scroll animations menggunakan Intersection Observer
- Hover effects pada kartu produk dan fitur
- Smooth scrolling untuk navigasi anchor links
- Transisi halus pada semua elemen interaktif

## Teknologi yang Digunakan

- **HTML5**: Struktur semantik dan aksesibilitas
- **CSS3**: Flexbox, Grid, animasi, dan media queries
- **JavaScript ES6**: DOM manipulation, event handling, dan Intersection Observer
- **Google Fonts**: Font Poppins untuk typography

## Struktur File

```
mikrotik-landing-page/
├── index.html          # File utama website
└── README.md           # Dokumentasi ini
```

## Cara Menjalankan

1. **Clone atau download** file `index.html`
2. **Buka di browser** dengan double-click pada file, atau
3. **Jalankan server lokal**:
   ```bash
   python3 -m http.server 8000
   ```
   Kemudian buka `http://localhost:8000/index.html`

## Kustomisasi

### Mengubah Konten
- Edit teks langsung di file `index.html`
- Cari komentar HTML untuk menemukan bagian yang ingin diubah

### Mengubah Styling
- Cari komentar CSS di bagian `<style>` untuk setiap section
- Sesuaikan warna, ukuran, dan animasi sesuai kebutuhan

### Menambah Produk
- Duplikasi struktur `<div class="product-card">` di bagian Products
- Tambahkan case baru di fungsi `openModal()` di JavaScript

### Mengubah Kontak
- Ganti nomor WhatsApp di atribut `href` tombol WhatsApp
- Sesuaikan placeholder form jika diperlukan

## Browser Support

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+

## Optimisasi

- **Performance**: Gambar dioptimalkan, font dari CDN
- **SEO**: Meta tags lengkap, struktur HTML semantik
- **Accessibility**: Alt text pada gambar, keyboard navigation
- **Mobile-first**: Responsive design dengan breakpoint 768px

## Lisensi

Website ini dibuat untuk tujuan demonstrasi dan dapat digunakan secara bebas untuk promosi produk Mikrotik.

## Kontak

Untuk pertanyaan atau kustomisasi lebih lanjut, hubungi tim development.
