PERTANYAAN :
jelaskan tentang tentang three way handshaking

**Three-Way Handshaking (Pengawakan Tiga Langkah):**

   Three-way handshaking adalah proses awal saat dua komputer ingin menjalin koneksi melalui TCP. Ini seperti berbicara satu sama lain sebelum memulai pertukaran data. Prosesnya terdiri dari tiga langkah, yang akan saya jelaskan dengan contoh:

   - **Langkah 1 (Permintaan Koneksi)**: Komputer A ingin berbicara dengan Komputer B, jadi A mengirimkan pesan ke B yang berisi permintaan untuk memulai koneksi. Misalnya, A mengatakan, "Halo, saya ingin berbicara denganmu."

   - **Langkah 2 (Persetujuan Koneksi)**: Jika Komputer B siap untuk berbicara dengan A, ia akan merespons permintaan tersebut dengan pesan persetujuan. Misalnya, B berkata, "Tentu, saya siap berbicara denganmu. Saya mendengarmu."

   - **Langkah 3 (Konfirmasi Koneksi)**: Sekarang, Komputer A harus memberi tahu Komputer B bahwa ia sudah mendengar persetujuan tersebut dan koneksi siap digunakan. Misalnya, A mengirim pesan kembali kepada B, "Saya juga mendengarmu dengan baik. Mari kita mulai berbicara."

   Setelah tiga langkah ini selesai, koneksi TCP antara dua komputer sudah dibuat dan mereka dapat mulai mengirim data dengan keyakinan bahwa koneksi ini berfungsi dengan baik.

Dengan three-way handshaking, koneksi TCP menjadi stabil dan dapat diawasi. Ini memastikan bahwa data yang dikirimkan akan sampai ke tujuan dengan benar dan tidak akan hilang di tengah jalan.