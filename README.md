# SDA-WEEK-7-SLL
📌 Deskripsi Program

Program ini merupakan implementasi struktur data Single Linked List untuk mengelola data kota dan nama manusia. Program dibuat dalam bahasa C dan menggunakan konsep linked list untuk menyimpan data nama dalam setiap kota.

Fitur utama program:

- Menambahkan kota baru ke dalam sistem

- Menambahkan nama manusia ke kota tertentu

- Menghapus kota beserta semua nama manusianya

- Menghapus nama tertentu dari sebuah kota

- Menampilkan semua data kota dan nama manusia

- Mencari data berdasarkan kota tertentu
  

📁 Struktur File

├── 📄 linked.h //  Header file untuk operasi linked list dasar

├── 📄 linked.c //  Implementasi operasi linked list dasar

├── 📄 SLL.h //     Header file untuk sistem manajemen kota-nama

├── 📄 SLL.c //     Implementasi sistem manajemen kota-nama

├── 📄 main.c //    Program utama dengan antarmuka menu

└── 📄 boolean.h // Definisi tipe data boolean


🔄 Alur Program

1. **Inisialisasi**:
   - Program memulai dengan menginisialisasi array kota
   - Menampilkan menu utama dengan 7 pilihan

2. **Operasi Tambah Data**:
   - Tambah Kota: Memasukkan nama kota baru ke dalam sistem
   - Tambah Nama: Memasukkan nama manusia ke kota tertentu

3. **Operasi Hapus Data**:
   - Hapus Kota: Menghapus kota beserta semua nama manusianya
   - Hapus Nama: Menghapus nama tertentu dari kota tertentu

4. **Operasi Tampil Data**:
   - Tampilkan Semua: Menampilkan seluruh data kota dan nama manusia
   - Tampilkan per Kota: Menampilkan data nama manusia untuk kota tertentu

5. **Keluar**:
   - Membersihkan semua alokasi memori sebelum program berakhir

🌆 Visualisasi

```text
┌─────────────────┐      ┌─────────────────┐      ┌─────────────────┐
│     KOTA 1      │      │     KOTA 2      │      │     KOTA 3      │
├─────────────────┤      ├─────────────────┤      ├─────────────────┤
│  🏙️ JAKARTA     |      │  🏙️ BANDUNG    │       │  🏙️ SURABAYA    │
│  HEAD: ─────────┼─────>│  HEAD: ─────────┼─────>│  HEAD: NULL     │
└────────┬────────┘      └────────┬────────┘      └─────────────────┘
         │                        │
         ▼                        ▼
┌─────────────────┐      ┌─────────────────┐
│    NODE 1       │      │    NODE 1       │
├─────────────────┤      ├─────────────────┤
│  👤 Nama: Budi  │      │  👤 Nama: Ani   │
│  🔗 Next: ──────┼─┐    │  🔗 Next: ──────┼─┐
└─────────────────┘ │    └─────────────────┘  │
                    │                         │
                    ▼                         ▼
   ┌─────────────────┐         ┌─────────────────┐
   │    NODE 2       │         │    NODE 2       │
   ├─────────────────┤         ├─────────────────┤
   │  👤 Nama: Citra │        │  👤 Nama: Rudi  │
   │  🔗 Next: NULL  │        │  🔗 Next: NULL  │
   └─────────────────┘         └─────────────────┘
```

🎯 Lesson Learned
- Implementasi praktis Single Linked List dalam kasus nyata

- Penggunaan array of linked lists untuk struktur data yang lebih kompleks


📝 Catatan

Program ini dikembangkan sebagai bahan pembelajaran struktur data dan pemrograman C. Kritik dan saran untuk pengembangan lebih lanjut sangat diterima.
