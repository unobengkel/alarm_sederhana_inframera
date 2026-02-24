Tentu, Fabian. Ini adalah rancangan file **README.md** yang disusun untuk mempermudah audiens di Instagram atau siapa pun yang mengakses folder tersebut dalam memahami proyek **Infrared Security Alert System (ISAS)** milikmu.

---

# Infrared Security Alert System (ISAS) 🚨

**Sistem Alarm Keamanan Mandiri Berbasis Sensor Inframerah (IR Barrier Alert)**

Proyek ini adalah solusi keamanan praktis dan ekonomis untuk memproteksi area pribadi seperti pintu, jendela, atau lemari penyimpanan tanpa bergantung pada instalasi kabel listrik rumah. Menggunakan logika *Active LOW*, sistem ini memberikan respon instan berupa suara saat terjadi interupsi pada sensor.

## 🛠 Fitur Utama

* 
**Dual 18650 Power Cell**: Kapasitas daya besar untuk durasi operasional yang lama.


* 
**Precision IR Detection**: Sensitivitas deteksi yang dapat diatur untuk akurasi tinggi.


* 
**Active LOW Relay Trigger**: Respons cepat dalam memicu alarm melalui sistem relay yang stabil.


* 
**Voltage Stability**: Dilengkapi regulator Step Down 5V (Buck Converter) untuk melindungi komponen dari kelebihan tegangan.


* 
**Standalone & Portable**: Berkat tenaga baterai dan casing mandiri, alat ini mudah dipindahkan atau ditempel di mana saja.



---

## 📂 Panduan Navigasi File

Gunakan file-file di bawah ini untuk memahami proyek secara mendalam:

1. 
**`1_perangkat_alarm.pdf` (Dasar Teori & Konsep)** 


* Berisi latar belakang proyek, fitur utama, serta tujuan dan manfaat pembuatan alat ini.




2. 
**`2_skema_n_komponen.pdf` (Detail Teknis)** 


* Daftar lengkap komponen yang digunakan (Sensor IR, Relay, Buzzer, Step Down, dll.) beserta penjelasan fungsinya masing-masing.




3. 
**`3_cara_menyalakan_alat.pdf` (Tutorial & Pengujian)** 


* Panduan operasional cara menyalakan alat, melakukan kalibrasi jarak sensor, hingga prosedur instalasi pada pintu untuk pengujian lapangan.




4. **Folder `/gambar_alat**`
* Dokumentasi visual unit ISAS yang sudah jadi.


5. **Folder `/skema_n_komponen**`
* Diagram sirkuit dan detail perkabelan antar modul.



---

## 💡 Cara Kerja Singkat

Sistem ditenagai oleh dua baterai 18650 yang tegangannya diturunkan menjadi 5V melalui modul Step Down. Arus ini menghidupkan Sensor IR yang terus memancarkan sinar inframerah.

* 
**Kondisi Aman (Pintu Tertutup)**: Sensor mendeteksi pantulan cahaya dari pintu/kusen; alarm tetap diam.


* 
**Kondisi Pelanggaran (Pintu Terbuka)**: Sensor kehilangan pantulan cahaya, mengirim sinyal *LOW* ke Relay, dan seketika membunyikan Buzzer.



---

## ⚙️ Komponen Utama

| Komponen | Fungsi Utama |
| --- | --- |
| **Sensor IR** | Mendeteksi rintangan/objek di depan pintu.

 |
| **Relay 1 Ch (Active LOW)** | Sakelar elektronik untuk memicu alarm.

 |
| **Buzzer** | Indikator audio atau sirine peringatan.

 |
| **Baterai 18650 (2 Sel)** | Sumber daya mandiri (7.4V - 8.4V).

 |
| **Regulator Step Down** | Penurun tegangan ke 5V yang stabil untuk sirkuit.

 |

---

Apakah kamu ingin saya membuatkan draf *caption* Instagram yang menarik untuk mempromosikan file README dan proyek ini?
