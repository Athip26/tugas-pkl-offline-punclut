# TUGAS PKL PPTIK OFFLINE 
### SEBELUM MENGERJAKAN PERSIAPKAN BERBAGAI KEPERLUAN SEPERTI:
- Account forum pptik, jika belum mempunyai akun **Diharuskan Mendaftar"** terlebih dahulu. Akun ini berguna untuk mengumpulkan laporan pkerjaan setiap harinya berupa thread yang ada diforum yang dapat di akses di [Link Forum](http://forum.pptik.id/forumdisplay.php?fid=461).
- Menginstall Software yang diperlukan.


### Software yang diperlukan : 
- Arduino IDE (Terbaru).
- MQTTBOX, MQTTX, dan lain-lain.

### Library Arduino IDE yang diperlukan:
- ESP versi 2.4.1. atau yang terbaru. Cara menginstall dapat dilihat pada link [Tutorial install board esp8266](https://www.tutorialiot.com/2019/02/cara-mudah-install-board-esp8266-di.html).
- PubSubClient


#### Hardware yang digunakan: 
- NodeMCU Amica ESP8288 / NodeMCU Lolin ESP8266.
- Micro USB Data.
- Soil Sensor.
- Relay.


## SETIAP TUGAS DIWAJIBKAN UNTUK:
- [x] Membuat video apa yang dikerjakan.
- [x] Membuat dokumen yang isinya menceritakan apa yang dikerjakan.
- [x] Submit dengan membuat thread pada [Forum](http://forum.pptik.id/forumdisplay.php?fid=461).
- [x] **Tugas di kumpulkan setiap orang**.


## Tugas 1 [Basic] WAKTU PENGERJAAN 3 HARI [15- 17 February 2021]
- Membuat program blink menggunakan esp8266 [Blink](https://github.com/pptik/tugas-pkl-offline-punclut/tree/main/Blink), siswa diwajibkan menambahkan sendiri serial println untuk setiap status led.
- Membuat program read analog  [Read analog](https://github.com/pptik/tugas-pkl-offline-punclut/tree/main/AnalogReadSerial).
- Membuat program read digital [Read Digital](https://github.com/pptik/tugas-pkl-offline-punclut/tree/main/DigitalReadSerial)


## Tugas 2 WAKTU PENGERJAAN 3 HARI [18- 20 February 2021]
- Membuat program menampilkan status pompa  [Status Pompa](https://github.com/pptik/tugas-pkl-offline-punclut/tree/main/Tahap-1-Serial-Monitor/relay-pump-serial).
- Membuat program menampilkan status pompa  [Status Soil](https://github.com/pptik/tugas-pkl-offline-punclut/tree/main/Tahap-1-Serial-Monitor/soil-moisture-serial).
- Membuat program mengirimkan status pompa  [Status Soil](https://github.com/pptik/tugas-pkl-offline-punclut/tree/main/Tahap-2-MQTT/soil-moisture).
- Membuat program mengirimkan status soil  [Status Soil](https://github.com/pptik/tugas-pkl-offline-punclut/tree/main/Tahap-2-MQTT/water-pump).
- Membuat progran integrasi soil dan pompa untuk setiap code di install di board esp8266 berbeda [Integrasi](https://github.com/pptik/tugas-pkl-offline-punclut/tree/main/Tahap-3-Smart%20Automatic%20Watering).


### 1. Untuk compile ikuti langkah berikut: 
- Buka Arduino IDE.
- Sambungkan Node MCU dan Kabel USB ke Port USB di port USB .
- Pilih Board yang akan di install di Arduino IDE
    > Tools -> Board -> Esp8266 Modules -> NodeMCU 1.0 (ESP-12E Module).
- Pilih upload speed di Arduino IDE
    > Tools -> Upload Speed -> 115200.
- Tekan ***Ctrl+U*** untuk upload.
- Tunggu hingga Done uploading.






