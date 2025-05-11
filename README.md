# IoT Akuarium AQ01 Documentation 🐠

Dokumentasi lengkap untuk proyek **IoT Monitoring Suhu dan Kelembaban Akuarium AQ01**, termasuk seluruh subsistem, versi kode, dan panduan deployment server Raspberry Pi.

## 📂 Struktur Dokumentasi

- **Subsistem IoT**  
  Pembacaan sensor suhu & kelembaban menggunakan ESP8266/ESP32 dan LCD I2C.

- **Subsistem Lokal**  
  Dashboard berbasis PHP + MySQL untuk menampilkan dan mengelola data.

- **Desain PCB**  
  Desain sirkuit cetak menggunakan EasyEDA dan CNC Engraver.

- **Server Raspberry Pi**  
  Instalasi headless server menggunakan Raspberry Pi OS Lite, Docker, dan MQTT.

## 🚀 Cara Menjalankan Dokumentasi

Dokumentasi ini dibangun menggunakan [Chirpy Theme for Jekyll](https://github.com/cotes2020/jekyll-theme-chirpy) dan dihosting di GitHub Pages.

1. Clone repositori:
   ```bash
   git clone https://github.com/username/iot-aq01-docs.git
   ```

2. Instal dependensi:
   ```bash
   bundle install
   ```

3. Jalankan lokal:
   ```bash
   bundle exec jekyll serve
   ```

## 🔖 Lisensi

Proyek ini didistribusikan di bawah lisensi MIT. Lihat `LICENSE` untuk informasi lebih lanjut.

---

> Dikembangkan oleh Gede Saindra Santyadiputra.
