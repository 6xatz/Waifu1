## Mata Kuliah

Sebagai tugas praktikum: [1] Bahasa Pemrograman | Universitas Pelita Bangsa.

## Cara menggunakan Git

1.  Memilih Shortcut pada Git Bash,
    <p align="left">
      <img src="/ss/1.jpg" width="450">
    </p>

        Target: --cd-to-home
        Start in: %HOMEDRIVE%%HOMEPATH%

dua perintah ini berfungsi agar **_/home/_** yang akan digunakan nanti berada pada User yang logon saat ini.

2.  Konfigurasi Git Config secara Global,

    > bisa juga secara _individual repository_.

    <p align="left">
      <img src="/ss/2.jpg" width="350">
    </p>

        git config --global user.name "6xatz"
        git config --global user.email "airalva@gmail.com"

Kalau typo (awokawok typo), santai aja. Bisa pake perintah **_--reset-author_** kok.

3.  Membuat Repository secara lokal pada drive dan menginisiasi Git,

    > disarankan membuat repository didalam folder kosong agar _/home/_ tidak berantakan.

    <p align="left">
      <img src="/ss/3.jpg" width="380">
    </p>

        pwd
        mkdir waifu
        cd waifu
        git init

**_pwd_** berfungsi untuk memeriksa tempat Git bekerja saat ini.
**_mkdir_** berfungsi untuk membuat folder atau direktori.
**_cd_** berfungsi untuk masuk ke sebuah direktori (**_cd .._** untuk kembali).
**_git init_** berfungsi untuk menginisiasi Git pada sebuah repository.

4.  Membuat Repository secara lokal pada drive dan menginisiasi Git,

    > karena kita sudah membuat _README.md_ sebelumnya. maka pastikan kalian uncheck: create README.md .

    <p align="left">
      <img src="/ss/4.jpg" width="330">
    </p>

        echo "# waifu" >> README.md

**_echo_** berfungsi untuk mengirim perintah ke konsol.
**_"# waifu"_** berfungsi untuk mengeksekusi perintah pada repository yang dituliskan.
**_README.md_** berfungsi untuk membuat _README.md_ .

5.  Menambahkan sebuah files ke Git dan melakukan Commit,

    > kamu bisa menggunakan _git status_ untuk memeriksa apakah terdapat files yang dimodifikasi atau tidak.

    <p align="left">
      <img src="/ss/5.jpg" width="580">
    </p>

        git add README.md
        git commit -m "Kembalilah ke masa lalu. Percayalah, kau akan menyesalinya."

**_git add_** berfungsi untuk menambahkan files ke Git.
**_git commit -m "deskripsi"_** perintah ini berfungsi untuk _"git" -> "lakukan commit" -> "master" (branch) -> "Deskripsi/Alasan commit"_.

6. Membuat Repository,
   > New Repository -> Create Repository.
   <p align="left">
     <img src="/ss/6.jpg" width="650">
   </p>

_konfigurasi harap sesuaikan dengan tugas masing-masing._

7.  Menyambungkan Git pada GitHub.

    > kamu akan disuruh Connect to GitHub (sync account) bisa menggunakan Browser/Token (saran sih make Browser biar lebih mudah).

    <p align="left">
      <img src="/ss/7.jpg" width="580">
    </p>

        git remote add origin https://github.com/6xatz/waifu.git
        git push -u origin master

**_git remote add_** berfungsi untuk menyambungkan Git dan GitHub repository.
**_git push_** berfungsi untuk push _git yang sudah di add sebelumnya_ untuk di push ke _branch_.
**_master_** = branch.

## Documentation

All associated resources. are licensed under the [MIT License](https://mit-license.org/).
