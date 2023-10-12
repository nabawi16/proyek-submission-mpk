# Proyek Submission MPK

**Aturan mengerjakan submission**<br>
Agar tugas submission dapat diperiksa dan diterima dengan baik, sebaiknya hindari beberapa hal berikut:

- Mengubah kode yang berada di dalam fungsi main()
- Mengubah (kecuali untuk mengerjakan TODO) atau menghapus kode yang sudah ada
- Membuat fungsi baru yang bukan merupakan tugas latihan
- Mengubah struktur project (menghapus, mengubah, atau memindahkan package)

# README Latihan 1

Latihan 1 ini bertujuan untuk mempraktikkan kemampuan pemrograman Kotlin Anda dengan fokus pada tiga tugas utama. Tugas-tugas ini berkaitan dengan penggunaan fungsi-fungsi dalam bahasa Kotlin untuk mengecek angka genap, mengecek apakah angka lebih dari 5, dan menghitung hasil sesuai rumus yang diberikan.

## Tugas

### TODO 1: Mengecek Angka Genap

Pada tugas ini, Anda diminta untuk mengimplementasikan fungsi `isEvenNumber(number: Int)` agar dapat mengecek apakah parameter `number` merupakan angka genap. Untuk menyelesaikan tugas ini, Anda dapat menggunakan operasi modulo (%) untuk memeriksa sisa pembagian.

### TODO 2: Mengecek Angka Lebih dari 5

Tugas ini mengharuskan Anda untuk mengisi kode pada fungsi `moreThanFive(number: Int)`. Anda perlu memastikan bahwa fungsi tersebut dapat menentukan apakah parameter `number` lebih dari 5 atau tidak.

### TODO 3: Menghitung Hasil

Pada tugas terakhir, Anda akan mengimplementasikan fungsi `result(number: Int)` agar menghasilkan nilai akhir sesuai rumus yang diberikan: `param * (param + 10)`.

## Penggunaan Kode

Kode utama terletak dalam fungsi `main()`. Anda akan melihat bahwa dalam fungsi `main()`, kita membuat kumpulan angka dari 1 hingga 100 menggunakan `1.rangeTo(100)`. Kemudian, kita melakukan perulangan for untuk setiap angka dalam kumpulan tersebut.

- Jika angka merupakan angka genap (sehingga sesuai dengan TODO 1), kita akan melewatkannya dengan pernyataan `continue`.

- Jika angka lebih dari 5 (sehingga sesuai dengan TODO 2), perulangan akan dihentikan dengan pernyataan `break`.

- Untuk angka yang tidak masuk dalam kedua kriteria di atas, kita akan menghitung hasil sesuai rumus dari TODO 3 dan mencetak hasilnya ke layar.

