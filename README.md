# **Penggunaan Git (Tutorial)**
# GIT
Git adalah salah satu VCS (Version Control Sistem) yg diciptakan Linus Torvalds, yang bertugas mencatat setiap perubahan pada file yang dikerjakan sendiri atau kelompok.

## Cara instal
* Langkah pertama yaitu mendownload aplikasi git di pada situs resmi [git](https://git-scm.com/) sesuai dengan versi windows anda

## Pengecekan git version
* untuk mengecek versi git yang terinstal pada komputer anda silahkan buka cmd, kemudian tuliskan `git --version`


![github](https://github.com/Marinska/latihan-1/blob/master/1.PNG)

## Menambah Global Config
* untuk penggunaan perdana, kita perlu mengkonfigurasi user.name dan user.email terlebih dahulu
* tambahkan username dengan perintah
`git config --global user.name "nama-user"`
* tambahkan useremail dengan perintah
 `git config --global user.email "akun-user"`

## Perintah dasar pada Git
* **git init**, untuk membuat repo local
* **git add**, menambah file baru
* **git commit**, menyimpan pembaharuan data pada git 
* **git push -u origin master**, mengirim perubahan pada repository
* **git clone [url]**, untuk mengcopy repository
* **git remote add origin [url]**, untuk menambah remote repository server

## Membuat repository lokal
* buka directory aktif, contoh c:\users\documents\github.
* klik kanan pada directory tersebut, pilih `git bash /terminal` sehingga muncul git bash comand.
* buat direktory dengan nama **latihan-1**, dengan perintah
`mkdir latihan-1`
* kemudian masuk kedalam directory tsb, dengan perintah
`cd latihan-1`

![github](https://github.com/Marinska/latihan-1/blob/master/2.PNG)


## Membuat repository local
* masukan perintah `git init`, untuk membuat repo local
* maka repository baru berhasil di inisialisasi, dengan adanya folder baru di direktory hidden dengan nama **.git**
* semua perubahan akan disimpan di directory tersebut.

![github](https://github.com/Marinska/latihan-1/blob/master/3.PNG)

## Menambah file baru
* buat file dengan nama readme.md pada directory repository 
`echo "#latihan-1" >> readme.md`

![github](https://github.com/Marinska/latihan-1/blob/master/4.PNG)

* tambahkan file readme.md kedalam berkas repo
`git add readme.md`
* cek status repository, masukan perintah
 `git status`
 
![github](https://github.com/Marinska/latihan-1/blob/master/5.PNG)

## Menyimpan perubahan ke database server repo
 * untuk menyimpan perubahan ke repositorylokal, gunakan perintah
  `git commit -m "comment"`
  
  ![github](https://github.com/Marinska/latihan-1/blob/master/6.PNG)  
  
## Membuat repository server pada web github
* pada laman **github**, silahkan login dengan id masing-masing
* pada pojok kanan atas, pilih tombol + untuk membuat repository baru

![github](https://github.com/Marinska/latihan-1/blob/master/7.PNG)

* isikan nama repository, lalu klik tombol **create repository**

![github](https://github.com/Marinska/latihan-1/blob/master/8.PNG)


## Remote repository
* untuk menambah remote repository, masukan perintah : 
`git remote add origin [url]`

![github](https://github.com/Marinska/latihan-1/blob/master/9.PNG)

## Push directory (mengirim perubahan keserver)
* untuk mengirim perubahan dengan push, masukan perintah
`git push -u origin master`
* biasanya, akan dimintai keterangan identitas id
* silahkan masukan username dan password **github**

![github](https://github.com/Marinska/latihan-1/blob/master/10.PNG)
![github](https://github.com/Marinska/latihan-1/blob/master/11.PNG)

## Melihat hasil repository pada web
* hasilnya dapat dilihat di repository **github** yang telah kita buat.
![github](https://github.com/Marinska/latihan-1/blob/master/12.PNG)

## Clone repository
* clone repository yaitu mengcopy sebuah repository yang sudah ada
* untuk mengcloning sebuah repository, silahkan masukan perintah
![github](https://github.com/Marinska/latihan-1/blob/master/13.PNG)

# Terima Kasih
Nama : Umar Ibnu Zainal Muttaqin
Kelas : TI.18.B.2
NIM : 311810909