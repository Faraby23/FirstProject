## 1.1 Latar Belakang

Dengan berkurangnya minat baca masyarakat yang semakin meningkat yang merupakan satu diantara beberapa dampak yang terjadi akibat kemajuan teknologi. Maka diciptakan teknologi berupa aplikasi untuk menjembatani hal tersebut, sehingga dapat memudahkan bagi para pengguna untuk mengakses kebutuhan yang ada.
## 1.2. Deksripsi Teknologi Informasi

Teknologi informasi yang dibuat ialah berupa aplikasi perpustakaan berbasis mobile, yang mana didalamnya berisi kumpulan ebook yang disediakan oleh pencipta. Aplikasi ini akan menjadi sebagian dari alat solusi untuk menyelesaikan permasalahan yang terjadi pada masyarakat. Tidak hanya itu, adanya teknologi informasi ini juga dapat mendukung pembelajaran siswa maupun mahasiswa dalam melaksanakan studi mereka. Pengguna dapat mencari, membaca dan menandai ebook yang disukai dalam aplikasi ini.

## 1.3. Branding

- Merk: mylib.
- Tagline: Membaca lebih praktis pada layar minimalis.
- Campaign: Bagaimana membuat aplikasi yang dapat meningkatkan minat baca pengguna.
- Target user:
  - Usia 7+
  - Orang yang senang membaca
  - Orang yang ingin mencari ilmu pengetahuan
  - Orang yang sedang menekuni suatu pengetahuan
  - Orang yang ingin lebih simple dalam membaca buku
- User experience theme:
  - Mudah
  - Sederhana
  - Simple

## 2. User Story

Sebagai | Saya ingin bisa | Sehingga | Prioritas
---|---|---|---
Pengguna | mencari ebook | mendapatkan ebook yang akan dibaca | ⭐⭐⭐⭐⭐
Pengguna | menandai ebook | bisa menyatukan tempat penanda buku | ⭐⭐⭐⭐
Pengguna | melihat detail buku | mengetahui spesifikasi buku terkait | ⭐⭐⭐⭐
Pengguna | membaca ebook | dapat membaca isi dari ebook terkait | ⭐⭐⭐⭐⭐
Pengguna | memberi rating ebook | rating muncul | ⭐⭐⭐
Pengguna | memberi comment ebook | comment muncul | ⭐⭐⭐

## 3. Struktur Data
```mermaid
erDiagram
  PENGGUNA {
    int id_pengguna
    string username
    string email
    string password
    string nama_lengkap
  }

  PENGGUNA ||--o{ EBOOK : mengakses

  EBOOK {
    string nama_ebook
    string nama_penerbit
    int tahun_terbit
    string nama_language 
    int jumlah_rating
    string nama_author
    string nama_country
    int isbn
    string nama_category
    string nama_publisher
 } 
```

## 4. Arsitektur Sistem

```mermaid
flowchart BT 
  subgraph cloud
    B[Database: SQLite/postgreSQL] 
  end
  A[Aplikasi Android & iPhone: Dart - Flutter] <--> B 
```
## 5. Teknologi, Library, dan Framework
Project ini dibangun dengan menggunakan teknologi bahasa pemrograman dart yang termasuk dalam framework flutter dilengkapi oleh library bloc yang ada pada flutter itu sendiri.


## 6. Desain User Experience dan User Interface

![image](https://github.com/Faraby23/FirstProject/assets/144707254/6ac8f81b-8522-4ebd-b03a-1d539f7dd3f9)

![image](https://github.com/Faraby23/FirstProject/assets/144707254/d010f605-2326-4a65-93f7-52c369d5d7f5)

![image](https://github.com/Faraby23/FirstProject/assets/144707254/8dc408e9-b763-430a-a2ad-cb71c29142f4)

![image](https://github.com/Faraby23/FirstProject/assets/144707254/736d217d-65b5-44c4-b283-8177965876b2)

![image](https://github.com/Faraby23/FirstProject/assets/144707254/842b6049-9960-4d62-90f9-07a67508863a)

![image](https://github.com/Faraby23/FirstProject/assets/144707254/527bb4ab-9982-4aa8-ab56-25a91c859b79)

## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini
