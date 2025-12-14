# 🎵 Aplikasi Pemutar Musik (Python)

Aplikasi ini adalah **program pemutar musik berbasis CLI (Command Line Interface)** yang dibuat menggunakan bahasa **Python** dengan penerapan struktur data **Doubly Linked List**. Program ini mendukung dua jenis pengguna, yaitu **Admin** dan **User**, dengan fitur manajemen lagu, playlist, dan navigasi lagu.

---

## 📌 Fitur Utama

### 👨‍💼 Admin

* Menambahkan lagu ke library
* Melihat seluruh lagu
* Mengupdate data lagu (judul & artis)
* Menghapus lagu dari library dan playlist

### 👤 User

* Melihat dan mencari lagu di library
* Memutar dan menghentikan lagu
* Menambahkan lagu ke playlist
* Menghapus lagu dari playlist
* Navigasi lagu (Next & Previous)
* Rekomendasi lagu otomatis berdasarkan artis atau genre

---

## 🧱 Struktur Data yang Digunakan

### Doubly Linked List

Digunakan untuk:

* **Library Lagu**
* **Playlist**

Setiap node memiliki:

* `data` → informasi lagu
* `prev` → pointer ke node sebelumnya
* `next` → pointer ke node berikutnya

### Stack

Digunakan untuk menyimpan **riwayat lagu yang diputar**.

---

## 📂 Struktur Program

```
📁 pemutar_musik/
│── main.py        # Program utama
│── README.md      # Dokumentasi aplikasi
```

---

## ▶️ Cara Menjalankan Program

1. Pastikan Python sudah terinstall (Python 3.x)
2. Simpan kode program sebagai `main.py`
3. Jalankan program dengan perintah:

```bash
python main.py
```

---

## 📜 Contoh Data Lagu

```json
{
  "id": "1",
  "title": "Midnight Sky",
  "artist": "Miley Cyrus",
  "genre": "Pop",
  "year": 2020
}
```

---

## 🧠 Konsep yang Dipelajari

* Penerapan **Doubly Linked List**
* Operasi CRUD (Create, Read, Update, Delete)
* Modular programming
* Penggunaan global state sederhana
* Pembuatan menu interaktif CLI

---

## ✅ Kelebihan Program

* Struktur data sesuai kebutuhan playlist
* Mudah dikembangkan
* Logika program jelas dan modular

## ⚠️ Catatan

* Program berbasis terminal (CLI)
* Data tidak disimpan permanen (tanpa database/file)

---

## 👨‍🎓 Dibuat Untuk

Program ini cocok digunakan sebagai:

* Tugas struktur data
* Praktikum linked list
* Contoh implementasi playlist musik sederhana

---

✨ *Dikembangkan menggunakan Python & konsep struktur data*
