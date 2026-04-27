# WebSocket: Implementasi Komunikasi Real-Time (Echo Server)

Proyek ini merupakan bagian dari tugas UTS Pemrograman Web yang mendemonstrasikan penggunaan protokol **WebSocket** untuk menciptakan komunikasi dua arah (*full-duplex*) yang cepat dan efisien antara browser dan server.

## Ringkasan Proyek
Berbeda dengan HTTP konvensional yang bersifat searah, proyek ini membuktikan bahwa WebSocket dapat menjaga koneksi tetap terbuka (persisten), sehingga server dapat mengirimkan data secara langsung tanpa menunggu permintaan dari klien. Dalam eksperimen ini, saya membangun sebuah **Echo Server** sederhana.

## Teknologi yang Digunakan
- **Node.js**: Sebagai lingkungan runtime server.
- **Library `ws`**: Library WebSocket untuk Node.js.
- **HTML5 & Vanilla JavaScript**: Sebagai antarmuka klien (frontend).


## Struktur File
- `server.js` - Logika backend yang menangani koneksi WebSocket dan pesan masuk.
- `index.html` - Antarmuka pengguna untuk mengirim pesan dan melihat respons real-time.


## Cara Menjalankan Proyek
1. **Prasyarat**: Pastikan [Node.js](https://nodejs.org/) sudah terinstal di komputer Anda.
2. **Instalasi**: Masuk ke folder proyek melalui terminal dan jalankan:
   ```bash
   npm install ws
## Menjalankan Server:

Bash
node server.js
Menjalankan Klien: Buka file index.html menggunakan browser (disarankan menggunakan Live Server di VS Code).

## screenshot program
<img width="1919" height="1003" alt="image" src="https://github.com/user-attachments/assets/7b7eebb8-2d5d-4e63-af03-ef85536efa89" />

<img width="959" height="499" alt="Hasil di crome" src="https://github.com/user-attachments/assets/a90ff2f2-63d5-46ff-87ff-9177575ddc83" />

<img width="1390" height="445" alt="image" src="https://github.com/user-attachments/assets/c7df1b88-4891-4f44-8762-31927dcad2ab" />

Referensi
Fette, I. & Melnikov, A. (2011). RFC 6455: The WebSocket Protocol.
MDN Web Docs. (2025). WebSocket API.

Terima Kasih.

