# 📱 UTS Pemrograman Sistem Mobile - Flutter App by Fadly

Selamat datang di repository UTS saya!  
Aplikasi ini dibuat untuk memenuhi tugas Ujian Tengah Semester mata kuliah **Pemrograman Sistem Mobile**.

## 👨‍🎓 Identitas Mahasiswa
- **Nama:** Fadly Difak Al Fatah
- **Program Studi:** Informatika

---

## 📌 Deskripsi Singkat

Aplikasi mobile sederhana berbasis **Flutter** yang menampilkan daftar postingan dan komentar menggunakan data dari API **JSONPlaceholder**.  
Tampilan aplikasi saya buat menyerupai media sosial modern agar lebih menarik dan interaktif.

---

## 🚀 Fitur Aplikasi

✅ **Login Page**  
Pengguna memasukkan email dan password (dummy login, belum terhubung backend)

✅ **Feed Page (List Post)**  
Menampilkan daftar post dari internet, dengan tampilan seperti Instagram

✅ **Interaksi Post**
- ❤️ Like → meningkatkan jumlah like lokal
- 💬 Comment → buka halaman detail
- 📤 Share → menampilkan snackbar

✅ **Detail Post Page**
Menampilkan detail isi post dan tombol "Lihat Komentar"

✅ **Comment Page**
Menampilkan komentar yang sesuai berdasarkan `postId`

---

## 🧰 Teknologi & Tools

- Flutter SDK
- Android Studio (emulator)
- Dart language
- HTTP Package (`http`)
- JSONPlaceholder API
- Material 3 UI

---

## 🗂️ Struktur Folder

```bash
lib/
├── main.dart
└── pages/
    ├── login_page.dart
    ├── post_list_page.dart
    ├── post_detail_page.dart
    └── comment_page.dart
