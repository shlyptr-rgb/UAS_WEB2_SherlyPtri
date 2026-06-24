Inventaris-Pro: Sistem Manajemen Barang

Aplikasi ini adalah sistem informasi inventaris berbasis web yang dibangun untuk memudahkan pengelolaan stok barang, memantau total aset secara real-time, dan memastikan keamanan data melalui sistem autentikasi.

🚀 Fitur Utama
Autentikasi Aman: Sistem login berbasis token (JWT) dengan Navigation Guard.

Manajemen Barang (CRUD): Tambah, lihat, ubah, dan hapus data barang dengan mudah.

Statistik Dashboard: Rekapitulasi otomatis Total Jenis Barang, Total Stok, dan Total Nilai Aset.

Pencarian Cepat: Fitur filter barang secara real-time untuk mempercepat pencarian.

Antarmuka Modern: Desain responsif dengan tema Dark Mode.
<img width="1915" height="996" alt="image" src="https://github.com/user-attachments/assets/3e509d9f-a571-416f-ac77-6a04f73c46f2" />
<img width="1915" height="990" alt="image" src="https://github.com/user-attachments/assets/642a8704-a408-4481-b50f-d8d6d1f75179" />
<img width="1915" height="999" alt="image" src="https://github.com/user-attachments/assets/65127441-df03-4b3a-b28c-590e6ad43d80" />


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

📝 Deskripsi Teknis
Aplikasi ini menerapkan arsitektur Single Page Application (SPA). Komunikasi antara frontend dan backend dilakukan menggunakan REST API dengan format JSON. Keamanan rute dikelola melalui middleware (Navigation Guard) yang memvalidasi token di setiap akses halaman privat.
Fitur Profil masih bersifat statis, sebagai Future Improvements.
