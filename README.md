# Monitoring Suhu dan Kelembaban dengan NodeRed
Program ini dibuat untuk memonitoring suhu dan kelembaban dari sensor DHT 22 menggunakan platform Node Red. Percobaan dilakukan menggunakan ESP32 pada platform WokWi yang telah dibuat sebelumnya [Simulasi Monitoring Suhu dan Kelembaban](https://wokwi.com/projects/408977016650234881)

![Simulasi Wokwi](https://github.com/mutualis/Monitoring-Suhu-dan-Kelembaban-dengan-NodeRed/blob/main/img/Simulasi%20Wokwi.png)

## Membuat Flows NodeRed
Selanjutnya membuat Flows pada NodeRed seperti gambar berikut, atau dapat mengimport file [JETSON](https://github.com/mutualis/Monitoring-Suhu-dan-Kelembaban-dengan-NodeRed/blob/main/flows.json) ini.

![Flows Nodered](https://github.com/mutualis/Monitoring-Suhu-dan-Kelembaban-dengan-NodeRed/blob/main/img/Flows.png)

## Hasil Running Program Monitoring
Percobaan ini dengan menjalankan platfom WokWi dan mendapatkan hasil yang sesuai. Nilai suhu dan kelembaban yang tertampil pada monitoring system NodeRed sama dengan nilai yang diatur pada sensor DHT 22 WokWi.

![Flows Nodered](https://github.com/mutualis/Monitoring-Suhu-dan-Kelembaban-dengan-NodeRed/blob/main/img/SimulasiHasil.png)
