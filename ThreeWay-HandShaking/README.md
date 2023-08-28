# 3 Way HandShaking
 <div align = "center">
        <img src="assets/3wayhandshake.jpg" alt="Image" width ="500" />
</div>

3-way handshake adalah proses yang digunakan dalam protokol jaringan, khususnya dalam protokol TCP (Transmission Control Protocol), untuk memulai koneksi antara dua perangkat yang berkomunikasi. Proses 3-way handshake ini memastikan bahwa kedua perangkat memiliki saluran komunikasi yang terbuka dan siap untuk pertukaran data.

Terkait dengan protokol TCP, 3-way handshake melibatkan tiga langkah atau pesan yang dikirimkan antara pengirim dan penerima:

## Langkah 1 (SYN): 
Pengirim mengirimkan pesan SYN (Synchronize) ke penerima untuk memulai permintaan koneksi. Pesan ini berisi nomor urut awal (sequence number) yang akan digunakan dalam pertukaran data.

## Langkah 2 (SYN-ACK): 
Penerima merespons dengan mengirimkan pesan SYN-ACK (Synchronize-Acknowledgment) sebagai tanda bahwa ia menerima permintaan koneksi. Pesan ini juga berisi nomor urut awal dan nomor urut pengirim yang akan digunakan dalam pertukaran data.

## Langkah 3 (ACK): 
Pengirim mengirimkan pesan ACK (Acknowledgment) sebagai konfirmasi bahwa ia menerima balasan SYN-ACK dari penerima. Dengan ini, koneksi telah didirikan dan dapat digunakan untuk pertukaran data.

Setelah proses 3-way handshake selesai, kedua perangkat dapat mulai bertukar data dengan menggunakan koneksi yang telah didirikan tersebut. Jika selama proses ini terjadi kegagalan atau gangguan, maka koneksi tidak akan terbentuk dan perangkat harus mencoba lagi untuk memulai koneksi.

Proses 3-way handshake memastikan bahwa komunikasi antara pengirim dan penerima dimulai dengan baik dan bahwa kedua perangkat memiliki pemahaman yang benar tentang nomor urut yang akan digunakan untuk mengatur aliran data dalam koneksi tersebut.




