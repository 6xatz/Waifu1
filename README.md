## Mata Kuliah
Sebagai tugas praktikum: [1] Bahasa Pemrograman | Universitas Pelita Bangsa. 

## Cara menggunakan Git
1. Memilih Shortcut pada Git Bash,
<p align="left">
  <img src="/ss/1.jpg" width="450">
</p>

    Target: --cd-to-home
    Start in: %HOMEDRIVE%%HOMEPATH%

dua perintah ini berfungsi agar ***/home/*** yang akan digunakan nanti berada pada User yang logon saat ini.

2. Konfigurasi Git Config secara Global,
> bisa juga secara *individual repository*.
<p align="left">
  <img src="/ss/2.jpg" width="350">
</p>

    git config --global user.name "6xatz"
    git config --global user.email "airalva@gmail.com"

Kalau typo (awokawok typo), santai aja. Bisa pake perintah ***--reset-author*** kok.

3. Membuat Repository secara lokal pada drive dan menginisiasi Git,
> disarankan membuat repository didalam folder kosong agar */home/* tidak berantakan.
<p align="left">
  <img src="/ss/3.jpg" width="380">
</p>

    pwd
    mkdir waifu
    cd waifu
    git init

***pwd*** berfungsi untuk memeriksa tempat Git bekerja saat ini.
***mkdir*** berfungsi untuk membuat folder atau direktori.
***cd*** berfungsi untuk masuk ke sebuah direktori (***cd ..*** untuk kembali).
***git init*** berfungsi untuk menginisiasi Git pada sebuah repository.

4. Membuat Repository secara lokal pada drive dan menginisiasi Git,
> karena kita sudah membuat *README.md* sebelumnya. maka pastikan kalian uncheck: create README.md .
<p align="left">
  <img src="/ss/4.jpg" width="330">
</p>

    echo "# waifu" >> README.md

***echo*** berfungsi untuk mengirim perintah ke konsol.
***"# waifu"*** berfungsi untuk mengeksekusi perintah pada repository yang dituliskan.
***README.md*** berfungsi untuk membuat *README.md* .

5. Menambahkan sebuah files ke Git dan melakukan Commit,
> kamu bisa menggunakan *git status* untuk memeriksa apakah terdapat files yang dimodifikasi atau tidak.
<p align="left">
  <img src="/ss/5.jpg" width="580">
</p>

    git add README.md
    git commit -m "Kembalilah ke masa lalu. Percayalah, kau akan menyesalinya."

***git add*** berfungsi untuk menambahkan files ke Git.
***git commit -m "deskripsi"*** perintah ini berfungsi untuk *"git" -> "lakukan commit" -> "master" (branch) -> "Deskripsi/Alasan commit"*.

6. Membuat Repository,
> New Repository -> Create Repository.
<p align="left">
  <img src="/ss/6.jpg" width="650">
</p>

*konfigurasi harap sesuaikan dengan tugas masing-masing.*

7. Menyambungkan Git pada GitHub.
> kamu akan disuruh Connect to GitHub (sync account) bisa menggunakan Browser/Token (saran sih make Browser biar lebih mudah).
<p align="left">
  <img src="/ss/7.jpg" width="580">
</p>

    git remote add origin https://github.com/6xatz/waifu.git
    git push -u origin master

***git remote add*** berfungsi untuk menyambungkan Git dan GitHub repository.
***git push*** berfungsi untuk push *git yang sudah di add sebelumnya* untuk di push ke *branch*.
***master*** = branch.

## Documentation
All associated resources. are licensed under the [MIT License](https://mit-license.org/).
