# labpy.8
# NAMA  = DZAKI ARIF RAHMAN
# NIM   = 312410312
# KELAS = TI.24.A4

![WhatsApp Image 2024-12-08 at 18 33 52](https://github.com/user-attachments/assets/459aafe8-8048-4826-ac65-9370b4c8afc8)

Program Pengelolaan Data Mahasiswa

Program ini adalah implementasi sederhana untuk mengelola data nilai mahasiswa menggunakan Python. 
Program ini memanfaatkan **Object-Oriented Programming (OOP)** dengan class `Mahasiswa`. 

## screenshout kode vsc

![Lappy__8](https://github.com/user-attachments/assets/7dc5aefb-f006-44ea-8e03-7c99374425f8)

## Fitur Program

1. **Menambahkan Data**  
   Menambahkan data mahasiswa ke dalam sistem dengan format `nama` dan `nilai`.

2. **Menampilkan Data**  
   Menampilkan semua data mahasiswa yang tersimpan.

3. **Menghapus Data**  
   Menghapus data mahasiswa berdasarkan nama.

4. **Mengubah Data**  
   Mengubah nilai mahasiswa berdasarkan nama.

## penjelasannya

### **Kelas Mahasiswa**

#### **Atribut**
- `self.data`  
  Atribut ini adalah sebuah dictionary (`dict`) yang digunakan untuk menyimpan data mahasiswa dalam format pasangan `nama: nilai`.  

#### **Metode**
1. **`__init__(self)`**  
   Konstruktor untuk menginisialisasi atribut `data` sebagai dictionary kosong.

2. **`tambah(self, nama, nilai)`**  
   Menambahkan data mahasiswa ke dalam atribut `data`.  
   - **Parameter:**  
     - `nama` (str): Nama mahasiswa.
     - `nilai` (int): Nilai mahasiswa.  
   - **Contoh:**  
     ```python
     mahasiswa.tambah("Dzaki", 90)
     ```

3. **`tampilkan(self)`**  
   Menampilkan semua data mahasiswa yang tersimpan di dalam `data`.  
   - Jika data kosong, program mencetak pesan "Tidak ada data mahasiswa."
   - Jika terdapat data, ditampilkan dalam format `nama: nilai`.  
   - **Contoh Output:**  
     ```
     Daftar Nilai Mahasiswa:
     Dzaki: 90
     Arif: 80
     Rahman: 85
     Santoso: 90
     ```

4. **`hapus(self, nama)`**  
   Menghapus data mahasiswa berdasarkan nama.  
   - **Parameter:**  
     - `nama` (str): Nama mahasiswa yang datanya akan dihapus.  
   - Jika nama ditemukan, program akan menghapus data dan mencetak pesan konfirmasi.
   - Jika nama tidak ditemukan, akan mencetak pesan bahwa data tidak ditemukan.  

5. **`ubah(self, nama, nilai_baru)`**  
   Mengubah nilai mahasiswa berdasarkan nama.  
   - **Parameter:**  
     - `nama` (str): Nama mahasiswa yang datanya akan diubah.
     - `nilai_baru` (int): Nilai baru yang akan diberikan.  
   - Jika nama ditemukan, nilai mahasiswa diubah dan program mencetak pesan konfirmasi.
   - Jika nama tidak ditemukan, program mencetak pesan bahwa data tidak ditemukan.

---

