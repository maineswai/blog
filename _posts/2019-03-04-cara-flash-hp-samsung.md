---
layout: single
title:  "Cara Flash HP Samsung Galaxy J2 (SM-J200G) Via Odin"
date:   2019-03-04 16:00:00 +0700
permalink: /:title
description: "Tutorial lengkap step by step cara flash hp android Samsung Galaxy J2 (SM-J200G) dengan menggunakan Odin di Laptop."
excerpt: "Tutorial lengkap step by step cara flash hp android Samsung Galaxy J2 (SM-J200G) dengan menggunakan Odin di Laptop."
header:
  image: /assets/images/flash-samsung-j200g.png
  caption: "Photo credit: [**Thumbnaily**](https://thumbnaily.site)"
toc: true
toc_label: "Daftar Isi"
toc_icon: "cog"
toc_sticky: true
categories: 
    - tutorial
    - android
tags : 
    - flash 
    - samsung
    - sm-j200g
    - laptop
    - odin
---
### Alasan kenapa hp samsung perlu di flash
Melakukan flash hp samsung galaxy ataupun hp android lainnya pastinya dilakukan karena beberapa alasan. Diantara beberapa alasan tersebut yaitu, hp sering mengalami error atau lambannya proses respon dari hp tersebut hingga menginginkan mendapat versi terbaru dari Android. Alasan itulah yang masih menjadi faktor kenapa para pengguna hp, terutama pengguna hp samsung ingin melakukan flash.

> Menurut gambaran sederhana dari saya sendiri itu, `flash` hampir sama seperti kita melakukan install ulang pada komputer atau laptop, namun kali ini dilakukan pada handphone.

#### Flash dapat menghapus seluruh data ?
<sub>**Note:** Saat melakukan flashing akan menghapus seluruh data-data dan aplikasi yang tersimpan atau terinstall pada perangkat android. Alangkah baiknya, lakukanlah backup atau memindakan data atau file-file penting ke media lain.</sub>

Kali ini saya akan memberikan sebuah tutorial atau cara flash hp samsung. Saya sendiri disini menggunakan **Samsung Galaxy J2** dengan model number **SM-J200G** dengan menggunakan `Odin`.

### Cara mengetahui tipe handphone dan nomor model hp samsung
Sangat penting mengetahui tipe handphone dan model nomor, karena jika salah maka akan berakibat gagalnya `flashing`. Lalu bagaimana cara mengetahui tipe hp dan model number hp samsung ?

1.	Pertama kalian klik ikon setting atau pengaturan.
2.	Lalu scroll atau gulirkan layar kebawah dan terdapat menu atau tulisan **"About Device"** atau **"Tentang Perangkat"**, silahkan kalian klik. 
    <figure>
    <img src="/assets/images/flash-samsung-j200g/12.jpg" alt="About device">
    <figcaption>About device.</figcaption>
    </figure>
3.	Akan terdapat _**device name**_ dan _**model number**_, silahkan kalian ingat atau catat karena ini perlu untuk mendownload firmwarenya
Jika sudah mengetahui 2 hal penting diatas, langkah selanjutnya adalah teman-teman harus memiliki komputer atau laptop, karena cara flash hp samsung ini dilakukan di komputer/laptop.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/13.jpg" alt="Device name & model number">
    <figcaption>Device name & model number.</figcaption>
    </figure>

#### Bahan yang diperlukan untuk flash hp samsung
1.	Yang pertama kalian butuhkan adalah firmware, nah untuk mendownload firmware ini kalian harus sesuaikan dengan tipe dan model number. Cara termudahnya adalah silahkan kalian ketikan di google **"firmware samsung sm-j200g"** silahkan sesuaikan atau ganti dengan model number hp samsung kalian, atau bisa dengan cara mengunjungi situs [https://www.sammobile.com/firmwares/](https://www.sammobile.com/firmwares/) lalu masukan model number hp kalian.

    <sub>**Note:** (Sebelum mendownload firmwarenya, diharapkan kalian daftar dahulu di web tersebut. Karena _firmware_ tidak akan bisa di download jika kita belum mendaftar pada situs tersebut).</sub>

    <figure>
    <img src="/assets/images/flash-samsung-j200g/21.png" alt="Mencari firmware hp samsung">
    <figcaption>Mencari firmware hp samsung.</figcaption>
    </figure>
2.	Kemudian dibagian **select country** kalian pilih <kbd>indonesia</kbd>, dan klik di versi terbarunya.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/22.png" alt="Firmware samsung j2 terbaru">
    <figcaption>Firmware samsung j2 terbaru.</figcaption>
    </figure>
3.	Lalu klik tombol <kbd>wait & download</kbd>. 

    <sub>**Note:** (sebelum klik, pastikan kalian sudah login di web tersebut), akan muncul pop-up dan menunggu waktu sekitar 15 detik dan tombol download baru akan muncul. Lalu klik download.</sub>

    <figure>
    <img src="/assets/images/flash-samsung-j200g/23.png" alt="Download firmware">
    <figcaption>Download firmware.</figcaption>
    </figure>

4.	Setelah itu yang perlukan selanjutnya adalah `Odin`, masih dihalaman yang sama silahkan kalian klik download odin.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/24.png" alt="Download odin">
    <figcaption>Download odin.</figcaption>
    </figure>
5.	Jika firmware samsung dan odin selesai didownload, silahkan kalian ekstrak.

### Tutorial cara flash hp samsung
Kali ini kita masuk kebagian terpentingnya, silahkan ikuti caranya dibawah ini.
1.	Silahkan kalian buka software atau aplikasi odin yang sudah di download tadi.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/31.png" alt="Aplikasi odin versi terbaru">
    <figcaption>Aplikasi odin versi terbaru.</figcaption>
    </figure>
2.	Posisi hp sumsung dalam keadaan mati, silakan kalian tekan tombol volume <kbd>-</kbd> , tombol kunci layar dan tombol home secara bersamaan, disini akan tampil layarbiru (saya lupa foto), kemudian kalian tekan tombol volume <kbd>+</kbd>, maka akan tampil seperti dibawah ini.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/32.jpg" alt="Tampilan layar biru">
    <figcaption>Tampilan layar biru.</figcaption>
    </figure>
3.	Hubungkan hp samsung kalian ke komputer/pc/laptop dengan kabel usb.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/33.jpg" alt="Hubungkan hp samsung ke laptop">
    <figcaption>Hubungkan hp samsung ke laptop.</figcaption>
    </figure>
4.	Jika hp sudah terhubung dengn laptop dan aplikasi odin maka akan tampil seperti dibawah.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/34.png" alt="Hp terhubung di odin">
    <figcaption>Hp terhubung di odin.</figcaption>
    </figure>
5.	Kemudian kalian klik _**AP**_ dan kalian pilih firmware yang sudah kalian download tadi.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/35.png" alt="Proses odin mengecek firmware">
    <figcaption>Proses odin mengecek firmware.</figcaption>
    </figure>
6.	Setelah itu pengecekan selesai kalian klik tombol start, maka proses flashing hp samsung pun sedang berlangsung ditandai dengan loading warna hijau diatas.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/36.png" alt="Start odin">
    <figcaption>Start odin.</figcaption>
    </figure>
7.	Berikut ini proses flashing yang sedang berjalan, mohon untuk tidak mencabut kabel usb ketika flash masih berjalan.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/37.jpg" alt="Proses flashing pada hp samsung">
    <figcaption>Proses flashing pada hp samsung.</figcaption>
    </figure>
8.	Proses flash pada odin selesai ditandai dengan tulisan _**PASS**_ diatas.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/38.png" alt="Proses flash sudah selesai">
    <figcaption>Proses flash sudah selesai.</figcaption>
    </figure>
9.	Jangan dicabut terlebih dahulu kabel datanya karena proses install android sedang berjalan.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/39.jpg" alt="Proses install sistem android di hp samsung">
    <figcaption>Proses install sistem android di hp samsung.</figcaption>
    </figure>
10.	Jika samsung sudah selesai maka akan ditandai dengan proses pemilihan bahasa, silahkan kalian lepas kabel data dan kalian tutup odin.
11.	Langkah terakhir adalah kalian setting android pada hp samsung seperti atur jam, tanggal, login email google dan seterusnya.
12.	Flash hp samsung selesai, maka akan tampil layar home samsung beserta aplikasi default bawaannya sama seperti saat membeli hp baru.
    <figure>
    <img src="/assets/images/flash-samsung-j200g/312.jpg" alt="Tampilan home samsung">
    <figcaption>Tampilan home samsung.</figcaption>
    </figure>

#### Kenapa gagal flashing HP Samsung J2 (SM-J200G) ?
Beberapa kendala yang mungkin terjadi saat flash hp samsung diantaranya hp samsung tidak terhubung dengan software atau aplikasi odin.




