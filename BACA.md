# Indikator TAC (Toleransi Rata-Rata Chandle)
=============================================

*Filosofi TAC:*
TAC (Tolerance Average Chandle) adalah indikator untuk platform TradingView yang digunakan untuk menghitung selisih antara harga penutupan dan Exponential Moving Average (EMA) untuk setiap candle selama periode waktu tertentu. Indikator ini membantu trader dalam mengidentifikasi perubahan tren harga berdasarkan perbedaan antara harga penutupan dan EMA.

*Keterangan:*
Repositori ini berisi kode sumber untuk indikator TAC (Average Chandle Tolerance) yang dikembangkan untuk platform TradingView. Indikator ini menampilkan nilai TAC sebagai garis pada grafik, dengan warna garis berubah sesuai dengan nilai TAC. Jika TAC positif, garis akan berwarna hijau, jika TAC negatif, garis akan berwarna merah, dan jika TAC nol, garis akan berwarna putih.

*Cara menggunakan TAC:*
Untuk menggunakan indikator TAC, Anda dapat mengikuti langkah-langkah berikut:

Salin seluruh kode di file "tac_indicator.pine".
Buka platform TradingView dan buka bagian "Pine Editor".
Rekatkan kode TAC di Editor Pine dan simpan skrip dengan nama yang diinginkan.
Tambahkan indikator TAC ke grafik dengan mengklik tombol "Indikator" dan cari nama indikator yang Anda simpan.
Tetapkan periode EMA sesuai dengan preferensi Anda menggunakan input yang disediakan.
Indikator TAC akan muncul di grafik dan menampilkan garis berwarna yang menunjukkan nilai TAC di setiap chandle.

*Deskripsi Kode:*
- `ema(close, period)`: Fungsi ini menghitung Exponential Moving Average (EMA) dari harga penutupan. EMA dihitung menggunakan rumus eksponensial untuk memberi bobot lebih pada data harga terkini.
- `spread(close, emaValue)`: Fungsi ini menghitung selisih antara harga penutupan dan EMA.
- `getTACValue(close, emaValue)`: Fungsi ini menghitung nilai TAC (perbedaan antara harga penutupan dan EMA) berdasarkan posisi harga penutupan relatif terhadap EMA. Jika harga penutupan di atas EMA, maka nilai TAC akan positif, dan jika harga penutupan di bawah EMA, maka nilai TAC akan negatif. Jika harga penutupan sama dengan EMA, TAC akan menjadi nol.
- `emaPeriods`: Variabel ini adalah input dari pengguna untuk menentukan periode EMA yang diinginkan.

*Lisensi:*
Indikator ini disediakan di bawah Mozilla Public License 2.0, yang berarti Anda dapat menggunakannya secara bebas dan bahkan memodifikasi kode sumbernya. Kami sangat menghargai kontribusi dan masukan dari pengguna untuk meningkatkan indikator ini.

*Nikmati Trading*
Selamat trading menggunakan indikator TAC! Semoga indikator ini membantu Anda dalam mengidentifikasi peluang perdagangan yang lebih baik. Jangan ragu untuk memberikan umpan balik atau pertanyaan di bagian "Masalah" jika Anda memiliki saran atau ingin berdiskusi lebih lanjut tentang indikator ini.

Terima kasih telah menggunakan indikator TAC dan semoga sukses dalam trading Anda!

Baca di [eng](https://github.com/affanyunas/tac-Indicator/blob/main/README.md)