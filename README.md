# Ibadah Tracker - Islamic Worship Habit Tracker

![Ibadah Tracker Banner](https://images.unsplash.com/photo-1564769625688-8178d915b01b?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80)

## Overview

Ibadah Tracker adalah aplikasi React Native yang dirancang untuk membantu umat Muslim melacak, mengelola, dan mempertahankan aktivitas ibadah harian mereka. Aplikasi ini menyediakan antarmuka yang indah dan intuitif untuk mencatat berbagai jenis ibadah Islam, mengatur prioritas, dan merayakan pencapaian spiritual.

## Fitur Utama

### Fungsionalitas Inti
- **Lacak Berbagai Jenis Ibadah**: Catat dan pantau berbagai bentuk ibadah Islam termasuk:
  - Sholat Wajib
  - Sholat Sunnah
  - Membaca Al-Quran
  - Dzikir
  - Puasa
  - Sedekah
  - Doa
  - Kajian

- **Pelacakan Waktu Sholat**: 
  - Lihat waktu sholat saat ini
  - Lihat hitungan mundur ke sholat berikutnya
  - Indikator visual untuk periode sholat saat ini

- **Sistem Prioritas**:
  - Tandai aktivitas ibadah sebagai Wajib, Penting, atau Sunnah
  - Filter aktivitas berdasarkan tingkat prioritas

- **Manajemen Aktivitas**:
  - Tambah, edit, dan hapus aktivitas ibadah
  - Tandai aktivitas sebagai selesai
  - Arsipkan aktivitas yang telah selesai
  - Filter berdasarkan status penyelesaian

### Pengalaman Pengguna yang Ditingkatkan
- **Sistem Pencapaian**:
  - Buka pencapaian berdasarkan konsistensi ibadah
  - Pelacakan kemajuan visual untuk setiap pencapaian
  - Animasi perayaan saat pencapaian dibuka

- **Konten Inspirasional**:
  - Galeri gambar Islam yang menginspirasi
  - Koleksi kutipan Al-Quran dan hadits motivasi yang berganti-ganti

- **Pemilihan Tanggal**:
  - Kalender bawaan untuk menjadwalkan aktivitas ibadah
  - Antarmuka pemilihan tanggal yang mudah

- **UI/UX yang Indah**:
  - Animasi dan transisi yang halus
  - Interaksi berbasis gerakan yang intuitif
  - Skema warna yang menyenangkan secara visual berdasarkan estetika Islam

## Implementasi Teknis

### Dibangun Dengan
- React Native dengan Expo
- TypeScript untuk keamanan tipe
- Tailwind CSS (melalui twrnc) untuk styling
- AsyncStorage untuk persistensi data lokal
- React Native Animated API untuk animasi yang lancar

### Komponen Utama
- Implementasi kalender kustom
- Sistem pelacakan pencapaian
- Perhitungan waktu sholat
- Perayaan penyelesaian dengan animasi
- Modal pemilihan kategori

## Instalasi

```bash
# Clone repository
git clone https://github.com/yourusername/ibadah-tracker.git

# Navigasi ke direktori proyek
cd ibadah-tracker

# Install dependencies
npm install

# Mulai server pengembangan Expo
npx expo start
```

## Penggunaan

1. **Tambahkan aktivitas ibadah baru**:
   - Pilih jenis ibadah
   - Masukkan nama aktivitas
   - Tetapkan tanggal/waktu
   - Pilih tingkat prioritas
   - Ketuk "Tambah Ibadah"

2. **Selesaikan aktivitas**:
   - Ketuk kotak centang di samping aktivitas
   - Konfirmasi penyelesaian dengan mengetuk tanda centang
   - Ucapkan "Alhamdulillah" untuk mengarsipkan aktivitas yang telah selesai

3. **Lacak kemajuan Anda**:
   - Lihat statistik ringkasan di bagian atas layar
   - Periksa kemajuan pencapaian di bagian Pencapaian
   - Filter aktivitas berdasarkan status penyelesaian atau prioritas

## Screenshots

[Masukkan screenshot aplikasi Anda di sini]

## Roadmap

- [ ] Tambahkan fitur komunitas untuk berbagi pencapaian
- [ ] Implementasikan pencari arah Qibla
- [ ] Tambahkan notifikasi untuk waktu sholat
- [ ] Integrasi dengan kalender Islam untuk hari-hari khusus
- [ ] Tambahkan dukungan multi-bahasa

## Kontribusi

Kontribusi sangat diterima! Silakan kirimkan Pull Request.

1. Fork proyek
2. Buat branch fitur Anda (`git checkout -b feature/fitur-luar-biasa`)
3. Commit perubahan Anda (`git commit -m 'Tambahkan beberapa fitur luar biasa'`)
4. Push ke branch (`git push origin feature/fitur-luar-biasa`)
5. Buka Pull Request

## Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT - lihat file LICENSE untuk detailnya.

## Ucapan Terima Kasih

- Referensi ayat Al-Quran dan hadits
- Algoritma perhitungan waktu sholat
- Komunitas open source React Native
- Kontributor dan penguji

---

*"Sesungguhnya shalat itu adalah kewajiban yang ditentukan waktunya atas orang-orang yang beriman." - Al-Quran 4:103*
