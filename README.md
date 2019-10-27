  
latihan1
<br/> **NAMA  : CUTRIDA ZAENAH ZAENAL**
<br/> **NIM   : 311910007**
<br/> **UNIV  : UNIVERSITAS PELITA BANGSA**
<br/> Tugas   : bahasa pemrograman
<br/>
<br/>
# MEMBUAT DAN MENAMBAHKAN FILE REPOSITORY 
## install aplikasi
download dan install aplikasi git sesuai os anda.. bisa download di (https://git-scm.com)
<br/>!![1](https://user-images.githubusercontent.com/56877903/67621947-e4b15b00-f83e-11e9-9622-625104e13103.PNG)
<br/>
<br/>
## buat akun git hub anda
<br/> buat akun git server anda di  (github.com) 
<
<br/>
![2](https://user-images.githubusercontent.com/56877903/67621948-e4b15b00-f83e-11e9-8b16-132f0103a368.PNG)

## Menambahkan Global Config
<br/>1.lakukanlah kofigurasi user name dan user email anda ke git dengan cara
<br/>2.buka aplikasi git
<br/>3.ketikan perintah
<br/> **git config --global user.name "username hub anda"**
<br/> **git config --global user.email "email hub anda"**
<br/>![2hubungkan](https://user-images.githubusercontent.com/56870558/67306357-0948c280-f521-11e9-83ba-fb213f78b1f0.jpg)
## membuat repository local
<br/>**1**. buat folder baru di windows explorer contoh d:\bahasa pemrograman
<br/>**2**. klik kanan dan pilih Git Bash
<br/>![3buat repost local](https://user-images.githubusercontent.com/56870558/67306361-0948c280-f521-11e9-9f7a-44c52195923c.jpg)
<br/>**3**. setelah ke git bash command buat direktori latihan anda contoh **latihan1**
<br/> **$ mkdir latihan1**
<br/> **$ cd latihan1**
<br/>![4 buat folder](https://user-images.githubusercontent.com/56870558/67306356-08b02c00-f521-11e9-911f-bbf673de2954.jpg)
## Membuat repository local
<br/>1.jalankan perintah **$ git init**
<br/>2. jika berhasil akan ada folder tersembunyi dengan nama **.git** di dalam folder latihan1
<br/>![5buat trpost local](https://user-images.githubusercontent.com/56870558/67308432-4c586500-f524-11e9-82bc-82e678640740.jpg)
<br/>
## Menambahkan file baru di repository
<br/>1.kita coba buat file bernama README.md 
<br/>2.jalankan perintah **$ echo "#latihan1" >> README.md**
<br/>3.file README.md Berhasil di buat
<br/>![6buat readme md](https://user-images.githubusercontent.com/56870558/67308433-4c586500-f524-11e9-95a6-6e56c5455086.jpg)
<br/>
<br/>4.tambahkan file tersebut ke dalam repository anda dengan perintah
<br/>**$ git add README.md**
<br/>![6c](https://user-images.githubusercontent.com/56870558/67308435-4cf0fb80-f524-11e9-82d6-2b44e3065d80.jpg)

## Simpan Perubahan Ke Data Base *commit*##
<br/>1.gunakan perintah **git commit -m "commit command"**
<br/>contoh : **$ git commit -m "file pertama"**
<br/>![6d](https://user-images.githubusercontent.com/56870558/67308437-4cf0fb80-f524-11e9-9781-23501adab517.jpg) 
<br/> perubahan berhasil di buat

## Membuat REpository Server
<br/>1.pertama pastikan akun git hub anda sudah di verifikasi
<br/>2.masuk ke akun anda klik tombol **+** yang ada di pojok kanan
<br/>3.klik **new repository**
<br/>4.**masukan repository** name contoh : latihan1
<br/>5.unchecklist pada **initialize this repository with a README** agar memudahkan tutorial pembelajaran ini
<br/>6.lalu klik **create repository**
<br/>![8 repostr](https://user-images.githubusercontent.com/56870558/67309649-701caa80-f526-11e9-8a09-99d9c9158943.jpg)
<br/>
## Menambahkan Remote Repository 
<br/>1.Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user. 
<br/>2.untuk menambahkan gunakan perintah **git remote add origin *(url)***
<br/>3.contoh **$ git remote add origin https://github.com/alikenzo99/latihan1.git**
<br/>![add origin](https://user-images.githubusercontent.com/56870558/67310110-53cd3d80-f527-11e9-818a-8cfb47939cb3.jpg)
<br/>

## Mengirimkan ke server *push*
<br/>1.untuk mengirim perubahan local repository ke server gunakan printah git push
<br/> **$ git push -u origin master**
<br/>2.nanti akan diminta password dan email anda pastikan input dengan benar
<br/>![push u](https://user-images.githubusercontent.com/56870558/67310444-f2599e80-f527-11e9-9da3-3cb37b087c13.jpg)
<br/>
<br/>
## Selesai sudah
<br/>1.untuk melihatnya coba buka laman https://github.com) arahkan pada repository yang anda buat tadi
<br/>2.maka perubahan dapat terlihat dengan munculnya file readme.md disitu..
<br/>
<br/>![selesai](https://user-images.githubusercontent.com/56870558/67310446-f2599e80-f527-11e9-9213-528d4efc1caf.jpg)






