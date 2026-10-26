# Pertemuan 12 - File I/O dan Error Handling

Nama: Mauliana Mutiara  
NIM: 2225250078  
Kelas: 3A

## Tujuan

Praktik ini bertujuan untuk mempelajari cara membaca,
menulis, mengolah, dan memvalidasi data file menggunakan Python.
Selain itu, praktik ini menggunakan try-except untuk menangani
error ketika file tidak ditemukan atau data tidak sesuai format.

## Format File Input

File nilai.txt menggunakan format:

NIM,nilai

Contoh:
A001,85
A002,78
A003,92

## Cara Menjalankan

Jalankan program dari terminal pada folder utama proyek.

python tugas/rekap_nilai_file.py

## Error yang Ditangani

- FileNotFoundError: ketika file input tidak ditemukan.
- ValueError: ketika nilai bukan angka atau format baris tidak sesuai.

## Test Case

1. Data normal: data valid berhasil direkap.
2. File hilang: program menampilkan pesan file tidak ditemukan.
3. Nilai invalid: baris yang tidak valid dilewati.
4. Baris kosong: baris kosong dilewati.
5. Batas lulus: nilai 60 dihitung lulus.

## Refleksi

Saya belajar bahwa data dapat disimpan dalam file agar tetap tersedia
setelah program selesai. Saya juga belajar menggunakan mode r, w,
dan a, serta try-except untuk menangani kesalahan saat membaca data.
Dengan validasi, data yang tidak sesuai format dapat dilewati tanpa
menghentikan seluruh proses rekap.