# Sistem Referensi

Sistem referensi geospasial digunakan untuk memastikan bahwa seluruh data dalam Kesatuan Lanskap Mangrove (KLM) memiliki acuan koordinat yang seragam dan dapat dianalisis serta divisualisasikan secara konsisten dalam berbagai platform pemetaan.

## Sistem Koordinat Geografis

Setiap data KLM harus mengacu pada sistem koordinat geospasial berikut:

- **Sistem Koordinat Geografis**  
  - Datum: WGS 84  
  - EPSG Code: 4326  
  - Format: Derajat Desimal (Decimal Degrees)  
  - Unit: Derajat  
  - Digunakan sebagai sistem acuan utama dalam pertukaran data nasional dan lintas sektor.

## Sistem Proyeksi Peta

- **Proyeksi Web Mercator**  
  - EPSG Code: 3857  
  - Digunakan dalam pemetaan berbasis web (web map), seperti tile rendering dan tampilan publik berbasis web.  
  - Tidak direkomendasikan untuk pengukuran jarak dan luas.

- **Proyeksi Silinder (Cylindrical Projection)**  
  - Direkomendasikan untuk **perhitungan geometri seperti luas dan panjang** pada satuan lanskap.  
  - Contoh sistem proyeksi silinder adalah Transverse Mercator (seperti UTM), yang memberikan hasil lebih akurat untuk penghitungan spasial dalam area lokal.

## Ketentuan Umum

| Jenis Data        | EPSG / Sistem Koordinat         | Format Data        | Tujuan                          |
|-------------------|----------------------------------|---------------------|----------------------------------|
| Vektor Nasional   | EPSG:4326 (WGS 84)              | SHP, GeoJSON        | Pertukaran dan interoperabilitas |
| Raster Web        | EPSG:3857 (Web Mercator)        | COG, MBTiles        | Visualisasi peta daring          |
| Kalkulasi Geometri | EPSG:54034 Cylindrical Equal Area     | GPKG, SHP           | Perhitungan luas, panjang        |

## Catatan

Seluruh data spasial wajib mencantumkan sistem referensi koordinat secara eksplisit dalam metadata untuk memastikan konsistensi dan keterpaduan lintas sistem dan platform.

---

Sistem referensi ini menjadi dasar utama dalam pemrosesan, penyajian, dan interoperabilitas data Kesatuan Lanskap Mangrove baik pada tingkat pusat maupun daerah, serta dalam integrasi ke dalam infrastruktur data spasial nasional.
