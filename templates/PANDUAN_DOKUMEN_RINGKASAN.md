# 📑 PANDUAN PENYUSUNAN DOKUMEN RINGKASAN KARYA (PDF 5–7 HALAMAN)
### AXIS 2026 — Lampiran A Guidebook Peserta

Dokumen Ringkasan Karya merupakan salah satu luaran wajib yang dievaluasi langsung oleh dewan juri untuk menilai aspek **Analisis Kebutuhan dan Perancangan Sistem (Bobot: 30%)** serta konsistensi teknis karya.

---

## 📌 Ketentuan Format Berkas
1. **Format File**: PDF tunggal (`.pdf`).
2. **Panjang Halaman**: **Tepat 5 sampai 7 halaman** (sudah termasuk halaman identitas/cover awal). Dokumen di bawah 5 halaman atau melebihi 7 halaman dapat dikenakan penalti penilaian.
3. **Ukuran Kertas**: A4, orientasi Portrait.
4. **Margin**: 2,5 cm (Standar/Normal di seluruh sisi).
5. **Tipografi**: Font standar yang mudah dibaca (misal: *Inter, Roboto, Arial, Times New Roman*), ukuran font 11–12 pt untuk teks utama, 1.15–1.5 line spacing.
6. **Penamaan File**: `AXIS2026_[Kategori]_[Nama Tim]_[Nama Perguruan Tinggi].pdf`  
   *(Contoh: `AXIS2026_KategoriA_GarudaDev_UniversitasIndonesia.pdf`)*

---

## 📄 Rekomendasi Struktur Tiap Halaman

### Halaman 1: Identitas Tim & Ringkasan Eksekutif (*Executive Summary*)
- **Header**: Logo Kompetisi AXIS 2026, Logo Perguruan Tinggi, dan Logo Tim/Aplikasi.
- **Judul Karya**: Nama aplikasi web dan *tagline* singkat solusi.
- **Identitas Tim**: Nama tim, perguruan tinggi, data lengkap ketua dan anggota tim (Nama, NIM, Program Studi).
- **Kategori Studi Kasus**: Pilih Kategori A, B, atau C.
- **Executive Summary**: 1–2 paragraf padat yang merangkum latar belakang masalah, urgensi solusi, pendekatan arsitektur teknologi yang dipilih, dan dampak nyata yang dihasilkan sistem.

---

### Halaman 2: Latar Belakang, Identifikasi Masalah & Target Pengguna
- **Latar Belakang Konteks**: Gambaran kondisi operasional organisasi/bisnis yang menjadi objek studi kasus.
- **Rumusan Masalah (Pain Points)**: Masalah konkret apa yang dihadapi pengguna sebelum adanya sistem ini (misal: pencatatan manual berantakan, keterlambatan persetujuan, kurangnya transparansi).
- **Target Pengguna (User Persona)**: Karakteristik pihak yang akan menggunakan sistem (contoh: Manajer Operasional, Staf Administrasi, Klien/Masyarakat).
- **Tujuan & Manfaat**: Dampak positif yang ingin dicapai (misal: efisiensi waktu pemrosesan, akurasi data 100%, kemudahan pelacakan berkas).

---

### Halaman 3: Proses Bisnis & Alur Kerja Sistem (Business Process Workflow)
- **Komparasi Proses**: Perbandingan ringkas alur kerja lama (*as-is*) versus alur kerja digital yang baru (*to-be*).
- **Diagram Alur (Workflow Diagram)**:
  - Sertakan diagram grafis seperti **Flowchart**, **BPMN (Business Process Model and Notation)**, atau **Activity Diagram**.
  - Tunjukkan interaksi antar-aktor (peran pengguna) dan bagaimana data mengalir dari pengajuan hingga selesai.

---

### Halaman 4: Arsitektur Sistem & Perancangan Basis Data
- **Diagram Arsitektur Sistem**:
  - Gambaran keterhubungan antara lapisan klien (browser/device), lapisan server (PHP / Framework), dan lapisan persistensi data (MySQL Database).
- **Desain Basis Data (ERD - Entity Relationship Diagram)**:
  - Diagram visual ERD yang menunjukkan entitas, atribut kunci (*Primary Key, Foreign Key*), kardinalitas relasi ($1:1$, $1:N$, $M:N$), dan normalisasi tabel yang rapi.
  - Kamus data ringkas untuk tabel-tabel utama.

---

### Halaman 5: Matriks Fitur & Pembagian Peran Pengguna (RBAC)
- **Matriks Hak Akses (Role-Based Access Control / RBAC)**:
  - Tabel matriks hak akses antar peran (misal: Admin, Manajer, Staf, User Publik) terhadap fitur-fitur seperti Create, Read, Update, Delete, Approve, dan Export.
- **Deskripsi Fungsionalitas Kunci**:
  - Penjelasan detil bagaimana fitur-fitur unggulan bekerja menyelesaikan tantangan studi kasus.

---

### Halaman 6: Spesifikasi Teknologi & Dokumentasi Antarmuka (UI Showcase)
- **Tech Stack Specification**:
  - PHP version, MySQL version, Web server, UI library (Tailwind/Bootstrap), CSS/JS plugins.
- **Tangkapan Layar (Screenshots) Antarmuka**:
  - Tampilkan 3–4 screenshot berkualitas tinggi dari antarmuka utama sistem (misal: Dashboard, Form Transaksi/Pengajuan, Tampilan Mobile Responsif).
  - Berikan *caption* atau keterangan singkat pada masing-masing tangkapan layar.

---

### Halaman 7: Kesimpulan, Nilai Keberlanjutan & Tautan Akses
- **Kesimpulan**: Rangkuman pencapaian sistem terhadap tujuan awal kompetisi.
- **Analisis Dampak & Keberlanjutan (Sustainability & Scalability)**:
  - Potensi adopsi pada lingkungan organisasi riil dan rencana pengembangan fitur di masa depan.
- **Tautan Akses Penting**:
  - 🔗 URL Live Deployment Website: `https://...`
  - 🔗 URL Repositori GitHub: `https://github.com/...`
  - 🔗 URL Video Demonstrasi (Maks. 3 Menit): `https://youtu.be/...`
  - 🔑 Kredensial Akun Demonstrasi Juri (Role 1 & Role 2).
