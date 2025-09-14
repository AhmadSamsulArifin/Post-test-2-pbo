# Post-test-2-pbo

##Deskripsi Singkat 


Program ini merupakan aplikasi sederhana berbasis Java yang mengimplementasikan konsep CRUD (Create, Read, Update, Delete) untuk mengelola data ruangan rumah sakit. Data yang dikelola meliputi nomor ruangan, tipe ruangan, dan status ruangan.Struktur program dibuat dengan memisahkan class sesuai fungsinya, menggunakan constructor, access modifier, serta penerapan packages (main, model, service) untuk mendukung konsep MVC (Model-View-Controller).

##Class


<img width="330" height="153" alt="image" src="https://github.com/user-attachments/assets/6808b765-19ad-4469-a7bc-20894d319c25" />


Disini kita terdapat 3 class yaitu
class Ruangan = berfungsi menyimpan struktur data
class RuanganService = Berfungsi untuk menyimpan logika CRUD (Create, Read, Update, Delete).
class Main = menu utama (tempat user memilih apakah ingin menambah data, menampilkan data, mengedit data, menghapus data, mencari, dll).


##Properties


<img width="661" height="193" alt="image" src="https://github.com/user-attachments/assets/a6810a65-9ee2-43e4-93d9-bc7b0ffdd068" />


Di dalam program ini, setiap class model harus memiliki minimal 3 properti (atribut). Class Ruangan digunakan sebagai model untuk menyimpan informasi data ruangan. 3 properti terdiri dari :

Nomor ruangan
tipe ruangan
status

##Constructor


<img width="588" height="132" alt="image" src="https://github.com/user-attachments/assets/5ea5f5ec-f0ee-44cc-9b0c-765264d9c611" />


Constructor adalah method khusus dalam Java yang dipanggil secara otomatis saat sebuah objek dibuat dari sebuah class. Didalam program ini diterapkan pada class Ruangan di dalam package model. Ketika akan membuat objek baru dari class Ruangan, constructor ini akan langsung dipanggil untuk mengisi nilai dari nomor, tipe, dan status.


##Access Modifier


<img width="977" height="361" alt="image" src="https://github.com/user-attachments/assets/b98e7a6e-f540-4296-a6d0-1a74d1074782" />


Dalam program CRUD ini, sudah menerapkan access modifier private pada properti class Ruangan, serta public pada constructor, getter, dan setter.


##Packages


<img width="330" height="148" alt="image" src="https://github.com/user-attachments/assets/7ef8a226-bc96-4083-8490-ddda7eee1147" />


Dalam program ini terdapat 3 packages untuk memisahkan class
packages main > terdapat class main yang isinya adalah kode yang menyimpan menu user
packages service > terdapat class ruanganservice yang berfungsi menyimpan kode logika CRUD
packages model > terdapat class ruangan untuk menyimpan struktur data seperti atribut dan constructor

##Mvc


<img width="331" height="150" alt="image" src="https://github.com/user-attachments/assets/bb5b3e3d-8024-4446-907f-a5d221e042a4" />


Program ini sudah menerapkan pola MVC (Model - View - Controller) dengan pemisahan kode ke dalam 3 packages berbeda agar lebih rapi, mudah dipahami, dan terstruktur.

Struktur packages :

Model → Class Ruangan yang merepresentasikan struktur data dengan properti, constructor, getter, dan setter.
View → Class Main yang menangani tampilan menu utama pengguna serta input/output.
Controller (Service) → Class RuanganService yang menangani logika bisnis, validasi input, dan operasi CRUD.

##Validasi input


<img width="539" height="77" alt="image" src="https://github.com/user-attachments/assets/a5d43d56-ffa7-48c6-ac58-f82a5ac9782f" />


Program menambahkan validasi agar data yang dimasukkan user sesuai aturan. Dalam program ini saya menambahkan tipe ruangan hanya boleh yang tertera di atas selain itu maka inputan tidak valid, dan juga saya menambahkan status itu hanya boleh terisi dan kosong jika lain dari kedua tersebut maka harus mengisi kembali.

##Fitur search.


<img width="532" height="116" alt="image" src="https://github.com/user-attachments/assets/e3a6ae4e-dedf-41a6-bfb3-c74faa7e844b" />


Di dalam program ini fitur search ini memungkinkan user bisa mencari ruangan berdasarkan nomor dan tipe.

##Alur Program

Program ini memiliki 7 menu 


<img width="1016" height="243" alt="image" src="https://github.com/user-attachments/assets/4436b521-0609-43a5-be82-ec4c09a62864" />




1. menu pertama yaitu menambah data, pada bagian ini user bakal diminta untuk mengisi data data seperti nomor ruangan,tipe ruangan, dan status.


<img width="977" height="229" alt="image" src="https://github.com/user-attachments/assets/87638fbb-dc61-428c-9b36-f39418e74f29" />



2. menu kedua yaitu menampilkan semua ruangan, dimenu ini program bakal menampilkan semua ruangan yang sudah di tambahkan.


<img width="973" height="187" alt="image" src="https://github.com/user-attachments/assets/e43b31b7-54a1-4a4e-a72e-82fc8ac0bf3e" />



3. menu ketiga yaitu mengupdate atau mengubah data, jadi pada menu ini user memilih mana yang akan diubah datanya.


<img width="965" height="238" alt="image" src="https://github.com/user-attachments/assets/536f8f17-0a7e-4cc7-a288-22256863a4ba" />



4. menu keempat yaitu menghapus ruangan, jadi dimenu ini user dapat menghapus data dengan memilih nomor yang ingin dihapus.


<img width="982" height="206" alt="image" src="https://github.com/user-attachments/assets/580a0c35-7f0f-4e41-99ae-9957628fc633" />



5. menu kelima yaitu mencari ruangan bedasarkan nomor, jadi dimenu ini user harus memasukkan nomor mana yang ingin di cari


<img width="580" height="211" alt="image" src="https://github.com/user-attachments/assets/e18bfac2-02f7-4937-9e99-fb6ee716ce1c" />



6. menu keenam yaitu mencari ruangan bedasarkan tipe, jadi dimenu ini user harus memasukkan tipe ruangan apa yang ingin di cari


<img width="971" height="197" alt="image" src="https://github.com/user-attachments/assets/4498f69a-5167-4799-8fe8-11174d374c0c" />



7. menu ketujuh yaitu keluar dari program


<img width="975" height="289" alt="image" src="https://github.com/user-attachments/assets/dc8b1d98-67c0-4220-9274-e89e21009658" />











