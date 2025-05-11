---
layout: post
title: "Server Raspberry Pi - Overview"
date: 2025-05-11
categories: [Server Raspberry Pi]
---

## Fungsi

Raspberry Pi digunakan sebagai server lokal pengganti laptop, untuk menampung dan mengelola data IoT dari perangkat ESP.

## Rencana Konfigurasi

- OS: Raspberry Pi OS Lite (64-bit)
- Manajemen Kontainer: Docker + Portainer
- Komunikasi: MQTT (untuk efisiensi), HTTP sebagai fallback
- Database: MySQL atau MariaDB (opsional)

## Skema Operasi

1. Raspberry Pi menerima data lokal dari ESP8266 (via WiFi lokal).
2. Data disimpan di lokal (MySQL).
3. Penjadwalan sinkronisasi data ke internet dilakukan secara berkala.

## File Konfigurasi

- `docker-compose.yml`
- `mqtt-setup.sh`
- `cron-sync.sh`
