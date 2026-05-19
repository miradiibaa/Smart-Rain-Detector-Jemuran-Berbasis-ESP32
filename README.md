# 🌧️ Smart Rain Detector Jemuran Berbasis ESP32

Sistem jemuran otomatis berbasis IoT yang mendeteksi hujan secara real-time dan menarik jemuran masuk secara otomatis menggunakan ESP32.

---

## 📋 Deskripsi Proyek

**Smart Rain Detector** adalah sistem yang dirancang untuk mengatasi masalah jemuran yang basah akibat hujan tiba-tiba. Dengan memanfaatkan berbagai sensor yang terhubung ke ESP32, sistem dapat mendeteksi perubahan cuaca dan merespons secara otomatis tanpa perlu campur tangan pengguna.

Proyek ini merupakan tugas mata kuliah **Internet of Things**, Program Studi Teknik Informatika, Fakultas Teknik dan Teknologi Kemaritiman, **Universitas Maritim Raja Ali Haji (UMRAH)**.

---

## ⚙️ Cara Kerja

```
Rain Sensor mendeteksi hujan
        ↓
ESP32 memproses data sensor
        ↓
Servo Motor bergerak → jemuran masuk otomatis
        ↓
OLED menampilkan status sistem
```

1. **Rain Sensor** mendeteksi keberadaan air hujan dan mengirim sinyal ke ESP32.
2. **ESP32** memproses sinyal dan menjalankan logika kontrol.
3. **Servo Motor** bergerak otomatis untuk menarik jemuran ke posisi aman.
4. **OLED Display** menampilkan status real-time seperti `Hujan Terdeteksi` atau `Jemuran Masuk`.
5. **DHT22** memantau suhu dan kelembapan udara secara berkala.
6. **LDR Sensor** mendeteksi kondisi cahaya lingkungan.
7. **RTC** mencatat waktu kejadian secara akurat.

---

## 🛠️ Alat dan Komponen

| Komponen | Fungsi |
|----------|--------|
| ESP32 | Mikrokontroler utama |
| Rain Sensor | Mendeteksi air hujan |
| DHT22 | Membaca suhu & kelembapan |
| LDR Sensor | Mendeteksi kondisi cahaya |
| RTC (Real Time Clock) | Pencatatan waktu |
| Servo Motor | Menggerakkan jemuran otomatis |
| OLED Display | Menampilkan status sistem |
| Breadboard | Media rangkaian |
| Kabel Jumper | Penghubung antar komponen |

---

## 👥 Anggota Kelompok

| Nama | NIM |
|------|-----|
| Amira Azza Nuuradiba | 2401020001 |
| Juan Prattycha Tazira | 2401020005 |
| Zafira Khairunnisa | 2401020006 |
| Naurah Nadhif Shahada | 2401020014 |
| Rashika Kasih Putri | 2401020017 |

---

## 🔧 Simulasi

Proyek ini disimulasikan menggunakan **[Wokwi](https://wokwi.com)** sebelum diimplementasikan pada perangkat keras nyata.

---

> Teknik Informatika · FTTK · UMRAH · 2025/2026
