# Sistem Pembayaran Web - UAS SPA 1124160181

Aplikasi Web SPA (Single Page Application) untuk simulasi sistem pembayaran produk/layanan kopi. Dibangun menggunakan HTML, Tailwind CSS (dengan Dark Mode), dan JavaScript Vanilla. Dirancang untuk tugas akhir UAS Web Lanjut.

---

## 🧾 Informasi Mahasiswa

- **Nama**: Arya Andromeda Putra  
- **NIM**: 1124160181  
- **Prodi**: Teknik Informatika  
- **Institusi**: Global Institute

---

## 🚀 Fitur Utama

- ✅ Form pembayaran dinamis (produk, jumlah, metode, dan kode promo)
- ✅ Dark mode dengan toggle
- ✅ Tema profesional dengan aksen oranye
- ✅ Diskon otomatis dengan kode promo
- ✅ Ringkasan dan riwayat transaksi (disimpan di localStorage)
- ✅ Statistik transaksi: total, pendapatan, dan rata-rata
- ✅ Modal konfirmasi setelah pembayaran berhasil
- ✅ Tombol hapus semua transaksi

---

## 🌙 Tema Dark Mode (Aksen Oranye)

Aplikasi ini menggunakan Tailwind CSS dengan `darkMode: 'class'`. Berikut skema warnanya:

| Elemen               | Kelas Tailwind                                      |
|----------------------|-----------------------------------------------------|
| Background           | `dark:bg-[#121212]`                                 |
| Card/Form            | `dark:bg-[#1E1E1E]`                                 |
| Input                | `dark:bg-[#2A2A2A] dark:text-white`                 |
| Primary Button       | `bg-[#FF6B00] hover:bg-[#FF851A]`                   |
| Border Input         | `dark:border-[#FF6B00]`                             |
| Text Utama           | `dark:text-white`                                   |
| Text Sekunder        | `dark:text-[#B0B0B0]`                               |
| Danger Button        | `dark:bg-[#FF3B30] hover:dark:bg-red-500`          |

---

## 📂 Struktur Proyek

```
.
├── index.html        # Halaman utama aplikasi
├── script.js         # Logika JavaScript (transaksi, promo, toggle dark mode)
├── style.css         # (Opsional) Custom styling tambahan
├── assets/           # Gambar profil & ikon
└── README.md         # Dokumentasi proyek
```

---

## 🎨 Kode Promo

Gunakan kode berikut untuk diskon:
- `KOPI86` → diskon 10%
- `COFFE88` → diskon 20%

---

## ⚙️ Cara Menjalankan

1. **Clone atau download** repositori ini.
2. Buka file `index.html` di browser modern (Chrome/Edge/Firefox).
3. Tidak membutuhkan server backend — semua data disimpan di **localStorage**.

---

## 🧑‍💻 Teknologi yang Digunakan

- HTML5
- Tailwind CSS (v3+, CDN)
- JavaScript (Vanilla)
- LocalStorage (Web API)

---

## 📸 Tampilan Antarmuka

- Light Mode: Latar biru ke putih, nuansa lembut
- Dark Mode: Latar abu gelap dengan aksen oranye profesional

---

## ✍️ Lisensi

Proyek ini dibuat sebagai tugas akademik dan bebas digunakan untuk pembelajaran.
