---
title: "MENGHITUNG JUMLAH NETWORK DAN HOST PADA IP ADDRESS"
last_modified_at: 2023-09-30T15:00:00-01:00
categories:
  - Blog
tags:
  - Tugas
  - BSI
  - Jaringan Komputer
---

Untuk menghitung jumlah network dan host yang akan terbentuk dari alamat IP Address serta membuat rincian alamat, kita perlu memahami notasi CIDR (Classless Inter-Domain Routing). Dalam notasi CIDR, alamat IP terdiri dari dua bagian: network address dan host address, di mana jumlah bit yang dialokasikan untuk network address dapat bervariasi.

![image](https://github.com/azrielbsi/azrielbsi.github.io/assets/126305178/d3f2c2c2-7e47-4afa-9668-4d4647e48c96)


Kelompok 3 Kelas: 19.A4.07

1. Azriel Fidzlie 19215261
2. M Daffa R 19215264
3. M Azhar A 19215058
4. Sigit Prastio 19215143
5. Maulana Reza Haqq 19215255

Hitunglah jumlah Network dan Host yang akanterbentuk dari alamat IP Address dibawah ini, kemudian buat rincian alamat (Network, Broadcast) beserta alamat yang dapat diberikan kepada setiap host (minimal untuk 5 host/komputer):
1. 192.168.10.1/30
2. 172.168.10.1/16
3. 172.168.10.1/22
4. 10.168.5.1/8
5. 10.168.5.1/17

# 1. 192.168.10.1/30

Netmask = 255.255

Subnet = 11111111. 11111111. 11111111. 111111.00

### Jumlah Network

= 2^6

= 2x2x2x2x2x2

= 64


### Host

= 2^2-2

= 2x2

= 4 - 2

= 2

= 2 Host


### Alokasi IP


Network   : 192.168.10.0

host : 192.168.10.1 - 192.168.10.2

broadcast : 192.168.10.3


Network   : 192.168.10.4

host : 192.168.10.5 - 192.168.10.6

broadcast : 192.168.10.7


Network   : 192.168.10.8

host : 192.168.10.9 - 192.168.10.10

broadcast : 192.168.10.11

# 2. 172.168.10.1/16

Netmask = 255.255.000.000

Subnet = 11111111.11111111.00000000.00000000

Network = 2n = 20 = 1 network

Host = 2h-2 = 216-2 = 65.534 host


### Alokasi IP

Network :172.168.0.0

Host : 172.168.0.1 - 192.168.255.254

Broadcast : 192.168.255.255


# 3. 172.168.10.1/22

Netmask = 255.255.252.0

Subnet = 11111111.11111111.11111100.00000000

Jumlah Network = 2^6

= 2x2x2x2x2x2

= 64 Network

### Jumlah Host = 2^10 - 2
= 1024 - 2
=1022 Host

### Alokasi IP

Network : 172.168.10.0

Host Pertama : 172.168.10.1

Host Kedua : 172.168.10.2

Host Terakhir : 172.168.255.254

Broadcast : 172.168.255.255


# 4. 10.168.5.1/8

Netmask = 255.000.000.000

Subnet = 11111111.00000000.00000000.00000000

Network = 2n = 20 = 1 network

Host = 2h-2 = 224-2 = 167.772.614 host


### Alokasi IP

Network : 10.168.5.0

Host : 10.0.0.1 - 10.255.255.254

Broadcast : 10.255.255.255


# 5. 10.168.5.1/17

Netmask = 255.255.128.000

Subnet = 11111111.11111111.10000000.00000000

Network = 2n = 21 = 2 network

Host = 2h-2 = 215-2 = 32.766 host


### Alokasi IP :

Network :10.168.0.0

Host : 10.168.0.1 - 10.168.127.254

Broadcast : 10.168.127.255
