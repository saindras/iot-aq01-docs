---
layout: post
title: "Dashboard Lokal - Manajemen Versi CODE-AQ01-DSHBRD001"
date: 2025-05-11
categories: [Subsistem Lokal]
---

## 🧾 Versi: `CODE-AQ01-DSHBRD001`

Versi ini merupakan integrasi pertama dashboard lokal dengan fitur lengkap yang mencakup:

### 🔹 Komponen Utama

| File | Fungsi |
|------|--------|
| `index.php` | Menampilkan data sensor dari database lokal secara realtime. Dilengkapi grafik suhu dan kelembaban, fitur ekspor Excel/CSV/PDF, serta tombol kirim data ke ThingSpeak dengan progress bar. |
| `upload.php` | Endpoint untuk menerima data dari perangkat IoT (ESP8266/ESP32) dan menyimpannya ke database `sensor_logs`. |
| `dashboard_thinkspeak.html` | Visualisasi data hasil sinkronisasi dari platform ThingSpeak. Menampilkan grafik suhu, kelembaban, dan waktu pengambilan dari cloud. |

### 📅 Catatan Perubahan

- Penambahan validasi tanggal di `index.php`
- Integrasi grafik Chart.js dan ekspor `jsPDF`, `SheetJS`, dan CSV
- Sinkronisasi manual ke ThingSpeak (`export_thinkspeak.php`)
- Flatpickr untuk pemilihan tanggal
- AJAX-based progress bar untuk pengiriman data

---

> Semua file berada di sistem lokal `htdocs/aq01/` dan telah diuji dengan ESP32 dan database MySQL lokal.
