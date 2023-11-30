# 2. Menerima Data JSON Melalui Protokol MQTT

## 1. Keterangan Singkat (Abstrak)

Dalam percobaan ini program dibuat untuk dapat menerima pesan atau data antara perangkat dimana data yang diterima berupa JSON.

## 2. Alat dan Bahan
1. Laptop
2. Node Red

## 3. Hasil dan Pembahasan

### Hasil Percobaan
![1  Flow pemrosesan data JSON melalui protokol MQTT](https://github.com/Aisyahnurul/AisyahN-system-embedded/assets/147674662/11d94dd2-16c2-448e-89a8-ee3dce4c2772)


Outputnya yang dihasilkan yaitu 30 yang merupakan output dari humi. Untuk menerima data JSON melalui protokol MQTT biasanya melibatkan implementasi dari dua fungsi callback utama: on_connect dan on_message. 
Fungsi on_connect dipanggil saat koneksi ke broker berhasil dibuat. Pada contoh ini, fungsi ini mengatur subscribe ke topik "topik/json" setelah berhasil terhubung. 
fungsi callback on_message untuk menanggapi setiap kali pesan diterima dari broker MQTT. 
Dalam fungsi ini,  dapat menguraikan dan memproses data JSON dari payload pesan.

## 4. Pengembangan 

### Hasil Percobaan
![2  pengembangan](https://github.com/Aisyahnurul/AisyahN-system-embedded/assets/147674662/56ea5776-0210-45b7-8b85-18951c138cad)

mempunya 2 input (Inject Node). Input pertama sama seperti pada percobaan diatas, Sementara Input yang lain menggunakan topic
kitchen/sensors, dengan jenis sensor flame : 0 , metane : 0, temp : 24, humi :38. Output yang dihasilkan tertampil dalam log yang berbeda. 
yaitu 30 yang merupakan output humi dari topic livingroom/sensors. Sedangkan output kedua yaitu 38 yang merupakan output humi dari topic kitchen/sensors.



<br></br>
