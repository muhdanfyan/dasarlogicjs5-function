# Memahami Function dalam JavaScript

Dalam JavaScript, **function** adalah blok kode yang dirancang untuk menjalankan tugas tertentu. Function memungkinkan kita untuk menulis kode yang dapat digunakan kembali, menghemat waktu, dan membuat program lebih mudah dipahami.

---

## 🎓 Apa Itu Function? 

Function adalah seperti **resep masakan**. Ketika kita ingin membuat hidangan tertentu, kita mengikuti langkah-langkah yang sudah ada di resep tanpa perlu mengingat semuanya. Function bekerja dengan cara yang sama: setiap kali kita ingin melakukan sesuatu, kita cukup "memanggil" function yang sudah dibuat sebelumnya.

Contoh dalam JavaScript:
```javascript
function greeting(nama) {
    console.log("Halo, " + nama + "! Selamat datang!");
}
```
Di sini, function greeting berfungsi untuk menampilkan sapaan bagi siapa saja yang namanya kita masukkan.

🔹 Memanggil Function
Setiap kali kita ingin menyapa seseorang, kita tinggal memanggil greeting dan memasukkan nama sebagai parameter:

```javascript
greeting("Andi");  // Output: "Halo, Andi! Selamat datang!"
greeting("Budi");  // Output: "Halo, Budi! Selamat datang!"
```
Dengan cara ini, kita bisa menyapa siapa pun tanpa menulis ulang logika sapaan setiap kali.

🎯 Mengapa Function Penting?
Menghemat Waktu dan Kode: Dengan function, kita hanya perlu menulis satu blok kode untuk tugas yang sama, dan cukup memanggilnya berulang kali.

Mudah Dibaca dan Dikelola: Function membantu kita membuat kode lebih rapi dan terorganisir. Setiap function memiliki tugas spesifik yang membuat program lebih mudah dipahami.

🚀 Contoh Kasus Penggunaan Function
Berikut beberapa contoh function yang sering digunakan dalam kehidupan nyata:

1. Menghitung Luas atau Volume
Misalkan kita ingin menghitung luas persegi panjang. Dengan function hitungLuasPersegiPanjang, kita cukup memasukkan panjang dan lebar untuk mendapatkan hasilnya.

```javascript
function hitungLuasPersegiPanjang(panjang, lebar) {
    return panjang * lebar;
}
```
let luas = hitungLuasPersegiPanjang(5, 10); // Output: 50
2. Mengirim Pesan atau Notifikasi
Dalam aplikasi, kita sering perlu mengirim notifikasi atau pesan kepada pengguna. Function kirimNotifikasi dapat memastikan setiap pesan dikirim dengan cara yang konsisten.

```javascript
function kirimNotifikasi(pesan) {
    console.log("Notifikasi: " + pesan);
}
```
kirimNotifikasi("Selamat datang di aplikasi kami!");
kirimNotifikasi("Update terbaru telah tersedia.");
3. Validasi Data
Function validasiEmail dapat digunakan untuk memastikan email yang dimasukkan pengguna valid. Daripada menulis ulang logika pengecekan berkali-kali, kita cukup memanggil function ini setiap kali kita butuh validasi email.

```javascript
function validasiEmail(email) {
    return email.includes("@");
}
```
let isValid = validasiEmail("test@example.com"); // Output: true
let isInvalid = validasiEmail("testexample.com"); // Output: false
Dengan function, kita bisa membuat program lebih efisien, rapi, dan mudah diperbarui di masa mendatang. Function adalah salah satu konsep dasar yang sangat penting dalam pemrograman JavaScript dan akan membantu kita mengelola kode secara lebih baik.

📚 Latihan
Cobalah membuat function sendiri berdasarkan contoh di atas atau buatlah function baru yang bisa menyelesaikan tugas lain, seperti menghitung volume, konversi satuan, atau memberi diskon pada harga barang.

Semoga penjelasan ini membantu kamu memahami cara kerja function dan bagaimana menggunakannya dalam program JavaScript!

```
**README.md ini** menjelaskan konsep function dengan analogi 
sederhana, memberikan contoh kode yang mudah diikuti, dan menyoroti kegunaan function dalam aplikasi sehari-hari. Ini juga mencakup bagian latihan untuk mendorong peserta belajar dengan praktek.
```


#Tugas: Memahami Cara Kerja Function dalam JavaScript
Di bawah ini terdapat beberapa tugas yang dirancang untuk membantu kamu memahami cara kerja function di JavaScript. Ikuti instruksinya dengan seksama dan coba untuk menjalankan kode kamu!

📌 Tugas 1: Membuat Fungsi Penyapa
Buat sebuah fungsi bernama sapaUser yang menerima satu parameter, yaitu nama. Fungsi ini akan menampilkan pesan sapaan di console sesuai dengan nama yang diberikan.

Contoh:
```javascript
sapaUser("Andi"); // Output: "Halo, Andi! Selamat datang!"
sapaUser("Budi"); // Output: "Halo, Budi! Selamat datang!"
```
Instruksi:

Buat fungsi sapaUser dengan parameter nama.
Di dalam fungsi, tampilkan pesan sapaan menggunakan console.log.
📌 Tugas 2: Fungsi Penghitung Luas Persegi
Buat fungsi bernama hitungLuasPersegi yang menerima satu parameter, yaitu sisi. Fungsi ini akan mengembalikan hasil perkalian dari sisi * sisi untuk mendapatkan luas persegi.

Contoh:
```javascript
let luas = hitungLuasPersegi(5); // Output: 25
```
Instruksi:

Buat fungsi hitungLuasPersegi dengan parameter sisi.
Gunakan operator perkalian untuk menghitung luas, dan kembalikan hasilnya dengan return.
📌 Tugas 3: Fungsi Penjumlahan Dua Angka
Buat sebuah fungsi bernama tambah yang menerima dua parameter, yaitu angka1 dan angka2. Fungsi ini akan mengembalikan hasil penjumlahan dari kedua angka tersebut.

Contoh:
```javascript
let hasil = tambah(10, 5); // Output: 15
Instruksi:
```
Buat fungsi tambah dengan dua parameter: angka1 dan angka2.
Gunakan operator + untuk menjumlahkan kedua angka, dan kembalikan hasilnya.
📌 Tugas 4: Fungsi Pengecek Bilangan Ganjil atau Genap
Buat sebuah fungsi bernama cekGanjilGenap yang menerima satu parameter, yaitu angka. Fungsi ini akan menampilkan pesan apakah angka tersebut ganjil atau genap.

Contoh:
```javascript
cekGanjilGenap(7); // Output: "Angka 7 adalah ganjil"
cekGanjilGenap(4); // Output: "Angka 4 adalah genap"
Instruksi:
```
Buat fungsi cekGanjilGenap dengan parameter angka.
Gunakan if-else untuk memeriksa apakah angka tersebut ganjil atau genap.
Tampilkan pesan hasilnya menggunakan console.log.
📌 Tugas 5: Fungsi Penghitung Diskon
Buat fungsi bernama hitungDiskon yang menerima dua parameter, yaitu harga dan diskon. Fungsi ini akan mengembalikan harga setelah dikurangi diskon.

Contoh:
```javascript
let hargaSetelahDiskon = hitungDiskon(100000, 20); // Output: 80000
Instruksi:

Buat fungsi hitungDiskon dengan dua parameter: harga dan diskon (diskon dalam persen).
Hitung jumlah diskon dari harga awal, lalu kurangi dengan harga.
Kembalikan harga setelah diskon dengan return.
📌 Tugas 6: Fungsi Validasi Usia untuk Mengemudi
Buat fungsi bernama cekUsiaMengemudi yang menerima satu parameter usia. Fungsi ini akan menampilkan pesan apakah seseorang cukup umur untuk mengemudi atau belum. Misalnya, usia minimal untuk mengemudi adalah 17 tahun.

Contoh:
```javascript
cekUsiaMengemudi(16); // Output: "Maaf, kamu belum cukup umur untuk mengemudi."
cekUsiaMengemudi(18); // Output: "Selamat! Kamu boleh mengemudi."
```

Instruksi:

Buat fungsi cekUsiaMengemudi dengan parameter usia.
Gunakan if-else untuk memeriksa apakah usia mencukupi atau tidak.
Tampilkan pesan hasil menggunakan console.log.
🎉 Selamat Mencoba!
Kerjakan tugas-tugas di atas untuk memahami cara kerja function dengan lebih baik. Dengan latihan ini, kamu akan lebih memahami bagaimana function dapat menerima parameter, melakukan proses, dan mengembalikan nilai atau pesan tertentu. Semangat! 🚀

```

---

Setiap tugas disusun untuk memberikan pemahaman dasar yang solid tentang cara kerja fungsi, parameter, return value, dan kontrol alur dasar di JavaScript.
```