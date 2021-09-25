# Jarkom-Modul-1-A08-2021
Praktikum Jaringan Komputer 2021 - Modul 1  
Anggota:
-   05111940000030 - Bunga Fairuz Wijdan
-   05111940000062 - Thomas Felix Brilliant
-   05111940000145 - Ikhlasul Amal Rivel

**Soal Pratikum Modul 1 Jaringan Komputer 2021:**

* [Soal 1](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-1)
* [Soal 2](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-2)
* [Soal 3](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-3)
* [Soal 4](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-4)
* [Soal 5](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-5)
* [Soal 6](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-6)
* [Soal 7](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-7)
* [Soal 8](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-8)
* [Soal 9](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-9)
* [Soal 10](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-10)
* [Soal 11](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-11)
* [Soal 12](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-12)
* [Soal 13](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-13)
* [Soal 14](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-14)
* [Soal 15](https://github.com/ThomasFel/Jarkom-Modul-1-A08-2021#Soal-15)

## Soal 1

### Sebutkan webserver yang digunakan pada "[ichimarumaru.tech](http://ichimarumaru.tech/)"!

Mengisi *display filter* dengan ‘**http.host contains ichimarumaru.tech**’.
![](https://lh4.googleusercontent.com/5S9fx9eWhHtdtnJ5qRXSaH3HlX9Y1Kh_6fTL5_J2xFHL1xWq0ljwIRd6TQxR_dQFK6apHmhUMsMbvvRT7pvpe82TbHIfr1WmFbTt58zJFEQji_WySjiVhQDPQkn3rDFoQQ=s0)

Follow TCP Stream.
![](https://lh5.googleusercontent.com/mmMB4X8I24Ggsqie-ZkWEuZj1mVuV3r1VwZ1dRi7AjnN85QPfMrw5XeOenEnJWw9BoJ7Th-paOr7PitcQfdwEre45gVMe1DmN0H9wwqmU-VVP3_Koc21NX8BcqIVBH4x6g=s0)

Kemudian bisa dilihat server yang dipakai adalah **nginx/1.18.0 (Ubuntu)**.
![](https://lh5.googleusercontent.com/3ZRdVaGcsWFdgdQcZ-OslxAxhGLeszLz-jPFkwN00yV_M8eDtTTof1E5S3Jsit_t8h4kc0_-Z5nOdA5PQbyaOQxu7BoZUZm1Ac9wEX8jnm8iTWO8JSiQLCXCXYqiDgi0rQ=s0)

## Soal 2

### Temukan paket dari web-web yang menggunakan basic authentication method!

Mengisi display filter dengan ‘**http.authbasic**’.
![](https://lh3.googleusercontent.com/VcjnbkERzFKHO0KVSw6P9DCflWOWcDTfRuHCC_FxYJHKeHzBS5OvHOFJVawBQgbW0DHVOk9g6vq0GaS_lPAP5-MTtUfP8Lfqr28UAZoUkHC6uM6zvz6Wx_nbA6YcPkXU5Q=s0)

Maka akan muncul website-website yang menggunakan metode **basic authentication**.

## Soal 3

### Ikuti perintah di [](http://aku.pengen.pw/) [basic.ichimarumaru.tech](http://basic.ichimarumaru.tech/)! Username dan password bisa didapatkan dari file .pcapng!

Mengisi display filter dengan ‘**http.host contains basic.ichimarumaru.tech**’.

![](https://lh4.googleusercontent.com/rGgVSXrZHhuLuFiZHfEbmYIx1n0RLoLxShk9EiWqdITKXbxjsQZYFeqCpW7ys_gV2QNgRSYPZgnPpp43uSVjYeJleKhFVdj0LospyS3kKlfKNPtJ-m3gsldFsyN3ciFzzQ=s0)

Lalu kita bisa melihat username dan password dari website dengan membuka **paket 568** (paket kedua), masuk ke Hypertext Transfer Protocol, Get, lalu ke Credentials. Didapat:

-   **Username  : kuncimenujulautan**
-   **Password  : tQKEJFbgNGC1NCZlWAOjhyCOm6o3xEbPkJhTciZN**

![](https://lh4.googleusercontent.com/Y84UK9tFa0hvecoYQZEDH5HX427pt5hwdiOVXI8_8kBnHduqmetczRisF2_mPFx72tamfGL7N-RHuyCU1BeR4kJtYrsMXzTva4bOyYb_kMnji9t7pzsKKiCzplOYN9cf9w=s0)

Kembali ke browser, lalu menuju **[](http://aku.pengen.pw/) [basic.ichimarumaru.tech](http://basic.ichimarumaru.tech/)**. Masukkan username dan password-nya. Akan muncul laman seperti di bawah.

![](https://lh3.googleusercontent.com/EKBv_HtMx1dFpu6h9Ajrfn3PQ1epQ1RCWz7gmg42M3nPS6t2g1km5i4rdDHJgtSGdKp7lzHoZcPbVt_CjYspD8_T5vj5lWModRQZ_naDIBdCKS0DSXuWLTUXwACah8QeJA=s0)

Jawab soal yang ada di laman tersebut. Jawabannya adalah ‘**putih-hijau, hijau, putih-oranye, biru, putih-biru, oranye, putih-cokelat, cokelat**’.

## Soal 4

### Temukan paket mysql yang mengandung perintah  query select!

Mengisi display filter dengan ‘**mysql.query contains select**’.

![](https://lh6.googleusercontent.com/mJ9cXK042mHRbkCYc97W21GWx9kgq_M8dELRoX_-azvLJGk8jimax_LE0agsSRe1jgPXn_mGtZgIE3WhfNnRajikAgdnOX5ttX9MUsZYBM-GaC4dHRkFcC8p8CKOCN3oAg=s0)

Akan muncul paket yang mengandung perintah query **select**.

## Soal 5

### Login ke [portal.ichimarumaru.tech](http://portal.ichimarumaru.tech/) kemudian ikuti perintahnya! Username dan password bisa didapat dari query insert pada table users dari file .pcap!

Mengisi display filter dengan ‘**mysql.query**’.

![](https://lh6.googleusercontent.com/OUZQHFF8yW3XoIHLIZonNy6-Rgfx5nfeXqJZtR9d2PWuI6-ocltKrb2CvZjSw5H65jBiusAJ8ptXHYOZ79Yl8gUYdGw-TT_6_R0O0WLgmrQbYmi34qHsukwSwOF5gLLHVw=s0)

Akan muncul query **insert** yang berisi:
-   **Username  : akakanomi**
-   **Password  : pemisah4lautan**
Masukkan username dan password-nya.

![](https://lh3.googleusercontent.com/BY1KfJ-9w2iP5NJIU_YZeQa-GpBr-tAONAp6t5NJlStIwNkVSkHhbPygJb66HOJHszKTK4RKASBQQMhLgGiAsnfzVnGtTjw50_OmxtvwqseLm6vVHCZXrJvHXr-kaVOa4g=s0)

Kemudian, akan muncul laman seperti ini dan bisa dijawab soal yang ada.

![](https://lh6.googleusercontent.com/VxGSC6flwkSqtHySF7hYh41M9vcI5F2I-ySUuelK8zzJEemW9Feqp8DKNasRPFKzFUyBk1V3-KmcTb1D2RC7JtBWTjggfcw4iV6F7AiyZHOq_ysQwpJjLGQOV0Cq2Qg0_g=s0)

Jawabannya adalah ‘**putih-oranye, oranye, putih-hijau, biru, putih-biru, hijau, putih-cokelat, cokelat**’.

## Soal 6

### Cari username dan password ketika melakukan login ke FTP Server!

## Soal 7

### Ada 500 file zip yang disimpan ke FTP Server dengan nama 0.zip, 1.zip, 2.zip, ..., 499.zip. Simpan dan Buka file pdf tersebut. (Hint = nama pdf-nya "Real.pdf")

## Soal 8

### Cari paket yang menunjukan pengambilan file dari FTP tersebut!

## Soal 9

### Dari paket-paket yang menuju FTP terdapat inidkasi penyimpanan beberapa file. Salah satunya adalah sebuah file berisi data rahasia dengan nama "secret.zip". Simpan dan buka file tersebut!

## Soal 10

### Selain itu terdapat "history.txt" yang kemungkinan berisi history bash server tersebut! Gunakan isi dari "history.txt" untuk menemukan password untuk membuka file rahasia yang ada di "secret.zip"!

## Soal 11

### Filter sehingga wireshark hanya mengambil paket yang berasal dari port 80!
Mengisi capture filter dengan ‘src port 80’
![](https://lh5.googleusercontent.com/hUOrSzoUN9blEmv2pfzeUwjaPyzfZZPVs6zJA6W-aMCZXklpL7IbfEujE3LEfis_UWUog9yMlTfjYV3usPVhmdW48iuqABtjvQWndoulY16fjTeVLS-Y5D1GWKjYvNNLAKYD33PG=s0)

Hasil ketika mengambil paket dari port 80
![](https://lh3.googleusercontent.com/vaEO3aXkNU6SET8YBNRM2vvlIpJhu-wpj4sO9x6hKn_ZzZyKM7Ird-gnH8xm_Lni__S4XsawyJLJ7LGxuvnytFEyHaYT3DXDhJyZqsAl932mwccqelQRsUCmmWEdVwGiY892nrOR=s0)

## Soal 12

### Filter sehingga wireshark hanya mengambil paket yang mengandung port 21!
Mengisi capture filter dengan ‘port 21'
![](https://lh3.googleusercontent.com/_B3NMd98Xb0q0EyYNzPJgsLBgUYR2nOSTkAFVJKAHmVjFkKDTGq29q4zVIgnafoye20KZocgFzlD98RKnn9WDA8Y4UKNzuW37lzw2xIHPkkynNFSqpKtD6nUpUVxUJZtsM4N-jaA=s0)

Hasil ketika paket mengandung port 21. Di sini tidak ada yang dimunculkan
![](https://lh4.googleusercontent.com/kXfuiuxiPIjUb-dCI7GLL7hCpg3yAqjvNTiNoNpNr9k5ud04E-6gIzu7eF1yMvTdWC3TJk5f-6mKqBdoaxJdJ-RItsqGndI_GePqZ4vqIbDsKFRqHvrKbIzyaOPxNE4a-jVpAMtM=s0)

## Soal 13

### Filter sehingga wireshark hanya menampilkan paket yang menuju port 443!
Mengisi capture filter dengan ‘dst port 443’
![](https://lh5.googleusercontent.com/FN2ajb6ZiP1LU3gW3_9ulJ5COR8LHq825CDqwd8REXk5znIsbGXbMFn_36KA7J90J3K27cC5V3U-B2luxkFCkTmmEdcZx6ImBSUvuJATg_CPRiYYnMYU_B6_pGf2VhI2fpAjLkmO=s0)

Hasil ketika menampilkan paket menuju port 443
![](https://lh3.googleusercontent.com/i4wjZgzO1cbuZMS6_pvCVohkV7UmoLpMtJ-FFjdHkYdM1MQHJ1AXyeuEHhQ96cn9lTjT0X1GdomJsSupzytgh5ks0sgF2Q2N1pjrIJt9e9R_U1SOXg0gCXVYLLhrPaP40d60afTb=s0)

## Soal 14

### Filter sehingga wireshark hanya mengambil paket yang tujuannya ke kemenag.go.id!
Mengisi capture filter dengan ‘host kemenag.go.id’
![](https://lh6.googleusercontent.com/lSGu79rxmJmCkh2ZDi9zaZm2lljEb6DVzwrvX8ei-Qpfs_TAPsGOR9iZgK4dbQ88m8SZi5-ziJ6bLHqieAjCBq98Wc4YcWKOr0ldMux9yFAxXbRFja6Vp66t88liySsTaxP8hCrF=s0)
    
Hasil ketika menampilkan paket yang tujuannya kemenag.go.id
![](https://lh4.googleusercontent.com/nmEjUtEZCmitx3SoDCuG98CzjQ3xLGySIfwLXcNk1yJ6aFBEfS_yRO05BfkhENMPu6kx8ePZylpENOLhAsicQU_OqvEb2mtpPfVVhQqwEX8l3aTmYJ8ypppCI0dA7Fh7HUUboih-=s0)

## Soal 15

### Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!
Mengisi display filter dengan ‘ip.src == [ip masing-masing]’
![](https://lh4.googleusercontent.com/44Ifx3KwaoGBaYBstA8YGHlFp2-txT3oVzqep9FoaIlTDejCU1LFgJistk4TVWW6YYnx_7X4-DJmhWUGvabPh04YHBUR_Y0BxfNz5BUfHHUxtMqMji6NI9jWp1CezvLDfssaz54y=s0)
