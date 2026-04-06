______________________
|Nama| Lina Mushlihah|
|----------|----------|
|NRP| 5025251063|
----------------
# Implementasi Stack (C++)

## Deskripsi
Program ini berisi implementasi struktur data **stack** menggunakan bahasa C++. Stack adalah struktur data yang menggunakan prinsip **LIFO (Last In First Out)**, yaitu data terakhir yang dimasukkan akan menjadi yang pertama dikeluarkan.

Pada repository ini terdapat dua pendekatan:
- Stack menggunakan **array**
- Stack menggunakan **linked list**

---

## Konsep Dasar Stack
Operasi utama pada stack:
- **Push** → menambahkan data ke stack
- **Pop** → menghapus data dari stack
- **Peek** → melihat elemen teratas
- **isEmpty** → mengecek apakah stack kosong

---

## Implementasi

### 1. Stack dengan Array
- Menggunakan array dengan ukuran tetap
- Menggunakan variabel `top` untuk menunjuk elemen teratas
- Memiliki kemungkinan **overflow** jika penuh

### 2. Stack dengan Linked List
- Menggunakan struktur node (linked list)
- Tidak memiliki batas ukuran (selama memori tersedia)
- Lebih fleksibel dibanding array
