# Metadata

Metadata adalah informasi deskriptif yang menjelaskan karakteristik, struktur, kualitas, dan isi dari data geospasial. Dalam konteks Kesatuan Lanskap Mangrove (KLM), metadata berfungsi untuk mendokumentasikan seluruh aspek teknis dan administratif dari data yang dihasilkan agar dapat ditemukan, diakses, digunakan, dan dipertukarkan secara efektif.

## Tujuan Metadata

Metadata disusun untuk:
- Menjamin keterlacakan asal-usul dan kualitas data.
- Mendukung interoperabilitas antar instansi.
- Memberikan informasi teknis bagi pengguna data.
- Memenuhi standar nasional dan internasional pengelolaan informasi geospasial.

## Standar Acuan

Metadata KLM disusun mengacu pada:
- **SNI ISO 19115-1:2019** – Metadata geospasial inti
- **SNI ISO 19139** – Representasi XML untuk metadata
- **Peraturan Kepala BIG No. 3 Tahun 2016** tentang Standar Nasional Indonesia (SNI) Metadata Geospasial

## Elemen Minimum Metadata

Setiap file data KLM wajib memiliki metadata dengan elemen minimum sebagai berikut:

| Elemen              | Keterangan                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| Judul               | Nama data atau layer (misalnya: KLM_Provinsi_Riau_2024)                     |
| Abstrak             | Ringkasan deskriptif tentang isi dan cakupan data                          |
| Kata kunci          | Term-term penting untuk pencarian metadata (misal: mangrove, KLM, Riau)    |
| Tanggal             | Tanggal pembuatan atau pembaruan data                                       |
| Pembuat             | Instansi atau tim yang bertanggung jawab atas pembuatan data                |
| Kontak              | Informasi kontak teknis (email, unit kerja, nomor telepon)                  |
| Sistem Referensi    | EPSG code dan deskripsi sistem koordinat yang digunakan                     |
| Skala               | Skala nominal atau resolusi spasial                                          |
| Format              | Format file data (misal: SHP, GeoJSON, GPKG)                                |
| Cakupan Wilayah     | Deskripsi atau bounding box wilayah spasial data                            |
| Keterbatasan Akses  | Informasi terkait hak akses dan pembatasan distribusi                      |

## Format Metadata

Metadata disimpan dalam format:
- **XML ISO 19139** untuk interoperabilitas lintas platform
- **YAML/JSON** untuk dokumentasi internal berbasis aplikasi
- **HTML** untuk publikasi dalam katalog metadata daring (geoportal)

## Integrasi Metadata

- Metadata harus dikaitkan langsung (linked) dengan file data utama dan mengikuti struktur folder repositori.
- Metadata juga dapat diintegrasikan dalam platform katalog metadata nasional (misalnya, Geoportal Satu Peta).

---

Dengan metadata yang baik dan sesuai standar, informasi geospasial Kesatuan Lanskap Mangrove dapat dimanfaatkan secara maksimal, baik untuk analisis teknis, perencanaan kebijakan, maupun pertukaran data antar instansi.
