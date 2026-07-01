# Praktikum OOP — Array, Method, dan Pengulangan

Kumpulan program praktikum sesuai materi "Array, Method, dan Pengulangan" (Semester 2, ILKOM).

## Daftar Program

| No | File | Materi |
|----|------|--------|
| 1 | `Larik1.java` | Array 1 dimensi + input Scanner |
| 2 | `ArrayDimensiDua.java` | Array 2 dimensi (matriks piksel) |
| 3 | `ContohString.java` | Kelas String & konstruktornya |
| 4 | `Fungsi2.java` | Method tanpa parameter |
| 5 | `FungsiParameter.java` | Method dengan parameter & return value |
| 6 | `UlangWhile1.java` | Pengulangan `while` |
| 7 | `UlangDo2.java` | Pengulangan `do...while` (konversi Celcius → Fahrenheit) |
| 8 | `UlangFor.java` | Pengulangan `for` |
| 9 | `Factorial.java` | Rekursi (faktorial) |
| 10 | `matrik/Main.java` | Program gabungan: array + method + pengulangan |

## Cara Menjalankan

Pastikan JDK (bukan hanya JRE) sudah terpasang di komputer kamu, lalu jalankan dari folder `src`:

```bash
# Compile satu file, contoh:
javac Larik1.java
java Larik1

# Untuk program dalam package matrik:
javac matrik/Main.java
java matrik.Main
```

Atau, import folder `src` ini sebagai project baru di Eclipse / IntelliJ / VS Code (dengan Java Extension Pack).

## Catatan

- Program nomor 1, 6, 7, 10 membutuhkan input dari keyboard (`Scanner`) — jalankan lewat terminal, bukan hanya klik run tanpa console.
- Program nomor 10 (`matrik/Main.java`) meminta input panjang, lebar, dan tinggi, lalu menghitung luas & volume sekaligus mempraktikkan array, method, dan `while` dalam satu program.
