
#Latihan 1: Penggunaan GIT
### Nama  : Herlan Wibowo
### NIM   : 312210324
### Matkul: Bahasa pemograman
### kelas : TI 22 A3
#### cara menggunakan git dan membuat file README.md
#### 1.Download git di ***(git-scm.com)***
![Gambar 1](Screenshot/ss1.png)
#### 2.Buka Git Bash lalu kita membuat direktory dengan menjalankan perintah $mkdir latihan1 setelah itu masuk kedalam direktori tersebut dengan ***$cd latihan1***
#### 3.Buat repository lokal dengan **$git init** jika sudah maka akan terbuat directory hidden beernama .git
#### 4.Lalu buat file bernama README.md dengan menjalankan ***$ echo "# latihan1" >> README.md***
![Gambar 2](Screenshot/ss2.png)
#### 5.Tambahkan file baru yang saja dibuat menggunakan ***$git add README.md***
![Gambar 3](Screenshot/ss3.png)
#### 6.Untuk menyimpan perubahan yang ada pada reposiotry local gunakan ***git commit -m "komentar commit"***
![Gambar 4](Screenshot/ss4.png)
#### 7.-Kita akan membuat repository server menggunakan ***http://github.com***
       -Anda harus membuat akun terlebih dahulu.
       -Pada laman github, klik tombol start a project, atau
       -Dari menu (icon +) klik New Repository
       -isi nama repository misal :Repository ke-1
       -lalu klik tombol create repository
       -kita juga bisa jika ingin membuat repository kita tidak ingin di lihat orang banyak klik private jika ingin sebaliknya klik publik
![Gambar 5](Screenshot/ss5.png)
#### 8.Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository,sehingga dapat diakses oleh banyak user
#### Untuk menambahkan remote repository server gunakan ***$ git remote origin [url]*** contoh:
       git remote add origin https://github,com/HerlanWibowo/Latihan1.git
#### 9.Untuk mengirim perubahan dari local repository ke server gunakan perintah git push
#### Perintah ini akan meminta memasukkan username dan password pada akun github anda
       git push -u origin master
#### Jika ingin melihat hasilnya arahkan pada repositorynya
#### Maka perubahan akan terlihat pada laman tersebut
![Gambar 6](Screenshot/ss6.png)
#### Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory).
       Untuk melakukan cloning, gunakan perintah git clone [url]
       $git clone https:github.com/HerlanWibowo/latihan1.git
