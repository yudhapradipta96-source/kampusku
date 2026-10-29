# kampusku

Nama: Pradipta Yudha
NIM: 25552012004
Kelas: TIF RP 24C CID (Konversi)
Program Studi: Teknik Informatika
Perguruan Tinggi: Universitas Teknologi Bandung

# 🎓 Kampusku - Aplikasi Informasi Jadwal & Mata Kuliah

Aplikasi mobile berbasis **Flutter** yang dikembangkan untuk menampilkan daftar mata kuliah, jadwal perkuliahan, serta informasi akademik kampus secara terstruktur dan terintegrasi. Proyek ini disusun sebagai bagian dari tugas praktikum mata kuliah **Pemrograman Mobile II**.

---

## Fitur Utama

- Daftar Mata Kuliah & Jadwal**: Menampilkan daftar mata kuliah beserta kode, hari, dan jumlah SKS.
- Lokalisasi Tanggal Bahasa Indonesia**: Format tanggal dinamis mengikuti standar lokal Indonesia menggunakan package `intl`.
- Responsive UI**: Tampilan antarmuka yang bersih dan responsif untuk berbagai ukuran layar perangkat Android.

---

## Struktur Proyek

Proyek ini menerapkan arsitektur *layered/modular pattern* agar kode rapi dan mudah dipelihara:

```text
lib/
├── models/         # Model data (misal: mata_kuliah.dart)
├── screens/        # Tampilan halaman utama & detail (misal: beranda_screen.dart)
├── widgets/        # Komponen UI reusable (misal: mata_kuliah_card.dart)
├── services/       # Layanan data / API
└── main.dart       # Titik masuk utama aplikasi & konfigurasi awal