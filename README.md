# pyhton.py5

# Tugas praktikum 5

# nama : yarni gea

# Nim : 312410413

# kelas : TI.24.A3



# Dari  Pratikum 5

# input

![image](https://github.com/user-attachments/assets/639d7f1b-d720-4a76-ab98-7550f62d4655)

# output 

![image](https://github.com/user-attachments/assets/29e4b668-7b41-42d8-a0aa-86e967c25d7f)

# flow chart 

![image](https://github.com/user-attachments/assets/9aea3db3-070d-4409-9c31-9941e753805a)

# 1. fungai

# Htung_nilai_akhir

# (tugas,uts,uas)

pyhton def hitung_nilai_akhir(tugas,uts,uas):

return (tugas*0.30)+(uts*0.35)+(uas*0.35)

 Fungsi ini menerima 3 parameter: nilai tugas, UTS, dan UAS
 
Menghitung nilai akhir dengan bobot:

Tugas: 30% (0.30)

UTS: 35% (0.35)

UAS: 35% (0.35)

Mengembalikan hasil perhitungan nilai akhir

# fungsi 

# tampilkan_daftar(daftar_mahasiswa):

python def tampilkan_daftar(daftar_mahasiswa): print("=" * 70) # Membuat garis pembatas print("| No | Nama | NIM | Tugas | UTS | UAS | Akhir |") print("=" * 70) # Membuat garis pembatas


Menerima parameter berupa list yang berisi data mahasiswa

Membuat tampilan tabel dengan header

Menggunakan perulangan untuk menampilkan setiap data mahasiswa

Format output menggunakan string formatting untuk merapikan tampilan

enumerate(daftar_mahasiswa, 1) digunakan untuk membuat penomoran mulai dari 1

# fungsi main():

python def main(): daftar_mahasiswa = [] # Inisialisasi list kosong

Fungsi utama program

Membuat list kosong untuk menyimpan data mahasiswa

# input data dan validasi

python while True: print("\nMasukkan data mahasiswa") nama = input("Nama : ") nim = input("NIM : ")

         while true :

              try: 

                  tugas = float(input("nilai tugas : ")

                  if 0 <= tugas <= 100: 

                        break 

                        print(" nilai harus antara 0-100!")

                        expect vallueeror:

                               print("masukkannilai yang valid!")

Menggunakan nested while loop untuk input dan validasi

Try-except untuk menangani input nilai yang tidak valid

Validasi rentang nilai (0-100)

Proses yang sama dilakukan untuk nilai UTS dan UAS

# simpan data :

python

# hitung nilai akhir:

nilai_akhir = hitung_nilai_akhir(tugas,uts,uas)

# tambahkan kedaftar:

mahasiswa = { 'nama': nama, 'nim': nim, 'tugas': tugas, 'uts': uts, 'uas': uas, 'nilai_akhir': nilai_akhir } daftar_mahasiswa.append(mahasiswa)

Memanggil fungsi hitung_nilai_akhir

Membuat dictionary untuk menyimpan data satu mahasiswa

Menambahkan dictionary ke dalam list daftar_mahasiswa

# konfirmasi tambah data :

python tambah = input("\nTambah data (y/t)? ") if tambah.lower() != 'y': break

Meminta konfirmasi untuk menambah data lagi

Jika input bukan 'y', keluar dari loop

# menampilkan hasil:

python print("\nDaftar Nilai Mahasiswa:") tampilkan_daftar(daftar_mahasiswa)

Memanggil fungsi tampilkan_daftar untuk menampilkan semua data

# program titik masuk:

python if name == "main": main()

Memastikan fungsi main() hanya dijalankan jika file dijalankan langsung

Tidak akan dijalankan jika file di-import sebagai modul

Fitur-fitur Program:

Dapat menambahkan data mahasiswa secara dinamis

Validasi input untuk nilai (harus numerik dan 0-100)

Perhitungan nilai akhir otomatis dengan bobot yang ditentukan

Tampilan output dalam bentuk tabel yang rapi

Penanganan error untuk input yang tidak valid

Konfirmasi untuk menambah data baru

Program ini dibuat untuk memudahkan pengelolaan data nilai mahasiswa dengan interface yang user-friendly dan penanganan error yang baik.







