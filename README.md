# Jarkom Modul 1 A08 - 2021

Anggota:
-   05111940000030 - Bunga Fairuz Wijdan
-   05111940000062 - Thomas Felix Brilliant
-   05111940000145 - Ikhlasul Amal Rivel

**Daftar Soal:**

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

### Jawaban:

Mengisi *display filter* dengan ``http.host contains ichimarumaru.tech``.

<img src="https://lh4.googleusercontent.com/5S9fx9eWhHtdtnJ5qRXSaH3HlX9Y1Kh_6fTL5_J2xFHL1xWq0ljwIRd6TQxR_dQFK6apHmhUMsMbvvRT7pvpe82TbHIfr1WmFbTt58zJFEQji_WySjiVhQDPQkn3rDFoQQ=s0" width=850>

Follow TCP Stream.

<img src="https://lh5.googleusercontent.com/mmMB4X8I24Ggsqie-ZkWEuZj1mVuV3r1VwZ1dRi7AjnN85QPfMrw5XeOenEnJWw9BoJ7Th-paOr7PitcQfdwEre45gVMe1DmN0H9wwqmU-VVP3_Koc21NX8BcqIVBH4x6g=s0" width=850>

Kemudian bisa dilihat server yang dipakai adalah **nginx/1.18.0 (Ubuntu)**.

<img src="https://lh5.googleusercontent.com/3ZRdVaGcsWFdgdQcZ-OslxAxhGLeszLz-jPFkwN00yV_M8eDtTTof1E5S3Jsit_t8h4kc0_-Z5nOdA5PQbyaOQxu7BoZUZm1Ac9wEX8jnm8iTWO8JSiQLCXCXYqiDgi0rQ=s0" width=850>

## Soal 2

### Temukan paket dari web-web yang menggunakan basic authentication method!

### Jawaban:

Mengisi *display filter* dengan ``http.authbasic``.

<img src="https://lh3.googleusercontent.com/VcjnbkERzFKHO0KVSw6P9DCflWOWcDTfRuHCC_FxYJHKeHzBS5OvHOFJVawBQgbW0DHVOk9g6vq0GaS_lPAP5-MTtUfP8Lfqr28UAZoUkHC6uM6zvz6Wx_nbA6YcPkXU5Q=s0" width="850">

Maka akan muncul website-website yang menggunakan metode **basic authentication**.

## Soal 3

### Ikuti perintah di [](http://aku.pengen.pw/) [basic.ichimarumaru.tech](http://basic.ichimarumaru.tech/)! Username dan password bisa didapatkan dari file .pcapng!

### Jawaban:

Mengisi *display filter* dengan ``http.host contains basic.ichimarumaru.tech``.

<img src="https://lh4.googleusercontent.com/rGgVSXrZHhuLuFiZHfEbmYIx1n0RLoLxShk9EiWqdITKXbxjsQZYFeqCpW7ys_gV2QNgRSYPZgnPpp43uSVjYeJleKhFVdj0LospyS3kKlfKNPtJ-m3gsldFsyN3ciFzzQ=s0" width="850">

Lalu kita bisa melihat *username* dan *password* dari website dengan membuka **paket 568** (paket kedua), masuk ke **Hypertext Transfer Protocol**, **Get**, lalu ke **Credentials**. Didapat:

-   **Username  : kuncimenujulautan**
-   **Password  : tQKEJFbgNGC1NCZlWAOjhyCOm6o3xEbPkJhTciZN**

<img src="https://lh4.googleusercontent.com/Y84UK9tFa0hvecoYQZEDH5HX427pt5hwdiOVXI8_8kBnHduqmetczRisF2_mPFx72tamfGL7N-RHuyCU1BeR4kJtYrsMXzTva4bOyYb_kMnji9t7pzsKKiCzplOYN9cf9w=s0" width="850">

Kembali ke browser, lalu menuju **[](http://aku.pengen.pw/) [basic.ichimarumaru.tech](http://basic.ichimarumaru.tech/)**. Masukkan *username* dan *password*-nya. Akan muncul laman seperti di bawah.

<img src="https://lh3.googleusercontent.com/EKBv_HtMx1dFpu6h9Ajrfn3PQ1epQ1RCWz7gmg42M3nPS6t2g1km5i4rdDHJgtSGdKp7lzHoZcPbVt_CjYspD8_T5vj5lWModRQZ_naDIBdCKS0DSXuWLTUXwACah8QeJA=s0" width="850">

Jawab soal yang ada di laman tersebut. Jawabannya adalah '**putih-hijau, hijau, putih-oranye, biru, putih-biru, oranye, putih-cokelat, cokelat**'.

## Soal 4

### Temukan paket mysql yang mengandung perintah query select!

### Jawaban:

Mengisi *display filter* dengan ``mysql.query contains select || mysql.query contains SELECT``.

<img src="https://lh5.googleusercontent.com/dLSkKIt8RV3TnygL8bUFQ1BRDOnhhtdTObdIncyie0tGVzoNb0vkN1NKdwrwc859UaUWTrBi8kVnwofahiyoORmWhgVCh5U9HtJ7BhLn0xrFrbHptEWxpfyBVABy-Yo60am4v0sJ=s0" width="850">

Akan muncul paket yang mengandung perintah *query* **select**.

## Soal 5

### Login ke [portal.ichimarumaru.tech](http://portal.ichimarumaru.tech/) kemudian ikuti perintahnya! Username dan password bisa didapat dari query insert pada table users dari file .pcap!

### Jawaban:

Mengisi *display filter* dengan ``mysql.query``.

<img src="https://lh6.googleusercontent.com/OUZQHFF8yW3XoIHLIZonNy6-Rgfx5nfeXqJZtR9d2PWuI6-ocltKrb2CvZjSw5H65jBiusAJ8ptXHYOZ79Yl8gUYdGw-TT_6_R0O0WLgmrQbYmi34qHsukwSwOF5gLLHVw=s0" width="850">

Akan muncul *query* **insert** yang berisi:
-   **Username  : akakanomi**
-   **Password  : pemisah4lautan**

Masukkan *username* dan *password*-nya.

<img src="https://lh3.googleusercontent.com/BY1KfJ-9w2iP5NJIU_YZeQa-GpBr-tAONAp6t5NJlStIwNkVSkHhbPygJb66HOJHszKTK4RKASBQQMhLgGiAsnfzVnGtTjw50_OmxtvwqseLm6vVHCZXrJvHXr-kaVOa4g=s0" width="850">

Kemudian, akan muncul laman seperti ini dan bisa dijawab soal yang ada.

<img src="https://lh6.googleusercontent.com/VxGSC6flwkSqtHySF7hYh41M9vcI5F2I-ySUuelK8zzJEemW9Feqp8DKNasRPFKzFUyBk1V3-KmcTb1D2RC7JtBWTjggfcw4iV6F7AiyZHOq_ysQwpJjLGQOV0Cq2Qg0_g=s0" width="850">

Jawabannya adalah '**putih-oranye, oranye, putih-hijau, biru, putih-biru, hijau, putih-cokelat, cokelat**'.

## Soal 6

### Cari username dan password ketika melakukan login ke FTP Server!

### Jawaban:

Mengisi *display filter* dengan ``ftp.request.command == USER || ftp.request.command == PASS``.

<img src="https://lh3.googleusercontent.com/02edDq4m9ktG5-mNdS2rzxO4VkOiVTvV9ZeW0tuYDEpax2uw_68yM829IlrbIZBiN8HbRAgdkSsVGRp_SdKo0P5KUCGixedso2cmPjvBLztpjCt-4jKVbcgJKLg6FFgBicJIhxE3=s0" width="850">

Akan muncul daftar *username* dan *password* yang *login* ke FTP Server.

## Soal 7

### Ada 500 file zip yang disimpan ke FTP Server dengan nama 0.zip, 1.zip, 2.zip, ..., 499.zip. Simpan dan Buka file pdf tersebut. (Hint = nama pdf-nya "Real.pdf")

### Jawaban:

Mengisi *display filter* dengan ``ftp-data and frame contains "Real.pdf"``.

<img src="https://lh4.googleusercontent.com/Fa8fNtZjC_dnxN4bX5EHlbfP0w0Wrf_ZXuTngEOgCUIrHXgRG-fP_s85srcIENJIwpSD8OMibS57UEBjQs9CieFY8iGJYwu6kvMREjQvl9Kqv-3g3gE6FgXD9d020NqsbbAi9RQL=s0" width="850">

Follow TCP Stream dan ubah data dari **ASCII** menjadi **RAW**.

<img src="https://lh3.googleusercontent.com/_r5bTwUBQn-ai_RX9su6xTmDBlgN21tLl883_mEycXBmb0MuljsyLrkMVVReNUpGA749ospW5NSGk6ioeV9KzdMOEpo8yimDZJSLxoZEaD4-qkkYJonJsQbr6DXGzJDzeBkBylKt=s0" width="850">

Simpan data sebagai **.zip**.

<img src="https://lh3.googleusercontent.com/8K-IIPKC8NIKABkr8dJwckttxpsmOrHMbiuveqToSZ7vpxbGsg86F9qDXHop-6gvKWY3Lct1-SL1cZO9_kJHpz_Y8FOFwdcGZniSW-eAZMUe4kqu676ZxjN99j4eOiz3sJ52x8AO=s0" width="850">

Ekstrak **.zip** tadi dan buka '**Real.pdf**'.

<img src="https://lh3.googleusercontent.com/FvxwTK6Xftiq20Ymj3kEpQydaUNnDaKnqAQSYODbDwW9GSnzy2CN_sA3qeey_tQhn6Xf8yxBsF-22YBe0r2eoSdzlu4bbuUrB5pzXWh85pRd16iZrVM_WeObPxGCG0GHpWsg2rJD=s0" width="850">

Hasilnya akan muncul seperti ini.

## Soal 8

### Cari paket yang menunjukan pengambilan file dari FTP tersebut!

### Jawaban:

Mengisi *display filter* dengan ``ftp-data.command == RETR``.

<img src="https://lh4.googleusercontent.com/Hkrj3uKhrvRjycbnDD2qzP7tNtkzkz6w_vhvPiVUY3Vz-ZwRLKXxDmnMjq6wJje_wNPoOitxSlLWWpFZjta62FW1rwgq83PHYr7UCQzD4dCB-K0OEGe1GxvRZME8eQCQpcXJK9Dv=s0" width="850">

Seharusnya muncul daftar paket untuk pengambilan file dari FTP. Tapi di sini karena tidak ada, maka tidak muncul.

## Soal 9

### Dari paket-paket yang menuju FTP terdapat inidkasi penyimpanan beberapa file. Salah satunya adalah sebuah file berisi data rahasia dengan nama "secret.zip". Simpan dan buka file tersebut!

### Jawaban:

Mengisi *display filter* dengan ``ftp-data and ftp-data.command contains "secret.zip"``.

<img src="https://lh4.googleusercontent.com/jfo-7woJz6asoahOn9YJ2IV-jQjJy-HmkwwE1jKOQ3CCiswwCr-dGoNeM1vkT5-SjQyi_hFf6LDM6GVvv-O1KWmUPd6LorL6aD1TrVc23nwE7L2GRHqHogMDD7EpP4Ep6IK6tXXb=s0" width="850">

Follow TCP Stream dan ubah data dari **ASCII** menjadi **RAW**.

<img src="https://lh4.googleusercontent.com/-nVAggqadiwQBUPUbK6b8Xp5fP3T3Wr8EEq3exTcA6-PN5lUKOjHO1OULnRpeSz5ycvZiHF9hRtIaskthEzE6pJC3NEg3nZs7oTQEDgofkTm8E1nnr6hj2UvzbG0DDsAq4TDdq-X=s0" width="850">

Simpan data sebagai **.zip**. Setelah di-*zip* kita tidak akan bisa mengekstraknya karena terdapat *password*. *Password zip* ini ada di **nomor 10**.

Beginilah isi **.pdf** jika sudah mendapatkan *password zip*.

<img src="https://lh6.googleusercontent.com/QqaftC_QgofPySfesPkj0f4l_HkxvH_59hi1W74elyu-E_RALY5xPrwkz4umMsWqKi3MJuGxiC8jE_DM3EpzVi8p7aNnWMMpPVdbmxjHOa5yVcb4IyVNuf9seX_elUfXUCmyKkO_=s0" width="850">

## Soal 10

### Selain itu terdapat "history.txt" yang kemungkinan berisi history bash server tersebut! Gunakan isi dari "history.txt" untuk menemukan password untuk membuka file rahasia yang ada di "secret.zip"!

### Jawaban:

Mengisi *display filter* dengan ``ftp-data.command contains "history.txt"``.

<img src="https://lh3.googleusercontent.com/gkEST3pgsVJwmP1qevhnmCP9VNDjOzjfrMfant13rXrVr8AoclBwf-f3-7hui6QEThJ3AYnuA5XORNG15fZ4oLE4hjDTZfGd1dmSZXKbGW-1yNw9ow-yprVOmHH7uHyuVpoeQlSP=s0" width="850">

Follow TCP Stream. Kemudian akan muncul seperti ini. Dari sini kita bisa lihat bahwa *password* ada di **bukanapaapa.txt**.

<img src="https://lh6.googleusercontent.com/z_ZfeWbfNrsr8ZnCeNlWJAGf0_19zrOFA_MoTjMkN6oSRTdjadfuRDPrenTk3h6S5cevx_ODVnJZd3i1at-bEQ3-KUHaH2awSSmW76qf2LWBVlFzaw0DC3M7ENTH82VW3rV64M9I=s0" width="850">

Mengisi *display filter* lagi dengan ``ftp-data.command contains "bukanapapa.txt"``.

<img src="https://lh3.googleusercontent.com/mby2n-lTKePIw_H2UwAH87wJautayHMZxql3SmlsNUvgqf0KKNiiLaQGZlDGxRirZ0olaOk8mquT1WLMQrrMMBAtha7bHjDTXzCZ0VbVADtM4DA9Dib0ngzaujVvfo7EF3iM0MRF=s0" width="850">

Follow TCP Stream. Kemudian akan muncul seperti ini. Dari sini kita bisa lihat bahwa *password* adalah **dibilangbukanapaapajugagapercaya**. *Password* ini digunakan untuk membuka *zip* **nomor 9**.

<img src="https://lh4.googleusercontent.com/X_EYuClcvyFeiIWFIt5nVRZpb88FPOH4fr9-W7FpAtDC4NO8_Kuorj12wm2pdDsq6nkHRjivgCFkPyS1RvLoOYp3pJtc0OAaMftR6b_RGasVCiP_VlxUW0MHZmuAPlDeyXDTKynu=s0" width="850">

## Soal 11

### Filter sehingga wireshark hanya mengambil paket yang berasal dari port 80!

### Jawaban:

Mengisi *capture filter* dengan ``src port 80``.

<img src="https://lh5.googleusercontent.com/hUOrSzoUN9blEmv2pfzeUwjaPyzfZZPVs6zJA6W-aMCZXklpL7IbfEujE3LEfis_UWUog9yMlTfjYV3usPVhmdW48iuqABtjvQWndoulY16fjTeVLS-Y5D1GWKjYvNNLAKYD33PG=s0" width="850">

Hasil ketika mengambil paket dari **port 80**.

<img src="https://lh3.googleusercontent.com/vaEO3aXkNU6SET8YBNRM2vvlIpJhu-wpj4sO9x6hKn_ZzZyKM7Ird-gnH8xm_Lni__S4XsawyJLJ7LGxuvnytFEyHaYT3DXDhJyZqsAl932mwccqelQRsUCmmWEdVwGiY892nrOR=s0" width="850">

## Soal 12

### Filter sehingga wireshark hanya mengambil paket yang mengandung port 21!

### Jawaban:

Mengisi *capture filter* dengan ``port 21``. Berbeda dengan biasanya yang memakai **Wi-Fi**, di sini menggunakan **Adapter for Loopback Traffic Capture**.

<img src="https://lh5.googleusercontent.com/rWxCzE9mQGlpN5TiUVnZIU9P7PrjdDcbHkWQTbrh-LvCCPDL63yVxgEiwinkj3AGKgCfFobBe4tfNxUECapz-UuPgmPJ3w6DHq0fKRl_yvtWwyGl1yZO55t14_bYF-G-njZJN1Xi=s0" width="850">

Hasil ketika mencari paket mengandung **port 21**. Di sini tidak ada yang dimunculkan karena harus menggunakan FTP. Bisa memakai **FileZilla** untuk mengujicoba.

<img src="https://lh6.googleusercontent.com/WfqFbOnjOte6up10ekWVGvTuF9dUidwo_cvPKDp83ojjyxfwUkv7tgEscEeUgtSiCCLD0UEC7qHhPAKBLztP-JqRTEvi7W420ZhUDxAEVRJmmsycdVBNDdYYeR9AZJcw82f6VSRw=s0" width="850">

Buka **XAMPP** dan *connect*-kan **FileZilla**. Kemudian akan muncul seperti ini.

<img src="https://lh3.googleusercontent.com/xFSU9AkQvtSfGx6Musdob_1DOHeehlj0OXfTWLSFoX8KsRaCn0YwPOYjDb7uJy0q3a0RxtX6jvRRY__MVpNlXSadPvW2r8o1XJyUY9L1MWCecRQROvpwDMawrtCaD7rQr6N1cmch=s0" width="850">

## Soal 13

### Filter sehingga wireshark hanya menampilkan paket yang menuju port 443!

### Jawaban:

Mengisi *capture filter* dengan ``dst port 443``.

<img src="https://lh5.googleusercontent.com/FN2ajb6ZiP1LU3gW3_9ulJ5COR8LHq825CDqwd8REXk5znIsbGXbMFn_36KA7J90J3K27cC5V3U-B2luxkFCkTmmEdcZx6ImBSUvuJATg_CPRiYYnMYU_B6_pGf2VhI2fpAjLkmO=s0" width="850">

Hasil ketika menampilkan paket menuju **port 443**.

<img src="https://lh3.googleusercontent.com/i4wjZgzO1cbuZMS6_pvCVohkV7UmoLpMtJ-FFjdHkYdM1MQHJ1AXyeuEHhQ96cn9lTjT0X1GdomJsSupzytgh5ks0sgF2Q2N1pjrIJt9e9R_U1SOXg0gCXVYLLhrPaP40d60afTb=s0" width="850">

## Soal 14

### Filter sehingga wireshark hanya mengambil paket yang tujuannya ke kemenag.go.id!

### Jawaban:

Mengisi *capture filter* dengan ``dst host kemenag.go.id``.

<img src="https://lh4.googleusercontent.com/k4APuQNkHtmYRxgqSwNu2glW8OS62llecp49r2Q4g1il9gyddWX1MDGpZXnDhraMUYhVLcpfmYS7wiIutc_3PIdSRqwkCW-eyHiKtwckONGr6VLRyqmE-F2-v_6HWVovj22k1mP-=s0" width="850">
    
Hasil ketika menampilkan paket yang tujuannya **kemenag.go.id**.

<img src="https://lh5.googleusercontent.com/hDlI7dVA8OgWTAhLg18px3G137_NRwj1zsi704z5lDZW-YvZPCTLwYL8OJEWsAXZRHyaS18DIcdOmRYAWUGqbBZLeexEwFp00nwOkv_EMrsJ5-W3dedZ-nqS3nfCVoHIauMrPztf=s0" width="850">

## Soal 15

### Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!

### Jawaban:

Cari IP Address masing-masing lewat *command prompt*. Kemudian, mengisi *display filter* dengan ``ip.src == [ip masing-masing]``.

<img src="https://lh4.googleusercontent.com/44Ifx3KwaoGBaYBstA8YGHlFp2-txT3oVzqep9FoaIlTDejCU1LFgJistk4TVWW6YYnx_7X4-DJmhWUGvabPh04YHBUR_Y0BxfNz5BUfHHUxtMqMji6NI9jWp1CezvLDfssaz54y=s0" width="850">

## Kendala
- Jaringan agak lemot sewaktu men-*download file* praktikum.
- Masih agak bingung penggunaan *command* dari Wireshark.
