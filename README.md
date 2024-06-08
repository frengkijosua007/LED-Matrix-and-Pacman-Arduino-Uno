Step 1: Pasang Kabel Jumper
•	VCC kita kasih kabel merah. GND kita kasih hitam. SDA kita kasih kabel kuning. SCL kita kasih kabel hijau

Step 2: GND Modul >> GND Arduino
•	Kita pasangkan GND Modul >> GND Arduino

Step 3: VCC Modul >> 5V Arduino
•	Kita pasangkan VCC Modul >> 5V Arduino

Step 4: SDA Modul >> A4 Arduino
•	Kita masukkan kabe SDA pin Modul >> A4 Arduino

SCL Modul >> A5 Arduino
•	Kita pasangkan SCL Modul >> A5 Arduino
•	Masukkan kabel jumper ke LED Matrix MAX 7210 secara berurut. Kemudian masukkan kabel MALE secara berurut. Tujuannya dilakukan secara berurut agar lebih mudah.

Step 5: VCC LED >> 5V Arduino di Project Based
•	Kabel hitam kita hubungkan ke depan kabel warna merah.

Step 6: GND LED >> GND Arduino
•	Kabel putih kita hubungkan ke GND

Step 7: DIN LED >> PIN 11 Arduino
•	Kaki DIN kita pasang ke PIN nomor 11 Arduino 

Step 8: CS LED >> PIN 10 Arduino
•	Kaki CS kita masukkan ke PIN nomor 10 Arduino

Step 9: CLK LED >> PIN 13 Arduino
•	Dan yang terakhir kaki CLK kita masukkan ke PIN 13 Arduino

Step 10: Kabel USB >> Laptop
•	Kita hunungkan kabel USB Printer ke Laptop


Uploading…
•	Maka disini akan muncul tulisan dari jam yang akan kita buat. Jadi disini tanggal pertama kali muncul dan tahunnya. Lalu ada jam beserta detiknya. Lalu temperatur karena midul RPC kita ini dilengkapi dengan sensor temperatur ruangan.

Jika mengganti WAIT = 80
•	Oke jadi pergerakan dari LED Matrixnya akan menjadi lebih lambat ya 

Jika mengganti WAIT = 30
•	Nah jadinya tadi kita liat sama sama jadinya lebih cepat

Hasil Merubah tanggal dan tahun
•	Jadi udah sukses untuk diatur. Jadi gampang. Nah ini kalau misalkan kita reset atau powernya mati ini udah otomatis akan update sendiri.

PACMAN
•	Kode sumber yang disediakan adalah bagian dari proyek Animasi PACMAN, kemungkinan melibatkan tampilan LED yang dikendalikan oleh chip driver MAX7219 atau MAX7221. Pernyataan #define menetapkan konstanta untuk konfigurasi, di mana MAX_DEVICES diatur ke 4, yang menunjukkan jumlah modul tampilan LED yang terhubung. Selain itu, penetapan pin ditentukan menggunakan CLK_PIN untuk clock, DATA_PIN untuk data, dan CS_PIN untuk pemilihan chip. Penugasan ini menentukan pin pada papan Arduino yang akan digunakan untuk komunikasi dengan chip driver MAX7219 atau MAX7221, memungkinkan animasi dan kontrol tampilan LED untuk menciptakan efek visual bertema PACMAN. Animasi dan logika tampilan yang sebenarnya akan diimplementasikan di bagian kode berikutnya, memanfaatkan parameter konfigurasi ini untuk komunikasi yang tepat dengan modul tampilan LED.
