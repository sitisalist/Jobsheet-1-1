# Johsheet-1-1

A. Memperoleh MAC Address ESP32 Receiver

Catat Mac Address ESP32.

<img width="360" alt="job1-1_A1" src="https://user-images.githubusercontent.com/121160420/210044775-bf088eed-131e-4522-9d42-944172824d83.png">

B. ESP-NOW One-Way Point-to-Point Communication

Setelah ESP32 sender dikonfigurasi, kemudian konfigurasikan ESP32 yang lain sebagai Receiver. Ketikkan script program berikut untuk mengkonfigurasi ESP32 sebagai receiver.

sender

gambar

receiver

gmbt


Aturlah jarak awal komunikasi antara sender dan receiver yaitu 1 meter. Kemudian ubah jarak komunikasi dengan penambahan 1 meter. Data yang dikirim pada tiap iterasi pengujian adalah 10 data. Aturlah tinggi antena atau peletakan ESP32 pada ground level (menempel tanah), 30 cm di atas tanah, dan 1 meter di atas tanah.


C. One-Way, One-to-Many Communication

a) Mengirim Pesan yang Sama Ke Beberapa Board ESP32

MAC Sender (Syauqi & Vania) : 3C:71:BF:F1:4B:08 MAC Reciver 1 (Noviantie & Dionysius) : 24:6F:28:02:C3:1C MAC Receiver 2 (Hesti & Nabila) : 24:0A:C4:C6:06:54 MAC Receiver 3 (Cantika & Razan) : 30:AE:A4:7A:8F:B8

Sender (Syauqi & Vania)

D. One-Way, Many-to-One Communication MAC Sender 1 (Syauqi & Vania) : 24:0A:C4:C5:E2:DC MAC Sender 2 (Hesti & Nabila) : 24:6F:28:02:C3:1C MAC Sender 3 (Cantika & Razan) : 24:0A:C4:C6:0E:7C MAC Receiver (Dionysius & Noviantie) : 3C:71:BF:F1:42:70

Sender (Syauqi & Vania)

E. Two-Way Communication Pengecekan Sensor menggunakan DHT22
