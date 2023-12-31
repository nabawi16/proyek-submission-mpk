# Proyek Submission MPK

**Mengerjakan submission**<br>
Latihan ini bertujuan untuk mempraktikkan beberapa aspek dasar dalam pengembangan perangkat lunak. Pada latihan ini, saya akan melakukan beberapa tugas berikut:

1. **Mengubah kode yang berada di dalam fungsi main():** Anda diharapkan untuk mengedit dan memodifikasi kode yang ada dalam fungsi `main()` sesuai dengan instruksi yang diberikan dalam latihan ini.

2. **Mengubah atau menghapus kode yang sudah ada secara default:** Anda perlu memeriksa kode yang sudah ada secara default dalam proyek dan melakukan perubahan atau penghapusan sesuai kebutuhan latihan.

3. **Membuat fungsi baru yang bukan merupakan tugas latihan:** Selain mengubah kode yang sudah ada, Anda diminta untuk membuat fungsi baru yang tidak ada dalam tugas latihan. Ini akan membantu Anda mempraktikkan kemampuan penambahan fitur baru ke dalam proyek.

4. **Mengubah struktur project (menghapus, mengedit, dan memindahkan package):** Anda akan belajar tentang pengelolaan struktur proyek dengan mengedit, menghapus, atau memindahkan paket-paket yang ada dalam proyek. Pastikan untuk menjelaskan langkah-langkah yang Anda ambil dalam file ini.

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

# README Latihan 2

Latihan 2 ini dirancang untuk mengasah kemampuan Anda dalam mengubah fungsi-fungsi dan melakukan perhitungan serta manipulasi data. Pada latihan ini, Anda akan fokus pada dua tugas yang memerlukan penyesuaian kode.

## Tugas

### TODO 1: Perhitungan dengan Penanganan Nilai Default

Pada tugas ini, Anda diminta untuk mengimplementasikan fungsi `calculate(valueA: Int, valueB: Int, valueC: Int?): Int` sehingga dapat mengembalikan nilai dengan menggunakan rumus berikut: `valueA + (valueB - valueC)`. Namun, ada penanganan khusus saat `valueC` bernilai `null`. Anda harus mengatur nilai default 50 sebagai gantinya. Ini akan memungkinkan Anda mengatasi nilai `null` dan menghasilkan perhitungan yang benar.

### TODO 2: Membuat String Hasil

Tugas kedua meminta Anda untuk mengisi kode pada fungsi `result(result: Int)` agar dapat menghasilkan teks yang sesuai dengan format yang diberikan: "Result is ${result}". Anda akan menggunakan nilai yang dihitung dari tugas pertama sebagai parameter.

## Penggunaan Kode

Kode utama terletak dalam fungsi `main()`. Anda akan melihat bahwa dalam fungsi `main()`, kita memiliki tiga variabel `valueA`, `valueB`, dan `valueC` dengan nilai-nilai tertentu.

- Kita menggunakan fungsi `calculate()` dua kali: sekali dengan `valueC` yang memiliki nilai, dan sekali lagi dengan `valueC` yang bernilai `null`.

- Hasil perhitungan dari kedua panggilan fungsi `calculate()` disimpan dalam variabel `resultA` dan `resultB`.

- Kemudian, kita menggunakan fungsi `result()` untuk menghasilkan string dengan nilai hasil dari perhitungan.

- Akhirnya, kita mencetak string-string hasil ke layar.

# README Latihan 3

Latihan 3 ini dirancang untuk melatih Anda dalam menggunakan jenis data generik (generic types) dalam bahasa Kotlin. Pada latihan ini, Anda diminta untuk melengkapi sebuah fungsi yang akan mengidentifikasi tipe data dari parameter yang diberikan dan mengembalikan pesan sesuai dengan tipe data tersebut.

## Tugas

### TODO: Mengidentifikasi Tipe Data

Pada tugas ini, Anda diminta untuk melengkapi kode dalam fungsi `checkType(args: T): String`. Fungsi ini akan menerima parameter dengan tipe data generik `T` dan akan mengembalikan pesan yang sesuai dengan tipe data parameter tersebut. Beberapa tipe data yang perlu Anda identifikasi dan tangani adalah:

- Integer
- String
- Boolean
- Double
- List<String>
- Map<String, String>

Anda perlu menggunakan konstruksi `when` untuk mengidentifikasi tipe data parameter dan mengembalikan pesan yang sesuai. Jika tipe data tidak sesuai dengan daftar yang diberikan, kembalikan pesan "Unknown Type".

## Penggunaan Kode

Kode utama terletak dalam fungsi `main()`. Anda akan melihat bahwa dalam fungsi `main()`, kita memiliki beberapa contoh penggunaan fungsi `checkType()` yang memeriksa berbagai tipe data.

- Kita memanggil `checkType()` dengan berbagai nilai, termasuk daftar, string, boolean, dan double. Hasil dari pemanggilan ini akan dicetak ke layar.


# README Latihan 4

Latihan 4 ini fokus pada penggunaan koleksi tipe `Map` dalam bahasa Kotlin. Anda akan belajar cara membuat dan menginisialisasi `Map` dengan menggunakan pasangan kunci-nilai (key-value pair). Tugas dalam latihan ini adalah melengkapi inisialisasi `Map` dengan pasangan kunci-nilai yang telah disediakan.

## Tugas

### TODO: Inisialisasi Map dengan Pasangan Kunci-Nilai

Pada tugas ini, Anda diminta untuk melengkapi kode dalam fungsi `vehicle()` yang mengembalikan tipe data `Map<String, String>`. Anda perlu menginisialisasi `Map` dengan pasangan kunci-nilai berikut:

- Kunci: type, Nilai: motorcycle
- Kunci: maxSpeed, Nilai: 230Km/s
- Kunci: maxTank, Nilai: 100Ltr

Anda harus mengikuti sintaksis yang benar untuk menginisialisasi `Map` dengan pasangan kunci-nilai yang sesuai.

## Penggunaan Kode

Kode utama terletak dalam fungsi `main()`. Anda akan melihat bahwa dalam fungsi `main()`, kita mencetak hasil dari fungsi `vehicle()` ke layar. Hasilnya akan berupa `Map` yang mengandung tiga pasangan kunci-nilai sesuai dengan instruksi yang telah Anda lengkapi.


# README Latihan 5

Latihan 5 ini berkaitan dengan penggunaan suspending functions (fungsi penangguhan) dan konsep asynchronous programming dalam Kotlin. Anda akan mengubah dua fungsi agar menjadi suspending functions dengan menggunakan operator `suspend`, dan Anda akan menambahkan operasi penangguhan dengan `delay`. Selain itu, Anda akan menggunakan `async` dan `await` untuk menjalankan fungsi-fungsi tersebut secara asynchronous.

## Tugas

### TODO 1: Mengubah Fungsi sum()

Pada tugas ini, Anda diminta untuk mengubah fungsi `sum(valueA: Int, valueB: Int)` agar memenuhi kriteria berikut:

- Mengubahnya menjadi suspending function dengan menambahkan operator `suspend`.
- Menambahkan penangguhan (delay) selama 3 detik.
- Mengembalikan nilai hasil perhitungan dengan rumus `valueA + valueB`.

### TODO 2: Mengubah Fungsi multiple()

Tugas kedua meminta Anda untuk mengubah fungsi `multiple(valueA: Int, valueB: Int)` agar memenuhi kriteria berikut:

- Mengubahnya menjadi suspending function dengan menambahkan operator `suspend`.
- Menambahkan penangguhan (delay) selama 2 detik.
- Mengembalikan nilai hasil perhitungan dengan rumus `valueA * valueB`.

## Penggunaan Kode

Kode utama terletak dalam fungsi `main()`. Anda akan melihat bahwa dalam fungsi `main()`, kita menggunakan `runBlocking` untuk menjalankan operasi asynchronous.

- Kami menjalankan dua fungsi (`sum` dan `multiple`) secara asynchronous menggunakan `async`, dan menyimpan hasilnya dalam variabel `resultSum` dan `resultMultiple`.
- Kemudian, kami menggunakan `await` untuk menunggu hasil dari kedua fungsi tersebut.
- Hasil dari perhitungan masing-masing fungsi dicetak ke layar.
