# Nmap Report Tool
---

**Nmap Report Tool** adalah aplikasi Python berbasis terminal untuk melakukan scanning jaringan menggunakan Nmap dengan berbagai opsi lengkap. Program ini memudahkan pengguna dalam melakukan pemindaian port, layanan, OS, dan fitur lainnya, sekaligus otomatis membuat laporan hasil scan dalam format DOCX dan PDF.

---

## Fitur Utama

- Pilihan hingga 25 jenis scan Nmap yang umum digunakan  
- Penjelasan lengkap tiap opsi scan agar pengguna memahami fungsinya  
- Simpan hasil scan otomatis dalam format dokumen (.docx) dan PDF  
- Tampilan antarmuka warna-warni dan logo ASCII art yang menarik  
- Folder laporan otomatis dibuat bernama `reports`

---

## Persiapan & Instalasi

1. Pastikan Python 3 sudah terpasang di sistem Anda.  
2. Install dependencies dengan menjalankan:  
   `pip install -r requirements.txt`  
3. Jalankan program dengan:  
   `python3 main.py`

---

## Cara Penggunaan

1. **Input target**: Masukkan IP address, hostname, atau domain tanpa protokol (`http://` atau `https://`).  
2. **Lihat penjelasan fitur**: Membaca detail fungsi dan opsi scan yang tersedia.  
3. **Pilih jenis scan**: Pilih opsi scan sesuai kebutuhan (misalnya Quick Scan, OS Detection, UDP Scan, dll).  
4. **Jalankan scan**: Mulai pemindaian dan otomatis simpan laporan di folder `reports`.  
5. **Keluar**: Tutup aplikasi.

---

## Penting Diketahui

- Beberapa scan seperti OS detection (`-O`) memerlukan hak akses root/sudo.  
- Gunakan tool ini hanya pada jaringan dan sistem yang Anda miliki izin untuk memindai.  
- Laporan hasil scan tersimpan dengan nama file yang aman (karakter non-alfanumerik diubah).  
- Folder `reports` akan otomatis dibuat jika belum ada.

---

## Lisensi

Program ini disediakan "as-is" tanpa jaminan apapun. Gunakan dengan bijak dan bertanggung jawab.

---

Terima kasih telah menggunakan **Nmap Report Tool**! Jika ada masukan atau masalah, silakan hubungi pembuat.
