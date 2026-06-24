Inventaris-Pro: Sistem Manajemen Barang

Aplikasi ini adalah sistem informasi inventaris berbasis web yang dibangun untuk memudahkan pengelolaan stok barang, memantau total aset secara real-time, dan memastikan keamanan data melalui sistem autentikasi.

🚀 Fitur Utama
Autentikasi Aman: Sistem login berbasis token (JWT) dengan Navigation Guard.

Manajemen Barang (CRUD): Tambah, lihat, ubah, dan hapus data barang dengan mudah.

Statistik Dashboard: Rekapitulasi otomatis Total Jenis Barang, Total Stok, dan Total Nilai Aset.

Pencarian Cepat: Fitur filter barang secara real-time untuk mempercepat pencarian.

Antarmuka Modern: Desain responsif dengan tema Dark Mode.

<img width="1915" height="950" alt="image" src="https://github.com/user-attachments/assets/ec4be8be-9ee4-4540-a629-282cdef4676e" />
<img width="1915" height="1001" alt="image" src="https://github.com/user-attachments/assets/42698234-92b4-4df0-af49-92268ef6623c" />
<img width="1915" height="947" alt="image" src="https://github.com/user-attachments/assets/0a1b69ba-91b6-40a9-bcbf-9dd1a6742407" />


🛠️ Tech Stack
Frontend: Vue.js 3, Vite, Tailwind CSS, Vue Router, Axios.

Backend: CodeIgniter 4 (RESTful API).

Database: MySQL.

⚙️ Cara Menjalankan Aplikasi
1. Backend (CodeIgniter)
Pastikan database sudah di-import (db_inventaris.sql).

Jalankan server lokal:

Bash
php spark serve
2. Frontend (Vue.js)
Masuk ke folder proyek frontend.

Install dependencies:

Bash
npm install
Jalankan aplikasi:

Bash
npm run dev
Buka di browser: http://localhost:5173/dashboard

Aplikasi ini menerapkan arsitektur Single Page Application (SPA). Komunikasi antara frontend dan backend dilakukan menggunakan REST API dengan format JSON. Keamanan rute dikelola melalui middleware (Navigation Guard) yang memvalidasi token di setiap akses halaman privat.Fitur Profil masih bersifat statis"), sebagai Future Improvements.
