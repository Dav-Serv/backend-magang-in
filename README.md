# Tutorial Penggunaan Magang-in

Magang-in adalah platform AI yang menghubungkan mahasiswa dengan lowongan magang sesuai keahlian. Dokumen ini menjelaskan cara penggunaan platform untuk tiga peran: **Pengguna (Mahasiswa)**, **Mitra (Perusahaan)**, dan **Admin**.

---

## Daftar Isi

1. [Memulai](#memulai)
2. [Untuk Pengguna (Mahasiswa)](#untuk-pengguna-mahasiswa)
3. [Untuk Mitra (Perusahaan)](#untuk-mitra-perusahaan)
4. [Untuk Admin](#untuk-admin)
5. [FAQ & Troubleshooting](#faq--troubleshooting)

---

## Memulai

### Mengakses Platform

Buka platform melalui browser:
- **Production:** https://magangin-ten.vercel.app
- **Lokal (development):** http://localhost:5173

### Mendaftar Akun Baru

1. Klik **Daftar** di pojok kanan atas
2. Isi nama, email, dan password
3. Klik **Sign Up**, otomatis diarahkan ke halaman onboarding

Atau pakai **Sign in with Google** untuk daftar/login lebih cepat.

### Login

1. Klik **Masuk**
2. Masukkan email dan password
3. Atau klik **Sign in with Google**

### Switch Tema (Gelap/Terang)

Klik icon matahari/bulan di Navbar atau di sidebar dashboard. Pilihan tersimpan otomatis.

---

## Untuk Pengguna (Mahasiswa)

### 1. Onboarding (Sekali Setelah Daftar)

Setelah register, kamu akan diarahkan ke halaman onboarding untuk memasukkan skill. Pilih salah satu:

#### A. Self-Declaration (Manual)
1. Pilih **Pilih Manual**
2. Centang skill yang kamu kuasai dari daftar (minimal 3)
3. Filter berdasarkan kategori (Frontend, Backend, Data Science, dll) atau search
4. Klik **Lanjut ke Matching**

#### B. Upload CV (AI-Powered)
1. Pilih **Upload CV**
2. Upload file CV (PDF/JPG/PNG, max 5MB)
3. AI akan otomatis mengekstrak skill dari CV
4. Lanjut ke Matching

### 2. Lihat Rekomendasi AI

Setelah onboarding, sistem otomatis menampilkan **Hasil Rekomendasi AI** — daftar lowongan paling cocok berdasarkan skill kamu, lengkap dengan:
- **Match Score** (persentase kecocokan)
- **Match Category** — Strong / Partial / Low
- **Matched Skills** dan **Missing Skills**
- **Roadmap Belajar** untuk skill yang belum dikuasai

### 3. Eksplorasi Lowongan

Menu sidebar **Lowongan**:
- Cari berdasarkan judul, perusahaan, atau lokasi
- Filter by lokasi atau jurusan
- Klik kartu untuk lihat detail

### 4. Melamar Lowongan

1. Buka detail lowongan
2. Klik **Lamar Sekarang**
3. (Opsional) Isi cover letter
4. (Opsional) Upload CV — disimpan ke cloud storage
5. Submit

### 5. Kelola Lamaran

Menu sidebar **Lamaran Saya**:
- Lihat semua lamaran yang sudah dikirim
- Filter dengan search (nama posisi, perusahaan, lokasi)
- Status: **Menunggu Review**, **Diterima**, **Ditolak**
- Saat status masih *pending*: bisa **Edit** (ubah cover letter & CV) atau **Batalkan**

### 6. Roadmap Belajar

Menu sidebar **Roadmap** — daftar roadmap pembelajaran berdasarkan lowongan yang cocok dengan skill kamu, untuk membantu upgrade keahlian.

### 7. Update Profil

Menu sidebar **Profil**:
- Edit data diri (nama, telepon, alamat, pendidikan)
- Update skill
- **Daftar jadi Mitra** (kalau ingin berperan sebagai perusahaan)

### 8. Daftar Menjadi Mitra

Kalau ingin posting lowongan sebagai perusahaan:
1. Buka **Profil**
2. Di card **Daftar Mitra**, isi:
   - Nama Perusahaan (wajib)
   - Deskripsi Perusahaan (opsional)
3. Klik **Kirim Request Mitra**
4. Status berubah ke **Menunggu persetujuan admin**
5. Setelah disetujui admin, role berubah jadi **Mitra**, login ulang untuk akses dashboard mitra

---

## Untuk Mitra (Perusahaan)

### 1. Lengkapi Profil Perusahaan

Setelah disetujui admin, login dan buka **Profil Perusahaan**:
- Nama perusahaan, industri, ukuran perusahaan
- Tahun berdiri, alamat, telepon
- Website, LinkedIn
- Deskripsi perusahaan

Klik **Edit Profil** → **Simpan**.

### 2. Pasang Lowongan

1. Klik tombol **+ Pasang Lowongan** di sidebar
2. Isi formulir:
   - **Judul Lowongan** (wajib)
   - **Nama Perusahaan** — otomatis terisi dari profil (read-only)
   - **Lokasi** — searchable dropdown dari master location
   - **Tipe** — On-site / Remote / Hybrid
   - **Durasi**, **Level**
   - **Jurusan** — dropdown dari master major
   - **Deskripsi** (wajib)
   - **Skills Required** — multi-select dari master skill (chip)
   - **Persyaratan**, **Benefits**
3. Klik **Pasang Lowongan**

### 3. Kelola Lowongan

Menu sidebar **Lowongan Saya**:
- Statistik: total, aktif, ditutup
- Search berdasarkan judul, perusahaan, atau lokasi
- Per-lowongan: **Tutup**/**Buka** atau **Hapus**

### 4. Review Pelamar

Menu sidebar **Daftar Pelamar**:
- Default: tampilkan **semua lamaran** dari semua lowongan
- Filter dengan dropdown lowongan spesifik
- Search berdasarkan nama, email, atau judul lowongan
- Per-pelamar: lihat skill, cover letter, dan **Lihat CV** (klik untuk buka file PDF)
- Aksi: **Terima** / **Tolak**

### 5. Lihat Pelamar dari Beranda

Di beranda dashboard mitra, klik **Lihat Pelamar** pada lowongan tertentu untuk langsung filter pelamar lowongan itu.

---

## Untuk Admin

### 1. Beranda

Dashboard admin menampilkan data realtime:
- **Total Pengguna**, **Mitra Aktif**, **Total Lowongan**, **Total Lamaran**
- Notifikasi: jumlah pending mitra & pending applications
- **Tanggal & jam realtime**
- **Daftar Tunggu Verifikasi Mitra** (pending requests)
- **Tren Registrasi User** (grafik 7 hari terakhir)
- **Log Aktivitas Sistem** (user baru, lamaran baru, lowongan baru, request mitra)

### 2. Manajemen User

Menu sidebar **Manajemen User**:
- Lihat semua user (Pengguna, Mitra, Admin)
- Filter by role (tab)
- Ganti role user via dropdown
- Hapus user (cascade delete: semua relasi ikut terhapus)

### 3. Verifikasi Mitra

Menu sidebar **Verifikasi Mitra**:
- Daftar user dengan request mitra **pending**
- Detail: nama perusahaan, deskripsi, tanggal request
- Aksi:
  - **Setujui** — role user berubah ke `mitra`, otomatis bisa posting lowongan
  - **Tolak** — status berubah ke `rejected`, role tetap `pengguna`

### 4. Kelola Lowongan

Menu sidebar **Kelola Lowongan**:
- Lihat semua lowongan dari semua mitra
- Statistik total, aktif, total pelamar
- Aksi per-lowongan: **Tutup** lowongan (admin override)

### 5. Laporan & Data Analitik

Menu sidebar **Laporan & Data**:
- **Pertumbuhan 6 Bulan Terakhir** — bar chart user baru & lowongan baru per bulan
- **Success Match Rate** — persentase lamaran diterima vs total
- **Top Industri/Jurusan** — distribusi lowongan
- **Recent Insights** — pelamar baru 7 hari, total lamaran, total diterima
- **Export CSV** — download data realtime

---

## FAQ & Troubleshooting

### Login Google gagal "redirect_uri_mismatch"
Pastikan URL backend Vercel sudah didaftarkan di Google Cloud Console → OAuth Client → Authorized redirect URIs (`https://<backend>.vercel.app/api/auth/google/callback`).

### "Gagal mendapatkan rekomendasi"
AI service eksternal mungkin sedang down. Coba lagi beberapa menit kemudian. Atau pastikan kamu sudah declare skill (minimal 3).

### CV tidak muncul saat mitra klik "Lihat CV"
Pelamar belum upload CV saat melamar. Atau lamaran dibuat sebelum sistem upload diperbarui.

### Setelah onboarding, login lagi tetap diarahkan ke onboarding
Bug yang sudah diperbaiki — pastikan kamu pakai versi terbaru. Logout dan login ulang.

### Request mitra ditolak admin
Hubungi admin untuk info lebih lanjut, atau revisi data perusahaan dan request ulang.

### Refresh halaman selain root → 404
Sudah diperbaiki dengan rewrite di `vercel.json`. Pastikan sudah deploy versi terbaru.

### Halaman dashboard putih di mode gelap
Pastikan browser cache di-clear (Ctrl+Shift+R). Kalau masih ada elemen putih, laporkan halaman/komponen mana.

---

## Akses Cepat

| Role | URL Login |
|---|---|
| Pengguna | `/login` → otomatis ke `/dashboard` |
| Mitra | `/login` → otomatis ke `/mitra/dashboard` |
| Admin | `/login` (akun admin manual di-set di DB) → `/admin` |

## Kontak

- **Bug report / saran:** kontak admin via email
- **Dokumentasi teknis:** README.md di repo

---

© 2026 Magang-in Platform
