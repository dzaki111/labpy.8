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
## Contoh Penggunaan

```python
if __name__ == "__main__":
    mahasiswa = Mahasiswa()

    # Menambahkan data mahasiswa
    mahasiswa.tambah("Dzaki", 90)
    mahasiswa.tambah("Arif", 80)
    mahasiswa.tambah("Rahman", 85)
    mahasiswa.tambah("Santoso", 90)

    # Menampilkan data mahasiswa
    mahasiswa.tampilkan()

    # Mengubah data mahasiswa
    mahasiswa.ubah("Rahman", 90)
    mahasiswa.ubah("Dzaki", 100)

    # Menghapus data mahasiswa
    mahasiswa.hapus("Santoso")

    # Menampilkan data mahasiswa setelah perubahan
    mahasiswa.tampilkan()
```

---

## Hasil Eksekusi

1. **Menambahkan Data**  
   ```
   Data Dzaki dengan nilai 90 berhasil ditambahkan.
   Data Arif dengan nilai 80 berhasil ditambahkan.
   Data Rahman dengan nilai 85 berhasil ditambahkan.
   Data Santoso dengan nilai 90 berhasil ditambahkan.
   ```

2. **Menampilkan Data Awal**  
   ```
   Daftar Nilai Mahasiswa:
   Dzaki: 90
   Arif: 80
   Rahman: 85
   Santoso: 90
   ```

3. **Mengubah Data**  
   ```
   Data Rahman berhasil diubah menjadi 90.
   Data Dzaki berhasil diubah menjadi 100.
   ```

4. **Menghapus Data**  
   ```
   Data Santoso berhasil dihapus.
   ```

5. **Menampilkan Data Akhir**  
   ```
   Daftar Nilai Mahasiswa:
   Dzaki: 100
   Arif: 80
   Rahman: 90
   ```
## screenshout Hasil vsc

![Screenshot 2024-12-09 144836](https://github.com/user-attachments/assets/11fa6c92-22d9-4e9f-b1fb-ea68b56a53a5)

## screenshout Flowchart

