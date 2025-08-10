# Nmap Report Tool

Program Python untuk melakukan scanning jaringan menggunakan Nmap dengan berbagai opsi scan lengkap, serta menyimpan hasil scan dalam format DOCX dan PDF secara otomatis.

## Fitur

- Scan jaringan dengan 25 opsi scan Nmap yang bisa dipilih sesuai kebutuhan
- Penjelasan lengkap tentang opsi-opsi scan Nmap
- Menyimpan hasil scan otomatis ke dalam folder `reports` dengan format `.docx` dan `.pdf`
- Tampilan menarik dengan logo dan warna menggunakan `colorama` dan `pyfiglet`

## Cara Install

1. Pastikan Python sudah terpasang di sistem Anda.
2. Install dependencies yang dibutuhkan dengan menjalankan perintah `pip install -r requirements.txt`.
3. Jalankan program dengan perintah `python3 main.py`.

## Cara Menggunakan

- Pilih menu input target untuk memasukkan IP, hostname, atau domain yang ingin discan.
- Pilih menu penjelasan fitur untuk membaca info tentang opsi-opsi scan.
- Pilih menu jenis scan untuk memilih metode scan Nmap yang diinginkan.
- Jalankan scan untuk mulai memindai target dan membuat laporan hasil scan.
- Laporan hasil scan akan otomatis tersimpan di folder `reports` dalam format `.docx` dan `.pdf`.

## Catatan

- Pastikan menggunakan tool ini sesuai dengan izin hukum yang berlaku.
- Hapus protokol `http://` atau `https://` pada input target, hanya masukkan domain atau IP saja.
- Beberapa opsi scan seperti deteksi OS (`-O`) membutuhkan hak akses root/sudo agar dapat berjalan.

Terima kasih telah menggunakan Nmap Report Tool!
