---
layout: post
title: "Subsistem Lokal - Overview"
date: 2025-05-11
categories: [Subsistem Lokal]
---

## Fungsi Utama

Subsistem lokal bertugas menampung data dari perangkat IoT secara realtime ke database lokal (MySQL) serta menampilkannya melalui dashboard berbasis PHP.

## Komponen Utama

- PHP + MySQL (XAMPP / LAMP)
- File utama: `index.php`, `upload.php`, `export_thinkspeak.php`
- Dashboard menampilkan data suhu, kelembaban, waktu, grafik, dan tombol ekspor.

## Daftar File dan Versi

| Nama File | Deskripsi |
|-----------|-----------|
| CODE-AQ01-DSHBRD001 | Dashboard lokal lengkap dengan grafik, ekspor, kirim ke ThingSpeak |
| upload.php | Endpoint untuk menerima data dari ESP8266/ESP32 |
| export_thinkspeak.php | Kirim data dari database lokal ke ThingSpeak |
