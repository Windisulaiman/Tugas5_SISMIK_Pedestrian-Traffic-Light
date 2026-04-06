# Penerapan Pedestrian-Traffic-Light

## 👨‍💻 Penulis
* **Nama:** Windi Sulaiman Ismansa
* **NIM:** H1H024005
* **Mata Kuliah:** Sistem Mikrokontroler 

## 🛠️ Komponen yang Digunakan
* 1x Arduino Uno 
* 7x LED (3 Merah, 1 Kuning, 3 Hijau)
* 7x Resistor (220 Ohm )
* Pushbutton 2x
* Kabel Jumper secukupnya

## 📌 Konfigurasi Pin GPIO

### Versi 1: Arduino Uno (Tugas Utama)
Sistem ini menggunakan pin digital Arduino dengan pemetaan sebagai berikut:
* Lampu Kendaraan (10,9,8)
* Lampu Penyebrangan Kiri( merah 12 dan hijau 11)
* Lampu Penyebrangan Kanan (Merah 7 dan hijau 6)
* Pushbutton (kanan 2, kiri 13)
  
## ⏱️ Aturan & Timing Sistem
 * Kondisi awal:
    • Lampu kendaraan hijau
    • Lampu pedestrian merah
* Saat ditekan:
    • Lampu kendaraan berubah menjadi merah
    • Lampu pedestrian berubah menjadi hijau
* Setelah waktu tertentu:
    • Lampu pedestrian kembali merah
    • Lampu kendaraan memasuki fase kuning (transisi)
* Sistem kembali ke kondisi awal:
    • Lampu kendaraan hijau
    • Lampu pedestrian tetap merah

## 🚀 Link Simulasi
Rangkaian dan simulasi dapat dilihat pada link dibawah ini:
* **Arduino Uno:** [Simulasi Tinkercad](https://www.tinkercad.com/things/7ZgOpGRwMwP-tugas-52).

