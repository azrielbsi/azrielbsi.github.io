---
title: "Mengenal Topologi Jaringan Komputer"
author_profile: false
excerpt: "Penjelasan mengenai **Topologi** menjelaskan **kelebihan** dan **kekurangan** topologi."
breadcrumbs: true
header:
  teaser: "/assets/images/teaser/topologi-jaringan.jpg"
  overlay_image: /assets/images/header/apple-eye.jpg
  overlay_filter: 0.5
last_modified_at: 2023-10-20T:00:00-01:00
categories:
  - Learn
tags:
  - Tugas
  - BSI
  - Jaringan Komputer
toc: true
toc_sticky: true
comments: true
---

# Pengertian Topologi Jaringan
Topologi jaringan komputer adalah metode atau cara yang digunakan agar bisa menghubungkan satu komputer dengan komputer lainnya. Struktur atau jaringan yang digunakan untuk menghubungkan satu komputer dengan komputer lainnya bisa dengan menggunakan kabel atau pun nirkabel (tanpa kabel).

# Fungsi Topologi Jaringan Komputer
Topologi jaringan komputer berfungsi untuk mengetahui bagaimana masing-masing komputer atau host dalam jaringan komputer dapat saling berkomunikasi satu sama lain.

# Jenis-Jenis Topologi Jaringan Komputer Beserta Kelebihan dan Kekurangannya

## 1. Topologi Ring (Cincin):

<figure style="width: 500px height: 300px" class="align-center">
  <img src="https://github.com/azrielbsi/azrielbsi.github.io/assets/126305178/5bbd6ce2-7b73-49cb-8bdc-12703eed3dd9" alt="ring">
</figure> 

Topologi Ring adalah jenis topologi jaringan komputer di mana setiap perangkat terhubung dengan dua perangkat lainnya, membentuk sebuah cincin tertutup. Data mengalir melalui cincin dari satu perangkat ke perangkat berikutnya dalam satu arah. Umumnya, jenis topologi ini menggunakan LAN card agar masing-masing komputer terkoneksi.

### Kelebihan Topologi Ring:
- Biaya instalasi biasanya murah karena jumlah kabel yang diperlukan relatif sedikit.
- Performa koneksi dalam topologi ini cukup baik karena data mengalir dalam satu arah.
- Proses instalasi dan konfigurasi cenderung mudah dilakukan.
- Implementasi topologi ini mudah dan cepat dilakukan.

### Kekurangan Topologi Ring:
- Jika terjadi masalah pada salah satu perangkat atau kabel, troubleshooting jaringan ini terbilang rumit karena seluruh cincin dapat terganggu.
- Topologi ring sangat rentan terhadap tabrakan arus data, yang dapat memperlambat atau mengganggu komunikasi.
- Jika salah satu koneksi dalam cincin mengalami masalah atau terputus, maka koneksi pada seluruh jaringan ring akan terputus.

## 2. Topologi Bus:

<figure style="width: 500px height: 300px" class="align-center">
  <img src="https://github.com/azrielbsi/azrielbsi.github.io/assets/126305178/03af4bfc-873a-453f-bfc4-c0b2fc4017b9" alt="bus">
</figure> 

Topologi Bus adalah jenis topologi jaringan komputer yang lebih sederhana, di mana perangkat-perangkat dalam jaringan terhubung ke satu kabel utama atau "bus". Setiap perangkat terhubung langsung ke bus, dan data dikirimkan ke seluruh jaringan, tetapi hanya perangkat yang dituju yang akan merespons dan menerima data. Biasanya, topologi bus digunakan dalam jaringan berbasis kabel coaxial.

### Kelebihan Topologi Bus:
- Penambahan perangkat client atau workstation baru relatif mudah dan murah dilakukan.
- Topologi ini mudah digunakan dan sangat sederhana, sehingga tidak memerlukan perangkat pusat yang mahal.
- Biaya instalasi rendah karena penggunaan kabel yang sedikit.

### Kekurangan Topologi Bus:
- Sering terjadi tabrakan arus data, terutama dalam jaringan yang padat, yang dapat mengganggu komunikasi.
- Proses pengiriman dan penerimaan data cenderung kurang efisien dibandingkan dengan topologi lain.
- Topologi bus yang lama sulit untuk dikembangkan jika jumlah perangkat atau panjang jaringan perlu diperluas.
- Jika ada masalah pada kabel, seperti putus atau gangguan, maka seluruh komputer atau workstation dalam jaringan tersebut dapat terganggu atau kehilangan koneksi.

## 3. Topologi Mesh:

<figure style="width: 500px height: 300px" class="align-center">
  <img src="https://github.com/azrielbsi/azrielbsi.github.io/assets/126305178/e56ba934-3747-4cab-b2b5-bbc250de5735" alt="mesh">
</figure>

Topologi Mesh adalah jenis topologi jaringan komputer di mana setiap perangkat terhubung langsung ke setiap perangkat lain dalam jaringan. Ini berarti ada banyak jalur yang berbeda untuk mengirim data dari satu perangkat ke perangkat lain. Dalam topologi ini, tidak ada perangkat pusat seperti hub atau switch. Jaringan mesh sering digunakan dalam aplikasi yang memerlukan keandalan tinggi dan keamanan data.

### Kelebihan Topologi Mesh:
- Bandwidth atau kapasitas jaringan sangat besar karena banyak jalur yang tersedia.
- Keamanan data pada topologi ini sangat baik karena data dapat mengalir melalui jalur yang berbeda.
- Tidak terjadi tabrakan arus data karena ada banyak jalur pengiriman data, yang meningkatkan efisiensi.
- Kemungkinan terjadinya kegagalan atau putusnya koneksi lebih rendah karena redundansi yang tinggi.
  
### Kekurangan Topologi Mesh:
- Membutuhkan banyak kabel untuk menghubungkan setiap perangkat dengan yang lain, sehingga biaya instalasi menjadi tinggi.
- Proses instalasi topologi mesh dapat sangat rumit karena harus menghubungkan banyak perangkat satu sama lain.
- Perlu manajemen yang baik untuk mengelola semua koneksi dalam jaringan mesh yang besar.
- Instalasi dan pemeliharaan cenderung mahal karena biaya kabel dan konfigurasi yang rumit.

## 4. Topologi Star (Bintang):

<figure style="width: 500px height: 300px" class="align-center">
  <img src="https://github.com/azrielbsi/azrielbsi.github.io/assets/126305178/4aa678bc-ed6a-4fb9-8d0e-5595b7d1d7f3" alt="star">
</figure>

Topologi Star adalah jenis topologi jaringan komputer di mana setiap perangkat terhubung ke satu titik pusat, yang bisa berupa hub atau switch. Dalam topologi ini, semua komunikasi antara perangkat harus melalui titik pusat tersebut. Topologi bintang umum digunakan dalam jaringan kantor, dan itu adalah salah satu topologi yang paling umum digunakan.

### Kelebihan Topologi Star:
- Jaringan dalam topologi ini tetap berjalan baik meskipun satu komputer client mengalami masalah atau terputus, karena masalah di satu perangkat tidak mempengaruhi perangkat lain.
- Tingkat keamanan data pada topologi ini cukup baik karena data hanya mengalir melalui hub atau switch, yang dapat dimonitor dan diatur dengan mudah.
- User lebih mudah mendeteksi masalah pada jaringan karena ketika ada masalah dengan koneksi, biasanya terkait dengan perangkat yang terhubung langsung ke titik pusat.

### Kekurangan Topologi Star:
- Topologi ini terhitung mahal karena mengharuskan penggunaan cukup banyak kabel, terutama jika jumlah perangkat yang terhubung sangat besar.
- Seluruh komputer dalam jaringan ini akan bermasalah jika hub atau switch mengalami masalah atau mati.
- Kinerja jaringan dapat dipengaruhi oleh kinerja hub atau switch pusat, sehingga jaringan ini sangat tergantung pada terminal pusat.

## 5. Topologi Tree (Pohon):

<figure style="width: 500px height: 300px" class="align-center">
  <img src="https://github.com/azrielbsi/azrielbsi.github.io/assets/126305178/e3650b35-a950-447f-b5f6-0344638572a0" alt="tree">
</figure>

Topologi Tree, juga dikenal sebagai Topologi Pohon, adalah jenis topologi jaringan komputer yang menggabungkan elemen dari topologi Bus (pohon bintang) dan topologi Star (bintang). Dalam topologi ini, beberapa pohon bintang terhubung ke satu pohon bus atau rangkaian pusat. Ini digunakan untuk menghubungkan berbagai hirarki dengan pusat yang berbeda-beda.

### Kelebihan Topologi Tree:
- Dapat dan mudah dikembangkan menjadi topologi jaringan yang lebih luas karena memiliki struktur hierarki yang dapat diulang.
- Susunan topologi ini terpusat secara hirarki, yang membuat pengaturan data lebih mudah dan terstruktur.
- Keamanan data pada topologi ini cukup baik, terutama jika pohon bintang memiliki kontrol akses yang tepat.

### Kekurangan Topologi Tree:
- Memiliki kinerja jaringan yang lambat karena data harus mengalir melalui jalur hirarki yang lebih tinggi.
- Penggunaan kabel yang sangat banyak menyebabkan biaya instalasi tinggi, terutama jika jaringan sangat luas.
- Kabel backbone, yang merupakan jalur pusat, bisa menjadi titik kegagalan potensial, sehingga jika ada masalah dengan kabel tersebut, seluruh bagian jaringan terkait juga akan terganggu.

## 6. Topologi Peer to Peer:

<figure class="align-center">
  <img src="https://github.com/azrielbsi/azrielbsi.github.io/assets/126305178/b897c5f5-a154-4a54-9107-5cf063ef12f7" alt="peer">
</figure>

Topologi Peer to Peer (P2P) adalah jenis topologi jaringan komputer yang sangat sederhana di mana setiap perangkat dalam jaringan dianggap setara. Dalam topologi ini, setiap perangkat berfungsi sebagai klien dan server secara bersamaan. Perangkat dapat berkomunikasi langsung satu sama lain tanpa harus melalui server pusat. Topologi P2P umumnya digunakan dalam jaringan kecil, seperti berbagi file antara komputer rumah.

### Kelebihan Topologi Peer to Peer:
- Biaya instalasi sangat murah karena tidak memerlukan perangkat pusat seperti server.
- Proses instalasi sederhana dan tidak memerlukan perangkat tambahan yang mahal.
- Setiap perangkat dalam jaringan dapat berperan sebagai server dan mengakses sumber daya yang dimiliki oleh perangkat lain.
- Topologi ini cocok untuk jaringan kecil dengan sedikit perangkat.

### Kekurangan Topologi Peer to Peer:
- Sangat sulit untuk dikembangkan menjadi jaringan yang lebih besar dan kompleks.
- Keamanan dalam topologi ini sering bermasalah karena perangkat berkomunikasi langsung satu sama lain, sehingga lebih rentan terhadap risiko keamanan.
- Proses troubleshooting (perbaikan masalah) seringkali rumit karena setiap perangkat bertanggung jawab atas fungsinya sendiri.
- Ketika jaringan tumbuh, manajemen perangkat dalam topologi P2P menjadi semakin sulit dan tidak efisien.

## 7. Topologi Linier (Bus Berurut):

<figure class="align-center">
  <img src="https://github.com/azrielbsi/azrielbsi.github.io/assets/126305178/60e2e105-7c34-43cb-a09a-160b79822258" alt="linier">
</figure>

Topologi Linier, atau yang juga dikenal sebagai Bus Berurut, adalah jenis topologi jaringan komputer yang menghubungkan perangkat dalam satu garis linear tunggal. Setiap perangkat terhubung dengan satu kabel utama dan data mengalir melalui garis tersebut dari satu perangkat ke perangkat berikutnya. Topologi ini sering digunakan dalam jaringan kabel koaksial lama, meskipun sekarang semakin jarang ditemui.

### Kelebihan Topologi Linier:
- Mudah dikembangkan dengan menambahkan perangkat baru ke garis utama.
- Penggunaan kabel sedikit, sehingga biaya instalasi relatif rendah.
- Tata letak topologi linier sederhana dan mudah dipahami.
- Tidak memerlukan kendali sentral seperti hub atau switch.

### Kekurangan Topologi Linier:
- Kepadatan lalu lintas data dapat tinggi, terutama jika jaringan padat, yang dapat mempengaruhi kinerja.
- Keamanan data dalam topologi ini tidak terjamin karena data dapat dengan mudah diakses oleh semua perangkat dalam jaringan.
- Jika terjadi masalah pada kabel utama, seperti putus, maka semua komputer atau perangkat dalam jaringan akan terganggu atau kehilangan koneksi.
- Topologi linier tidak cocok untuk jaringan yang kompleks atau besar karena dapat sulit untuk mengelola ketika jaringan berkembang.

## 8. Topologi Hybrid:

<figure style="width: 500px height: 300px" class="align-center">
  <img src="https://github.com/azrielbsi/azrielbsi.github.io/assets/126305178/ea2325ba-47be-48a1-833c-197f166ff1f0" alt="Hybrid">
</figure>

Topologi Hybrid adalah jenis topologi jaringan komputer yang merupakan gabungan dari dua atau lebih topologi yang berbeda, yang membentuk satu jaringan yang lebih besar dan kompleks. Dalam topologi hybrid, berbagai elemen topologi digabungkan untuk memenuhi kebutuhan khusus dan tuntutan jaringan yang lebih kompleks. Misalnya, jaringan dengan beberapa cabang kantor dapat menggunakan topologi bintang di setiap kantor cabang, tetapi terhubung melalui topologi mesh atau topologi pohon secara keseluruhan.

### Kelebihan Topologi Hybrid:
- Fleksibel dan dapat disesuaikan dengan kebutuhan spesifik jaringan.
- Penambahan koneksi atau cabang baru pada topologi ini bisa dilakukan dengan relatif mudah.
- Dapat mengoptimalkan kelebihan dari berbagai jenis topologi, seperti keamanan dari topologi bintang, atau redundansi dari topologi mesh.
- Cocok untuk jaringan yang kompleks dan berukuran besar dengan berbagai persyaratan berbeda.

### Kekurangan Topologi Hybrid:
- Proses instalasi dan pengaturannya bisa rumit, terutama jika melibatkan banyak jenis topologi yang berbeda.
- Manajemen topologi hybrid sangat sulit dilakukan karena perlu memahami dan mengelola berbagai jenis topologi yang digunakan.
- Biaya untuk membuat topologi ini bisa cukup mahal, terutama jika melibatkan peralatan dan infrastruktur yang beragam.
- Kelemahan salah satu jenis topologi dalam hybrid dapat memengaruhi seluruh jaringan jika tidak dikelola dengan baik.
  
## Kelompok 3 Kelas: 19.A4.07

![image](https://github.com/azrielbsi/azrielbsi.github.io/assets/126305178/0b0e94ec-ec1d-41d3-925f-4fa19adfaf21)

1. Azriel Fidzlie 19215261
2. M Daffa R 19215264
3. M Azhar A 19215058
4. Sigit Prastio 19215143
5. Maulana Reza Haqq 19215255
