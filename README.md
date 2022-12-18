# Belajar Exception pada python

**Dengan menggunakan block try except**

**Repository ini dibuat sebagai tugas Bahasa pemrogramman**

  1. Pertama kita buat sebuah folder bernama `13-exception` dan didalamnya kita buat file bernama `Praktikum.py` , `filedemo.txt` dan `filedemo2.txt`
     
     ![Screenshot (152)](https://user-images.githubusercontent.com/115474950/208316950-5736e0c2-32d9-4484-b11a-ec5f8f1463da.png)
     
  2. Sekarang mari kita buka file `Praktikum.py` lalu inputkan codingan sebagai berikut :
     
     ![Screenshot (153)](https://user-images.githubusercontent.com/115474950/208316955-6edc8946-258e-4e61-8ab8-44d1ed0e612c.png)
     
     Kita melakukan penanganan kesalahan NameError lalu run dengan cara ketik `python Praktikum.py` di terminal Maka hasilnya sebagai berikut :
     
     ![Screenshot (154)](https://user-images.githubusercontent.com/115474950/208316983-80fdb374-2976-4463-9ea9-8a75fea6a605.png)
     
  3. Masih difile yang sama yaitu `Praktikum.py` lalu inputkan codingan sebagai berikut :
     
     ![Screenshot (151)](https://user-images.githubusercontent.com/115474950/208316639-ccf51be4-9555-403d-bd70-98f7f69a8619.png)

     Jangan lupa untuk mengcomment codingan sebelumnya atau kalian boleh hapus agar kita fokus di contoh kedua yaitu FileNotFoundError
     
     lalu run dengan cara ketik `python Praktikum.py` di terminal Maka hasilnya sebagai berikut :
     
     ![Screenshot (152)](https://user-images.githubusercontent.com/115474950/208316681-c9003cdf-d72d-4b28-b864-93296b6e873c.png)

  4. Masih difile yang sama yaitu `Praktikum.py` lalu inputkan codingan sebagai berikut :
     
     
     
     Jangan lupa untuk mengcomment codingan sebelumnya atau kalian boleh hapus agar kita fokus di contoh kedua yaitu FileExistError
     
     lalu run dengan cara ketik python `Praktikum.py` di terminal Maka hasilnya sebagai berikut :
     
     
     
     disini error bahwa file tersebut sudah ada, seperti yang kita lihat filedemo2 sudah kita buat diawal. jadi kita tidak boleh membuat file dengan nama yang sama  dalam satu folder
  
  5. Masih difile yang sama yaitu `Praktikum.py` lalu inputkan codingan sebagai berikut :
     
     
     
     Jangan lupa untuk mengcomment codingan sebelumnya atau kalian boleh hapus agar kita fokus di contoh keempat yaitu TypeError
     
     lalu run dengan cara ketik python `Praktikum.py` di terminal Maka hasilnya sebagai berikut :
     
     
     
     Baik disini errornya berupa type yaitu bahwa nim itu harus integer, karena fungsi input selalu mengembalikan type data string, jika kalian tidak ingin eror kalian bisa convert nim trsebut ke integer dngn cara berikut => nim = int(input("Masukan NIM : "))
     
     
     
