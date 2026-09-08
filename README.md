# Tugas Pertemuan 1 - Praktikum Pemrograman Mobile

* Nama: Edgina Syafa Ayu Wicaksono
* NIM: H1D024046

## Penjelasan Program

Aplikasi ini merupakan aplikasi mobile Android berbasis Jetpack Compose (Kotlin) yang dibuat untuk memenuhi Tugas Pertemuan 1 Praktikum Pemrograman Mobile. Aplikasi bernama **Jualan** menampilkan halaman "Tentang Jualan", yaitu sebuah platform yang mewadahi produk lokal UMKM di wilayah Kabupaten Purbalingga, Jawa Tengah.

### Fitur dan Alur Kerja Aplikasi:

1. **Icon Aplikasi Custom**
   * Icon bawaan Android Studio (robot hijau) diganti menggunakan Image Asset Studio dengan icon custom bertema tumbuhan/daun yang merepresentasikan aplikasi Jualan.

2. **Halaman Utama (Tentang Jualan)**
   * **Header Lingkaran (Box + CircleShape):** Menampilkan lingkaran abu-abu berisi tulisan "Jualan" di bagian atas layar, dibuat menggunakan komponen `Box` dengan `Modifier.clip(CircleShape)`.
   * **Judul:** Teks "Tentang Jualan" ditampilkan dengan ukuran besar dan tebal (`fontSize = 24.sp`, `fontWeight = FontWeight.Bold`).
   * **Deskripsi Aplikasi:** Teks penjelasan singkat mengenai tujuan aplikasi Jualan sebagai wadah produk UMKM lokal.
   * **Bagian Misi (Row):** Menampilkan baris berlatar abu-abu terang berisi "Misi Kami: Memajukan UMKM Lokal", disusun menggunakan komponen `Row` dengan pembagian proporsi ruang (`Modifier.weight()`).

3. **Tata Letak (Layout)**
   * Seluruh elemen disusun secara vertikal menggunakan `Column` dengan jarak antar elemen diatur menggunakan `Spacer`.
   * Elemen diposisikan di tengah secara horizontal menggunakan `Alignment.CenterHorizontally`.

## Teknologi yang Digunakan

- **Bahasa Pemrograman:** Kotlin
- **UI Toolkit:** Jetpack Compose (Declarative UI)
- **IDE:** Android Studio
- **Build Tool:** Gradle (Kotlin DSL)
- **Minimum SDK:** API 29 (Android 10.0)

## Screenshot

<img width="250" alt="WhatsApp Image 2026-09-08 at 19 45 17" src="https://github.com/user-attachments/assets/862e3303-b67e-49e9-ade2-2a6e7462bbde" />

<img width="250" alt="WhatsApp Image 2026-09-08 at 19 56 05" src="https://github.com/user-attachments/assets/70effcea-7b28-4113-92e3-68f740408305" />


