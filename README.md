# **Penggunaan Git (Tutorial)**
# GIT
Git adalah salah satu VCS (Version Control Sistem) yg diciptakan Linus Torvalds, yang bertugas mencatat setiap perubahan pada file yang dikerjakan sendiri atau kelompok.

## Cara instal
* Langkah pertama yaitu mendownload aplikasi git di pada situs resmi [git](https://git-scm.com/) sesuai dengan versi windows anda

## Pengecekan git version
* untuk mengecek versi git yang terinstal pada komputer anda silahkan buka cmd, kemudian tuliskan `git --version-


![github](https://github.com/marinska/latihan1/1.png)

## Menambah Global Config
* untuk penggunaan perdana, kita perlu mengkonfigurasi user.name dan user.email terlebih dahulu
* tambahkan username dengan perintah
`git config --global user.name "nama-user"`
* tambahkan useremail dengan perintah
 `git config --global user.email "akun-user"`

## Perintah dasar pada Git
* **git init, untuk membuat repo local
* **git add, menambah file baru
* **git commit, menyimpan pembaharuan data pada git 
* **git push -u origin master, mengirim perubahan pada repository
* **git clone [url], untuk mengcopy repository
* **git remote add origin [url], untuk menambah remote repository server

## Membuat repository lokal
* buka directory aktif, contoh c:\users\documents\github.
* klik kanan pada directory tersebut, pilih `git bash /terminal` sehingga muncul git bash comand.
* buat direktory dengan nama **latihan1**, dengan perintah
`mkdir latihan1`
* kemudian masuk kedalam directory tsb, dengan perintah
`cd latihan1`

![github](https://github.com/marinska/latihan1/2.png)


## Membuat repository local
* masukan perintah `git init`, untuk membuat repo local
* maka repository baru berhasil di inisialisasi, dengan adanya folder baru di direktory hidden dengan nama **.git**
* semua perubahan akan disimpan di directory tersebut.

![github](https://github.com/marinska/latihan1/3.png)

## Menambah file baru
* buat file dengan nama readme.md pada directory repository 
`echo "#latihan1" >> readme.md`

![github](https://github.com/marinska/latihan1/4.png)

* tambahkan file readme.md kedalam berkas repo
`git add readme.md`
* cek status repository, masukan perintah
 `git status`
 
![github](https://github.com/marinska/latihan1/5.png)

## Menyimpan perubahan ke database server repo
 * untuk menyimpan perubahan ke repositorylokal, gunakan perintah
  `git commit -m "file utama"`
  
  ![github](https://github.com/marinska/latihan1/6.png)  
  
## Membuat repository server pada web github
* pada laman **github**, silahkan login dengan id masing-masing
* pada pojok kanan atas, pilih tombol + untuk membuat repository baru

![github](https://github.com/marinska/latihan1/7.png)

* isikan nama repository, lalu klik tombol **create repository**

![github](https://github.com/marinska/latihan1/8.png)


## Remote repository
* untuk menambah remote repository, masukan perintah : 
`git remote add origin [url]`

![github](https://github.com/marinska/latihan1/9.png)

## Push directory (mengirim perubahan keserver)
* untuk mengirim perubahan dengan push, masukan perintah
`git push -u origin master`
* biasanya, akan dimintai keterangan identitas id
* silahkan masukan username dan password **github**

![github](https://github.com/marinska/latihan1/10.png)
![github](https://github.com/marinska/latihan1/11.png)

## Melihat hasil repository pada web
* hasilnya dapat dilihat di repository **github** yang telah kita buat.
![github](https://github.com/marinska/latihan1/12.png)

## Clone repository
* clone repository yaitu mengcopy sebuah repository yang sudah ada
* untuk mengcloning sebuah repository, silahkan masukan perintah
![github](https://github.com/marinska/latihan1/13.png)

# Terima Kasih
