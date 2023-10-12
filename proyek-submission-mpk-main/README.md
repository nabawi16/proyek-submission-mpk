# Proyek Submission MPK 

**Aturan mengerjakan submission**<br>
Agar tugas submission dapat diperiksa dan diterima dengan baik, sebaiknya hindari beberapa hal berikut:

- Mengubah kode yang berada di dalam fungsi main()
- Mengubah (kecuali untuk mengerjakan TODO) atau menghapus kode yang sudah ada
- Membuat fungsi baru yang bukan merupakan tugas latihan
- Mengubah struktur project (menghapus, mengubah, atau memindahkan package)

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


