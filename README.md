
|Nama|NIM|Kelas|Matkul|
|----|---|-----|------|
|Restu sayidina ahmad |312310431|TI.23.A4|Pemograman Web 1|

* Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

![Screenshot 2024-10-08 113513](https://github.com/user-attachments/assets/0a2ff9ff-bf3d-472c-ad18-234c41d46d9d)

Hal yang saya Ubah yaitu :
1. Background yang menjadi warna Biru muda
2. Header yang saya warnai biru tua dengan text putih
3. Navigasi Tautan yang diberi efek hover
4. menambahkan bayangan dan sudut membulat untuk memberi kesan rapi.
   

*  Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya

Perbedaan antara pendeklarasian CSS menggunakan h1 {...} dan #intro h1 {...} terletak pada spesifisitas selektor yang digunakan:

Selektor Elemen (h1 {...}) mengaplikasikan gaya ke semua elemen h1 di halaman web tanpa membedakan konteks di mana elemen tersebut berada. Jadi, semua elemen h1 yang ada di halaman akan mendapatkan gaya yang sama.

Selektor ID (#intro h1 {...}) ini lebih spesifik. Ia hanya akan mengaplikasikan gaya ke elemen h1 yang berada di dalam elemen dengan ID intro. Ini memungkinkan kita menerapkan gaya khusus hanya untuk elemen h1 di dalam konteks tertentu (di dalam elemen dengan ID intro), tanpa mempengaruhi elemen h1 lain di luar konteks tersebut.

![Screenshot 2024-10-08 115745](https://github.com/user-attachments/assets/06880cd3-73ad-4ef3-a139-99565b1ac44a)

* Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!

Yang akan muncul dalam hasil nya adalah Inline CSS karena Inline CSS mempunyai prioritas tertinggi di antara eksternal atau internal, contoh :

![Screenshot 2024-10-08 123606](https://github.com/user-attachments/assets/15d9b27e-eeea-4321-ae09-8c2b9d0fe37a)

CSSnya

![Screenshot 2024-10-08 123625](https://github.com/user-attachments/assets/a3d41c5b-85ab-4d60-b8f7-a82c0757ba6a)

Maka Hasilnya : 

![Screenshot 2024-10-08 130300](https://github.com/user-attachments/assets/fb3003a0-cd33-465e-802e-52bf72cd266a)



* Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya!

Ketika sebuah elemen HTML memiliki ID dan class, dan kedua selektor tersebut memiliki deklarasi CSS masing-masing,
maka spesifisitas (specificity) akan menentukan deklarasi mana yang akan ditampilkan oleh browser.
Dengan kata lain, jika sebuah elemen memiliki ID dan class, dan kedua selektor tersebut mengatur properti yang sama, gaya dari ID akan lebih prioritas.

![Screenshot 2024-10-08 124808](https://github.com/user-attachments/assets/f23c8143-f183-45b8-b483-04a49128d426)

Dan hasilnya adalah :

![Screenshot 2024-10-08 130327](https://github.com/user-attachments/assets/c151fc72-f6f8-41d5-bb8f-bb4733c21b74)

