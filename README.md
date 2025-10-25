

# 🌍 Aplikasi Travel Explorer

Aplikasi mobile untuk menjelajahi berbagai destinasi wisata dengan tampilan yang sederhana, bersih, dan mudah digunakan.
Dibangun menggunakan **React Native** dan **TypeScript** agar performa cepat dan kode tetap terstruktur.

---

## ✨ Fitur Utama

* 🧩 **Komponen DestinationCard yang Reusable**
  Menampilkan destinasi lengkap dengan gambar, negara, rating, harga per orang, dan tombol favorit.

* 🧭 **Navigasi Bottom Tabs**
  Terdiri dari tiga menu utama: **Home**, **Ticket**, dan **Profile** dengan ikon yang berubah sesuai tab aktif.

* 📍 **Halaman Detail Destinasi**
  Setiap destinasi memiliki halaman detail sendiri dengan deskripsi, rating, rekomendasi wisata, dan tombol **Book Now**.

* 💬 **Popup Review Traveler**
  Terdapat tombol *“View All”* untuk melihat semua ulasan dalam tampilan modal popup.

* 🎟️ **Halaman Ticket (Daftar Tiket)**
  Menampilkan tiket berdasarkan kategori: *Hotel*, *Pesawat*, *Villa*, dan *Atraksi*, lengkap dengan jadwal dan harga.

* ❤️ **Interaksi Ringan & Tampilan Modern**
  Efek tekan (*pressed state*), ikon hati (favorit), serta transisi halus antarhalaman untuk pengalaman yang lebih hidup.

---

## 🧰 Teknologi

* React Native
* TypeScript
* React Navigation v6
* StyleSheet bawaan React Native (tanpa library UI tambahan)
* Data dummy lokal (array/JSON)

---

## 📂 Struktur Folder

```
project-root/
│
├── assets/
│   ├── images/
│   │   ├── labuan-bajo.jpg
│   │   ├── venice.jpg
│   │   ├── kyoto.jpg
│   │   └── bali.jpg
│   └── screenshots/
│       ├── onboarding.png
│       ├── home.png
│       ├── detail.png
│       └── ticket.png
│
├── components/
│   └── DestinationCard.tsx
│
├── navigation/
│   └── BottomTabs.tsx
│
├── screens/
│   ├── Onboarding.tsx
│   ├── Home.tsx
│   ├── Detail.tsx
│   ├── Ticket.tsx
│   └── Profile.tsx
│
└── App.tsx
```

---

## 🚀 Cara Menjalankan

```bash
# Instal semua dependensi
npm install

# Jalankan Metro Bundler
npx react-native start

# Jalankan di Android
npx react-native run-android

# Jalankan di iOS (opsional)
npx react-native run-ios
```

---

## 📱 Alur Penggunaan

1. Saat aplikasi dibuka, tampil halaman **Onboarding**
2. Masuk ke **Home** untuk melihat daftar destinasi populer
3. Pilih salah satu destinasi untuk melihat **Detail Screen**
4. Tekan **View All** untuk melihat ulasan lengkap
5. Tekan **Book Now** untuk lanjut ke halaman **Ticket**

---

## 👤 Pengembang

**Nama:** Sabri
**Judul Proyek:** Travel Explorer App
**Dibuat dengan:** React Native & TypeScript
**Tahun:** 2025

---
