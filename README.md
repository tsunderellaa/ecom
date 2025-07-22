# App E-Commerce Khusus SMEKAR

Platform jual-beli full-stack eksklusif untuk lingkungan SMK Negeri 1 Karawang (SMEKAR).  
Dibuat dengan Laravel + React, aplikasi ini memungkinkan siswa dan guru untuk bertransaksi secara aman dan terstruktur berdasarkan peran dan kelas.

---

## Fitur
- Auth System aman dengan Laravel + React
- Access khusus dengan roles menggunakan Spatie
- Product System (CRUD, Upload Gambar, Filter, Kategori)
- Moderasi gambar dengan Sightengine AI
- Sistem cart dan checkout
- History pesanan
- Tampilan dan animasi modern menggunakan AOS.js dan Anime.js
- Dashboard admin untuk managemen dan moderasi
- Telah di tes dengan PHPUnit
- Frontend di deploy di Vercel

## Tech Stack

### Front-end
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [AOS.js](https://michalsnik.github.io/aos/) - Animasi Scroll
- [Anime.js](https://animejs.com/) - Transisi
- [Axios](https://axios-http.com)

### Back-end
- [Laravel](https://laravel.com)
- [Spatie Laravel-permission](https://spatie.be/docs/laravel-permission)
- [PHPUnit](https://phpunit.de/) – Unit testing
- [Sightengine API](https://sightengine.com/) – AI untuk moderasi gambar
- [Supabase](https://supabase.com/) – Penyimpanan gambar

### Database
- MySQL (via XAMPP & Adminer)
- ERD Visualizer dengan [DrawSQL](https://drawsql.app)

**[Complete Project Timeline](https://www.notion.so/Project-Timeline-238eb5326e73806ea1b5c263facd5344)**

---

##  🛠  Setup Lokal
1. **Clone Repo**
   ```bash
   git clone https://github.com/tsunderellaa/ecom.git
   cd ecommerce
2. **Install package dependency**
   ```bash
   composer install
   npm install
   cp .env.example .env
   php artisan key:generate
3. **Jalankan Migraasi dan Seed**
   ```bash
   php artisan migrate --seed
4. **Jalankan server**
   ```bash
   php artisan serve
5. **Jalankan React Dev Server**
   ```bash
   cd resource/js
   npm run dev
6. **Sightengine setup**
   - Dapatkan API dari [Sightengine](https://sightengine.com/)
   - Taruh API Key ke `.env`

# Credit

## Dibuat dengan ❤ oleh kelompok 4 
- M Faris Anwar - Ketua Kelompok
- [M Arif Sulaiman](https://github.com/arfsulaiman) - Lead Front End
- [Your Kitten ≽^-⩊-^≼](https://github.com/tsunderellaa) - Lead Back End
- Nur Azizah - Lead UI/UX Designer 
- Vacant
- Vacant

# Lisensi
Proyek ini dibuat untuk keperluan pembelajaran dan presentasi internal. Tidak untuk komersial.
