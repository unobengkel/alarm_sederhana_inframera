# Infrared Security Alert System (ISAS) 🚨

**Sistem Alarm Keamanan Mandiri Berbasis Sensor Inframerah (IR Barrier Alert)**

Proyek ini adalah solusi keamanan praktis, ekonomis, dan *standalone* yang dirancang untuk memproteksi area pribadi seperti pintu, jendela, atau lemari tanpa bergantung pada instalasi kabel listrik PLN. 

Sistem ini memanfaatkan teknologi sensor inframerah dengan logika *Active LOW* untuk memberikan respon instan berupa suara (buzzer) saat terjadi interupsi atau perubahan posisi pada objek yang dipantau.

---

## 🛠 Fitur Utama

* **Dual 18650 Power Cell**: Menggunakan dua baterai 18650 untuk kapasitas daya besar dan durasi operasional yang lama.
* **Precision IR Detection**: Sensitivitas sensor yang dapat diatur (kalibrasi) untuk akurasi deteksi jarak dekat.
* **Active LOW Relay Trigger**: Respon sakelar mekanis yang cepat dan stabil dalam memicu alarm.
* **Voltage Stability**: Dilengkapi modul *Step Down 5V* (Buck Converter) untuk memastikan arus tetap stabil dan aman bagi komponen.
* **Portable Design**: Tanpa kabel eksternal, memudahkan pemasangan di berbagai sudut ruangan.

---

## 📂 Panduan Navigasi File

Untuk memahami proyek ini lebih dalam, silakan merujuk pada file-file berikut:

1.  **`1_perangkat_alarm.pdf` (Dasar Teori)**
    * Berisi latar belakang proyek, fitur utama, serta tujuan dan manfaat teknis dari sistem ISAS.
2.  **`2_skema_n_komponen.pdf` (Detail Teknis)**
    * Daftar lengkap komponen beserta spesifikasi dan fungsinya dalam rangkaian.
3.  **`3_cara_menyalakan_alat.pdf` (Panduan Operasional)**
    * Instruksi cara menyalakan, melakukan kalibrasi sensor, hingga prosedur pengujian pada pintu.
4.  **Folder `/gambar_alat`**
    * Dokumentasi visual unit yang sudah selesai dirakit.
5.  **Folder `/skema_n_komponen`**
    * Diagram pengabelan (wiring diagram) untuk membantu perakitan ulang.

---

## ⚙️ Spesifikasi Komponen

| Komponen | Fungsi |
| :--- | :--- |
| **Sensor IR** | Mendeteksi rintangan/objek melalui pantulan cahaya inframerah. |
| **Relay 1 Ch (Active LOW)** | Bertindak sebagai sakelar elektronik untuk memutus/menyambung arus alarm. |
| **Buzzer** | Output suara peringatan (alarm). |
| **Baterai 18650** | Sumber daya utama (High Capacity). |
| **Step Down LM2596/Mini** | Menurunkan tegangan baterai ke 5V DC yang stabil. |

---

## 💡 Cara Kerja Singkat

Sistem bekerja dengan prinsip interupsi cahaya:
1.  **Kondisi Tertutup**: Sensor IR mendeteksi pantulan cahaya dari kusen pintu. Output sensor berada pada kondisi *HIGH*, sehingga Relay tidak terpicu.
2.  **Kondisi Terbuka**: Saat pintu dibuka, sensor kehilangan pantulan cahaya. Sinyal berubah menjadi *LOW*, memicu Relay untuk menutup sirkuit Buzzer.
3.  **Alarm Aktif**: Buzzer akan terus berbunyi selama sensor tidak mendeteksi adanya rintangan di depannya.

---

## 🚀 Instalasi Cepat

1.  Tempelkan unit pada daun pintu menggunakan *glue tack* atau baut kecil.
2.  Pastikan moncong sensor menghadap tepat ke arah kusen pintu (jarak ideal 2-10 cm).
3.  Nyalakan sakelar *ON*.
4.  Uji dengan membuka pintu; pastikan buzzer merespons secara *real-time*.

---
*Dibuat untuk keperluan dokumentasi proyek teknis - 2026*
