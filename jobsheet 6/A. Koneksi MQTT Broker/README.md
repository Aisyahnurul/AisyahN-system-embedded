# 1. Koneksi MQTT Broker

## 1. Keterangan Singkat (Abstrak)

Dalam percobaan ini program dibuat untuk dapat mentransmisikan pesan atau data antara perangkat 
## 2. Alat dan Bahan
1. ESP32             ==> 1 buah
2.  LED              ==> 1 buah
3.  Multimeter        ==> 1 buah
4. Breadboard        ==> 1 buah
5. Sensor DHT11      ==> 1 buah
6. Potensiometer     ==> 1 buah
7. Resistor 1K Ohm   ==> 1 buah
8. Kabel jumper
   

## 3. Hasil dan Pembahasan

### Hasil Percobaan
![1  Flow dasar transmisi data menggunakan protokol MQTT](https://github.com/Aisyahnurul/AisyahN-system-embedded/assets/147674662/f7c162d5-db89-4e75-ad62-782060f71475)

Pada percobaan ini output yang dihasilkan yaitu berupa data string “28” yang merupakan output dari Temperature. 
Fungsi koneksi MQTT broker adalah membentuk dan memelihara koneksi antara perangkat atau aplikasi klien dengan broker MQTT. 
Dalam konteks protokol MQTT, broker bertindak sebagai server yang menerima dan menyampaikan pesan antara klien-klien yang terhubung. 
Broker MQTT biasanya memiliki informasi koneksi, seperti alamat IP atau nama host broker, port yang digunakan untuk koneksi (defaultnya adalah 1883 untuk non-secure dan 8883 untuk secure/TLS).


<br></br>
