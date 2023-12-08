# Cisco Packet Tracer

## Tentang Projek

Repository untuk menyimpan semua tugas pada mata kuliah Konsep Jaringan yang diampu oleh Dr. Ferry Astika Saputra ST, M.Sc ([@ferryastika](https://github.com/ferryastika)).

---
## Ping Over Device with different Router
Ping adalah salah satu perintah yang digunakan dalam Packet Tracer, yang merupakan perangkat lunak simulasi jaringan yang dikembangkan oleh Cisco. Perintah ping digunakan untuk menguji konektivitas antara dua perangkat atau host dalam jaringan.

Contoh Koneksi antara device dan juga router yang berbeda.
![Alt text](assets/Full.png)

| Jenis | Penjelasan |
| -------- | -------- |
| **Copper Cross-over** (garis putus-putus) |  jenis kabel jaringan yang digunakan untuk menghubungkan dua perangkat jaringan serupa secara langsung. Ini biasanya digunakan untuk menghubungkan perangkat jaringan yang serupa, seperti komputer ke komputer, switch ke switch, atau router ke router, tanpa perlu perangkat tambahan seperti switch atau hub di antaranya. | 
| **Copper Straight-Through** (garis lurus)| Kabel Copper Straight-Through adalah jenis kabel jaringan yang paling umum digunakan untuk menghubungkan perangkat jaringan yang berbeda jenis, seperti komputer ke switch atau router. Dalam kabel straight-through, urutan pin pada satu ujung kabel sama dengan urutan pin pada ujung yang lainnya. Ini berarti bahwa sinyal transmit (TX) dari satu perangkat terhubung langsung ke sinyal receive (RX) pada perangkat yang lain, dan sebaliknya. |
---
### Penjelasan
Setiap perangkat dalam jaringan memiliki alamat IP yang unik dan subnet mask yang sesuai. PC dalam jaringan yang sama (misalnya, PC1 dan PC2 di Switch 1) memiliki alamat IP dalam jaringan yang sama dengan subnet mask yang benar, sehingga mereka dapat berkomunikasi langsung satu sama lain tanpa perlu melibatkan router.

Router di sini berfungsi sebagai gateway untuk menghubungkan dua jaringan yang berbeda. Router 1 menghubungkan Jaringan A (192.168.1.0/24) dan Jaringan B (10.0.1.0/24), sedangkan Router 2 menghubungkan Jaringan A (192.168.2.0/24) dan Jaringan B (10.0.1.0/24).

Ketika PC ingin mengirim ping ke PC di jaringan yang berbeda, mereka akan mengirim paket ke gateway (router) mereka, yaitu Router 1 atau Router 2. Router akan memeriksa tabel rute dan meneruskan paket ke tujuan yang sesuai.

Dengan konfigurasi IP yang benar dan tabel rute yang sesuai di router, PC dapat mengirim ping satu sama lain melalui router dan antarmuka jaringan yang sesuai, sehingga memungkinkan komunikasi antar-jaringan.

---

## Hasil Percobaan
disini kita mengecek dengan menggunakan perintah ping antar pc ke pc lain :
- ### PC 0 -> PC 1 & 2 & 3

![Alt text](assets/PC0toAll.png)


- ### PC 1 -> PC 0 & 2 & 3

![Alt text](assets/PC1toAll.png)

- ### PC 2 ke PC 0 & 1 & 3

![Alt text](assets/PC2toAll.png)


- ### PC 3 ke PC 0 & 1 & 2

![Alt text](assets/PC3toAll.png)

