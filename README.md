# Jobsheet-1-1

A. Memperoleh MAC Address ESP32 Receiver

Catat Mac Address ESP32.

<img width="360" alt="job1-1_A1" src="https://user-images.githubusercontent.com/121160420/210044775-bf088eed-131e-4522-9d42-944172824d83.png">

B. ESP-NOW One-Way Point-to-Point Communication

Setelah ESP32 sender dikonfigurasi, kemudian konfigurasikan ESP32 yang lain sebagai Receiver. Ketikkan script program berikut untuk mengkonfigurasi ESP32 sebagai receiver.

sender

<img width="404" alt="JOB1-1B1m" src="https://user-images.githubusercontent.com/121160420/210076126-6b54eb6b-0659-41b7-8394-7245d9f6d538.png">

receiver

![sender](https://user-images.githubusercontent.com/121160420/210078907-f54f75c3-904e-4ca4-ab3a-3b0de58585cc.jpg)

Aturlah jarak awal komunikasi antara sender dan receiver yaitu 1 meter. Kemudian ubah jarak komunikasi dengan penambahan 1 meter. Data yang dikirim pada tiap iterasi pengujian adalah 10 data. Aturlah tinggi antena atau peletakan ESP32 pada ground level (menempel tanah), 30 cm di atas tanah, dan 1 meter di atas tanah.

<img width="391" alt="tabel jarak" src="https://user-images.githubusercontent.com/121160420/210076296-4bd1e84f-1e3b-4925-bf53-31d4071c586c.png">

TX-RX Ground 1,2 Meter

Sender

![image](https://user-images.githubusercontent.com/121160420/210076431-2b672c6e-4718-4944-a2eb-ad1fe7d7622f.png)

Receiver

![TX-RX 1,2 m](https://user-images.githubusercontent.com/121160420/210077802-7d3c613d-9df9-4ec8-a7e9-9741467a1016.jpg)

TX-RX Tinggi 30cm Jarak 1 Meter

Sender

![image](https://user-images.githubusercontent.com/121160420/210078625-aedef043-4d24-45a8-a6ca-78b066a9c0b6.png)

Receiver
![tx-rx 30 1,2](https://user-images.githubusercontent.com/121160420/210078412-c9283f12-03b3-4c99-8f33-35e9378bd946.jpg)

TX-RX Tinggi 1 Meter Jarak 1 Meter

Sender

Gambar

Receiver

![TX-RX 1M 1,2 m](https://user-images.githubusercontent.com/121160420/210079567-7671c342-896a-4c0e-b5c5-59c8b38fe302.jpg)

TX-RX Ground 2 Meter

Sender

gambar

Receiver

![TX-RX2M](https://user-images.githubusercontent.com/121160420/210080752-200efe49-3837-453f-9bc3-ede1ccf72f56.jpg)

TX-RX Tinggi 30cm Jarak 2 Meter

Sender

Gambar

Receiver

![TX-RX30 2M](https://user-images.githubusercontent.com/121160420/210080966-e43ee7d9-5cd7-48bd-9933-7bf41b05c2db.jpg)

TX-RX Tinggi 1m Jarak 2 Meter

Sender

gambar

Receiver

![TX-RX 1M 2 m](https://user-images.githubusercontent.com/121160420/210081834-6cb13f25-69ba-4401-a7aa-691aeeb8945a.jpg)

TX-RX Ground 3 Meter

Sender

gambar

Receiver

C. One-Way, One-to-Many Communication

TX-RX Tinggi 30cm Jarak 3 Meter

Sender

gambar

Receiver

![30 jarak 3m](https://user-images.githubusercontent.com/121160420/210082356-39180335-d99c-491f-8905-a3504d141642.jpg)

TX-RX Tinggi 1 Meter Jarak 3 Meter

Sender

Gambar

Receiver

![1m 3m](https://user-images.githubusercontent.com/121160420/210082496-aa9d50eb-cd93-4771-8233-270ad6b8dd30.jpg)

TX-RX Ground 4,2 Meter

Sender

Gambar

Receiver

![ground 4,2m](https://user-images.githubusercontent.com/121160420/210082672-85e18bf4-d3cf-418b-a692-9b48432eeb6e.jpg)

TX-RX Tinggi 30cm Jarak 4,2 Meter

Sender

Gambar

Receiver

![30cm 4,2m](https://user-images.githubusercontent.com/121160420/210082806-4ded31d4-9073-4eb0-9706-409c0dec39f3.jpg)

TX-RX Tinggi 1 Meter Jarak 4,2 Meter

Sender

gambar

Receiver

![1m jarak4,2](https://user-images.githubusercontent.com/121160420/210082919-6e83952c-bb30-4d8c-9f7c-7f6a4cadeec9.jpg)

TX-RX Ground 5,4 Meter

Sender

gambar

Receiver

![ground 5,4m](https://user-images.githubusercontent.com/121160420/210083058-ba2d499e-9e03-41f3-8642-0f4b5fda7f29.jpg)

TX-RX Tinggi 30cm Jarak 5,4 Meter

Sender

gambar

Receiver

![30 jarak 5,4m](https://user-images.githubusercontent.com/121160420/210083187-982354ea-e367-4005-8c6d-a18d39ed8b16.jpg)

TX-RX Tinggi 1 Meter Jarak 5,4 Meter

Sender

gambar

Receiver

![1m jarak 5,4m](https://user-images.githubusercontent.com/121160420/210083277-28997f47-6ac5-46bc-bd06-db8149bc21f6.jpg)


a) Mengirim Pesan yang Sama Ke Beberapa Board ESP32

MAC Sender (Ayudya & Salist) : 24:6F:28:2B:6D:D8 MAC Reciver 1 (Satria & Adika) : 24:6F:28:02:C3:1C MAC Receiver 2 (Fariz & Josandy) : 24:6F:28:95:D5:80 

Sender (Ayudya & Salist)

Gambar

Receiver 1

gambar

Receiver 2

Gambar


D. One-Way, Many-to-One Communication MAC Sender 1 (Satria & Adika) : 24:6F:28:02:C3:1C MAC Sender 2 (Fariz & Josandy) : 24:6F:28:95:D5:80 MAC Receiver (Ayudya & Salist) : 24:6F:28:2B:6D:D8

Sender 1 (Satria & Adika)

gambar

Sender 2 (Fariz & Josandy)

gambar

E. Two-Way Communication Pengecekan Sensor menggunakan DHT22

<img width="283" alt="image" src="https://user-images.githubusercontent.com/121160420/210084267-abb904c8-cf98-41ba-8718-08baf64f45fc.png">

![image](https://user-images.githubusercontent.com/121160420/210084335-43901cf7-02a3-4727-90bd-d3effb7f1a16.png)
