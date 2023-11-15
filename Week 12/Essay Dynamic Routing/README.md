# Essay Dynamic Routing

#### :memo: Pengantar <br>
Jaringan komputer modern merupakan jantung dari komunikasi dan pertukaran data di seluruh dunia. Dalam jaringan yang kompleks dan berukuran besar, rute pengiriman data adalah elemen kunci yang menentukan bagaimana informasi bergerak dari satu titik ke titik lain. Salah satu teknik yang penting dan efektif dalam mengelola rute pengiriman ini adalah dynamic routing.<br>

#### :bulb: Apa Itu Routing? <br>
Routing merupakan hal yang vital dalam dunia jaringan komputer. Routing merupakan proses meneruskan paket-paket data dari satu jaringan ke yang lainnya. Proses ini dapat diartikan juga sebagai penggabungan beberapa jaringan untuk meneruskan paket data dari satu jaringan ke jaringan selanjutnya. <br>
Alat yang melakukan proses routing bernama Router. Selain berfungsi mengirimkan paket data antar jaringan, router juga berfungsi menentukan jalur terbaik untuk mencapai network tujuan. Untuk menjalankan fungsi tersebut, router menggunakan routing table. Routing table berisi informasi keberadaan beberapa network, sekaligus merupakan pedoman jalur yang dilalui sebuah paket data agar bisa mencapai tujuannya. <br>

#### :bulb: Dynamic Routing <br>
Routing dinamis atau dynamic routing adalah protokol routing yang digunakan untuk menemukan network serta untuk melakukan update routing table pada router. Routing dimanis ini lebih mudah dilakukan daripada menggunakan routing statis dan default. Meskipun begitu, routing jenis ini terdapat perbedaan dalam pemrosesan data di CPU router dan penggunaan bandwidth dari link jaringan. <br>
Routing dinamis ini berada pada lapisan network layer jaringan komputer dalam TCP/IP Protocol Suites. Berkebalikan dengan routing statis, routing dinamis memiliki protokol routing yang akan mengatur router secara otomatis untuk saling berkomunikasi. Informas ini digunakan untuk membangun dan memperbaiki table routing nya. Ada berbagai macam protokol routing dinamis, seperti: 
<li>RIP (Routing Information Protocol)</li>
<li>IGRP (Internal Gateway Routing Protocol)</li>
<li>OSPF (Open Shortest Path First)</li>
<li>BGP (Border Gateway Protocol)</li>

#### :bulb: Perbedaan Dynamic Routing dan Static Routing <br>
| Routing Statis | Routing Dinamis |
|---|---|
| Tabel routing dibuat dan dihapus secara manual oleh administrator | Tabel routing dibuat dan dihapus secara otomatis oleh protokol |
| Cocok digunakan untuk jaringan skala kecil | Cocok digunakan untuk skala besar |
| Tidak banyak membutuhkan resource | Banyak menggunakan resource |
| Lebih aman | Kurang aman |
| Tidak menggunakan protokol routing | Menggunakan protokol seperti RIP, OSPF, dsb |
| Berfungsi pada protokol IP | Berfungsi pada inter-routing protocol |
| Router tidak dapat membagi informasi routing | Router membagi informasi routing secara otomatis | <br>

#### :bulb: Cara Kerja Dynamic Routing <br>
Routing dinamis bekerja dengan cara mengatur tiap router sehingga dapat berkomunikasi antar router satu dengan router lainnya dan saling memberikan informasi dan juga tentunya informasi routing yang dapat menguba isi dari routing table, dengan kata lain routing dinamis adalah proses pengisian data pada routing table secara otomatis. Secara khusus, routing dinamis merupakan jenis routing yang paling mudah dikonfigurasikan dan lebih efektif dalam memilih rute terbaik untuk sebuah tujuan jaringan serta dapat menemukan jaringan terluar. <br>

#### :memo: Referensi
<li>Amelia, S. (2011). "Perbedaan Routing Statis dan Dinamis: Panduan Lengkap". Diakses 6 November 2023 dari https://www.dewaweb.com/blog/perbedaan-routing-statis-dan-dinamis/</li>
<li>"Routing Dynamic: Pengertian, jenis, dan cara kerjanya". Diakses 6 November 2023 dari https://www.idn.id/routing-dynamic/</li>
<li>Iqbal, M. (2020). "Dynamic Routing". Diakses 6 November 2023 dari https://miqbal.staff.telkomuniversity.ac.id/dynamic-routing/</li>