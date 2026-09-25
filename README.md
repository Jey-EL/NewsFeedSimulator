# News Feed Simulator

Aplikasi simulasi news feed menggunakan Kotlin dan Jetpack Compose.

## Fitur

Aplikasi ini menerapkan:

- Flow untuk menghasilkan berita baru setiap 2 detik.
- Filter berita berdasarkan kategori Technology.
- Transformasi data berita menggunakan Flow operator.
- StateFlow untuk menyimpan jumlah berita yang telah dibaca.
- Coroutines dengan async/await untuk mengambil detail berita secara asynchronous.
- Error handling pada proses pengambilan detail berita.

## Teknologi

- Kotlin
- Jetpack Compose
- Kotlin Coroutines
- Flow
- StateFlow
- Android Studio

## Cara Menjalankan

1. Clone repository ini.
2. Buka project menggunakan Android Studio.
3. Tunggu proses Gradle Sync selesai.
4. Jalankan aplikasi menggunakan emulator atau perangkat Android.
5. Aplikasi akan menampilkan berita kategori Technology yang dihasilkan setiap 2 detik.

## Cara Menggunakan

### 1. Melihat Berita

Berita baru akan muncul secara otomatis setiap 2 detik.

### 2. Menandai Berita sebagai Dibaca

Tekan tombol:

`Tandai Sudah Dibaca`

Jumlah berita yang dibaca akan bertambah.

### 3. Mengambil Detail Berita

Tekan tombol:

`Ambil Detail Berita`

Aplikasi akan mengambil detail berita secara asynchronous.

## Struktur Project

```text
NewsFeedSimulator
├── app
│   └── src
│       └── main
│           └── java
│               └── com.example.newsfeedsimulator
│                   ├── MainActivity.kt
│                   ├── NewsViewModel.kt
│                   └── news
│                       ├── News.kt
│                       └── NewsRepository.kt
└── README.md