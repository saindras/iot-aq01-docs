---
layout: post
title: "Desain PCB - Overview"
date: 2025-05-11
categories: [Desain PCB]
---

## Tujuan

Desain PCB ini digunakan untuk merapikan dan menstabilkan koneksi antara ESP8266, sensor DHT11/DS18B20, dan LCD I2C agar siap dicetak ke papan PCB menggunakan CNC Engraver.

## Komponen Utama

- NodeMCU ESP8266 V3 (CP2102, USB Type-C)
- Sensor DHT11 dan DS18B20
- LCD 16x2 I2C (PCF8574 backpack)
- Header pin, resistor pull-up (untuk DS18B20)

## Tools yang Digunakan

- EasyEDA untuk desain dan wiring skematik
- Mesin: EIDEVO DIY Pro CNC 3018 Engraver
- Pisau Engraver: HSS 1.98–3.56 mm (opsi alternatif dari V-bit 0.2 mm)

## File Pendukung

- `diagram.json` – desain wiring simulasi
- `pcb-layout.jpg` – tangkapan layar tata letak PCB
- `bom.csv` – daftar komponen (Bill of Materials)
