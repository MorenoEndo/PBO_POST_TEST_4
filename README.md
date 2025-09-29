# PBO Post Test 4

## Deskripsi
Program ini merupakan pengelolaan data **Manga** menggunakan konsep OOP di Java. Program sudah ditambahkan penerapan **Abstraction** dan **Polymorphism** sesuai instruksi.

## Fitur Utama
- Menambahkan data manga (menggunakan Overloading method).
- Menampilkan daftar manga.
- Implementasi abstract class dan interface.
- Demonstrasi Polymorphism (Overloading & Overriding).

## Abstraction
1. **Abstract Class**: `Genre`
   - Memiliki method abstract `deskripsiGenre()` yang dioverride pada `Shonen` dan `Seinen`.
2. **Interface**: `Publishable`
   - Digunakan pada class `Manga` dengan method `publishInfo()`.

## Polymorphism
1. **Overriding**:
   - Class `Shonen` dan `Seinen` meng-override method `deskripsiGenre()` dari abstract class `Genre`.
2. **Overloading**:
   - Class `MangaManager` memiliki dua method `tambahManga()`:
     - `tambahManga(Manga manga)`
     - `tambahManga(String judul, String author, String genre, int tahun)`

## Cara Menjalankan
1. Compile semua file `.java`:
   ```bash
   javac *.java
   ```
2. Jalankan program:
   ```bash
   java MainManga
   ```

## Output Program (contoh)
```
Shonen: Manga yang ditujukan untuk pembaca muda laki-laki, penuh aksi dan petualangan.
Seinen: Manga dengan cerita lebih serius, biasanya untuk pembaca dewasa.

Daftar Manga:
Manga: Naruto | Author: Masashi Kishimoto | Genre: Shonen | Tahun: 1999
Manga: Berserk | Author: Kentaro Miura | Genre: Seinen | Tahun: 1989
```

## Catatan
- Program ini menerapkan kombinasi **abstract class** dan **interface** sehingga mendemonstrasikan konsep **Abstraction** lebih jelas.
- Polymorphism ditunjukkan melalui **Overriding** dan **Overloading** dalam program.
