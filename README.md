# IoT Prototype Project - Tugas 2

## Deskripsi

Proyek ini merupakan bagian dari Tugas 2 dalam SIC Stage 2. Tujuan dari tugas ini adalah untuk membuat dashboard di platform Ubidots yang menampilkan data dari dua sensor menggunakan ESP32 dan Micropython. Selain itu, data juga dikirimkan ke API menggunakan REST API dan disimpan dalam database MongoDB.

## Komponen

- **ESP32**: Digunakan untuk mengumpulkan data dari sensor dan mengirimkannya ke Ubidots dan MongoDB.
- **Sensor**: Dua sensor yang digunakan dalam proyek ini adalah sensor DHT22 untuk suhu dan kelembapan, serta sensor PIR untuk mendeteksi gerakan.
- **Ubidots**: Platform untuk menampilkan data sensor dalam bentuk visualisasi.
- **MongoDB**: Digunakan untuk menyimpan data sensor menggunakan Python.
- **Python (Flask)**: Digunakan untuk membuat API yang mengelola data dan menyimpannya di MongoDB.

## Persyaratan

### Hardware:
1. ESP32
2. Sensor DHT22 (untuk suhu dan kelembapan)
3. Sensor PIR (untuk mendeteksi gerakan)

### Software:
1. Micropython (untuk ESP32)
2. Python 3.x (menggunakan Flask untuk API)
3. Akun Ubidots
4. MongoDB
