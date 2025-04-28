Aji Nur Fahrurrahman 
122203004
Teknik Informatika
Pemograman mobile dan web
UTS

Informasi Penggunaan
1. Siapkan Android Studio
Pastikan kamu sudah install Android Studio (versi terbaru lebih baik).
Buka Android Studio dan pilih New Project → Pilih template Empty Activity → Klik Next.
Isi nama project (contoh: QRCodeApp), pilih bahasa Kotlin (atau Java jika mau), lalu Finish.

2. Tambahkan Dependency Library QR Code
Untuk membuat QR Code, kita pakai library ZXing.
Buka build.gradle (Module: app)
Tambahkan ini di bagian dependencies: 
//implementation 'com.journeyapps:zxing-android-embedded:4.3.0'
Setelah itu, klik Sync Now supaya library terpasang.

3. Desain Layout (XML)
Buka res/layout/activity_main.xml

4. Coding di MainActivity
Buka file MainActivity.kt

5. Jalankan ke HP atau Emulator
Hubungkan HP ke laptop/PC dan aktifkan USB Debugging, atau pakai Emulator Android Studio.
Klik tombol Run (Shift + F10) di Android Studio.
Pilih device → Tunggu aplikasi di-install dan dibuka.

6. Hasil Akhir
Aplikasi tampil di HP.
Masukkan teks di kolom input → Klik Generate QR Code → QR Code akan muncul di bawahnya!


Uji Coba dengan QR di bawah ini

![alt text](https://github.com/flyclaws/UTSmobileQrCode/blob/main/image/Email.png?raw=true)
Ini adalah Qr Code untuk Email
![alt text](https://github.com/flyclaws/UTSmobileQrCode/blob/main/image/Maps.png?raw=true)
Ini adalah Qr Code untuk Maps
![alt text](https://github.com/flyclaws/UTSmobileQrCode/blob/main/image/URL.png?raw=true)
Ini adalah Qr Code untuk URL
![alt text](https://github.com/flyclaws/UTSmobileQrCode/blob/main/image/phone.png?raw=true)
Ini adalah Qr Code untuk Phone
