# Kriptografi-pada-Punk-Records-v1-Menggunakan-FastAPI-untuk-Keamanan-dan-Integritas-Data


Implementasi layanan kriptografi berbasis FastAPI pada sistem Punk Records-v1 untuk meningkatkan keamanan komunikasi dan integritas data melalui digital signature ECDSA, pertukaran kunci ECDH, enkripsi AES-GCM, secure session, dan relay pesan terenkripsi.


# Implementasi Layanan Kriptografi pada Punk Records-v1 Menggunakan FastAPI

## Deskripsi Proyek

Repository ini berisi implementasi layanan kriptografi yang terintegrasi dengan sistem Punk Records-v1 menggunakan FastAPI sebagai framework pengembangan API berbasis Python. Proyek ini bertujuan untuk meningkatkan keamanan komunikasi antarpengguna serta menjaga keaslian, integritas, dan kerahasiaan data yang dipertukarkan melalui layanan API.

Sistem ini menerapkan beberapa mekanisme kriptografi modern untuk mendukung proses autentikasi, pertukaran kunci, enkripsi pesan, dan verifikasi dokumen digital.

## Fitur Utama

- **Digital Signature ECDSA**  
  Digunakan untuk menandatangani dan memverifikasi pesan atau dokumen digital guna memeriksa keaslian sumber serta mendeteksi perubahan data setelah penandatanganan.

- **Hybrid Cryptography**  
  Mengombinasikan Elliptic Curve Diffie–Hellman (ECDH) untuk membangun rahasia bersama dalam proses pertukaran kunci dan AES-GCM untuk mengenkripsi serta memverifikasi integritas data.

- **Secure Session Management**  
  Mendukung pengelolaan sesi komunikasi agar pertukaran data dapat dilakukan melalui mekanisme sesi yang dirancang untuk menjaga keamanan komunikasi.

- **Public Key Management**  
  Menyediakan mekanisme penyimpanan dan pengelolaan public key yang diperlukan dalam proses verifikasi tanda tangan digital dan komunikasi kriptografi.

- **Encrypted Message Relay**  
  Mendukung penerusan pesan dalam bentuk terenkripsi sehingga isi pesan tidak perlu dikirimkan sebagai teks biasa melalui layanan relay.

- **PDF Digital Signing**  
  Mendukung proses penandatanganan dokumen PDF untuk membantu memverifikasi keaslian dan mendeteksi perubahan terhadap dokumen yang ditandatangani, sesuai dengan mekanisme implementasinya.


## Tujuan Proyek

Proyek ini dikembangkan untuk mempelajari dan menerapkan penggunaan kriptografi modern dalam pengembangan layanan API, khususnya untuk melindungi komunikasi digital dan menjaga integritas data. Implementasi ini juga menjadi referensi pembelajaran mengenai integrasi mekanisme kriptografi dengan aplikasi backend berbasis Python.

## Catatan

Fitur dan tingkat keamanan aktual bergantung pada detail implementasi, pengelolaan kunci, konfigurasi sesi, serta proses validasi yang diterapkan. Keberadaan algoritma kriptografi saja tidak otomatis menjamin keamanan keseluruhan sistem.
