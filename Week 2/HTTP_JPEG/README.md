# Mengakses Packet Gambar Pada HTTP

## Tentang Projek

Repository untuk menyimpan semua tugas pada mata kuliah Konsep Jaringan yang diampu oleh Dr. Ferry Astika Saputra ST, M.Sc ([@ferryastika](https://github.com/ferryastika)).

---

1. Buka file sample capture http_with_jpegs.cap menggunakan Wireshark, pastikan filter capture HTTP <br>
   ![Wireshark](./assets/jpeg_cap.png)

2. Cari packet dengan info **200 OK (JPEG JFIF image)** <br>
   ![200 OK](./assets/200_ok.png)

3. Klik packet tersebut, lalu klik kanan pada **JPEG File Interchange Format** yang terletak pada window di kiri bawah. Kemudian pilih menu **Show Packet Bytes..** atau bisa dengan menekan **CTRL + SHIFT + O** <br>
   ![Interchange Format](./assets/left_bar.png)

4. Maka Wireshark akan otomatis menampilkan data gambar dari packet tersebut. Berikut adalah contoh gambar yang terdapat pada packet nomor 61. <br>
   ![61](./assets/61.png)

---

Terdapat total 5 packet dengan data gambar pada file capture tersebut. Berikut adalah 4 packet tersisa yang terdapat data gambar:

<p align="center">
<img src="./assets/72.png" alt="72">
<br>
<i>Packet No. 72</i>
</p>

<br>

<p align="center">
<img src="./assets/259.png" alt="259">
<br>
<i>Packet No. 259</i>
</p>

<br>

<p align="center">
<img src="./assets/269.png" alt="269">
<br>
<i>Packet No. 269</i>
</p>

<br>

<p align="center">
<img src="./assets/479.png" alt="479">
<br>
<i>Packet No. 479</i>
</p>
