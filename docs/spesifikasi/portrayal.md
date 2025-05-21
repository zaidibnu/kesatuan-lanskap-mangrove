# Portrayal (Simbolisasi)

Portrayal atau simbolisasi adalah representasi visual dari informasi geospasial dalam peta, yang bertujuan untuk menyampaikan makna data secara jelas dan konsisten. Dalam konteks Kesatuan Lanskap Mangrove (KLM), simbolisasi berperan penting untuk membedakan berbagai fungsi, status, dan elemen dalam satuan lanskap secara intuitif, baik di peta cetak maupun aplikasi digital.

## Tujuan Simbolisasi

- Menyajikan fungsi dan karakteristik KLM secara visual.
- Membedakan kelas-kelas data secara tematik.
- Mendukung keterbacaan dan interpretasi data di berbagai skala.
- Menstandarkan tampilan antar wilayah dan antar platform (web, desktop, cetak).

## Elemen yang Disimbolkan

| Elemen                  | Jenis Representasi | Keterangan                                              |
|--------------------------|---------------------|----------------------------------------------------------|
| Batas KLM               | Garis tebal putus-putus (stroke) | Penegasan batas unit lanskap                            |
| Fungsi Lindung          | Poligon berwarna hijau gelap     | Area mangrove dengan status lindung                     |
| Fungsi Budidaya         | Poligon berwarna cokelat muda    | Area yang diperbolehkan untuk pemanfaatan terbatas      |
| Zona Transisi           | Poligon berwarna kuning atau oranye semi transparan | Area antara lindung dan budidaya                  |
| Titik Survey            | Titik lingkar kecil berwarna merah | Lokasi groundcheck/spasial sampling                     |
| CVI (Kerentanan Pesisir)| Gradien warna (biru → merah)     | Nilai kerentanan pesisir dari rendah ke tinggi          |

## Standar Warna (Palet Tematik)

| Fungsi Ekosistem        | Warna        | Kode Hex |
|-------------------------|--------------|----------|
| Lindung                | Hijau tua    | `#005952` |
| Budidaya               | Cokelat muda | `#d2b48c` |
| Zona Transisi          | Kuning-Oranye semi transparan | `#ffc10780` |
| Tidak diklasifikasi    | Abu-abu      | `#c0c0c0` |

## Format File Simbolisasi

- **SLD (Styled Layer Descriptor)**: Untuk interoperabilitas dengan GeoServer dan QGIS.
- **QML**: Template simbolisasi untuk QGIS.
- **CartoCSS / Mapbox Style**: Untuk pemetaan berbasis web (Mapbox GL, MapLibre).
- **PNG/SVG Legend**: Untuk keperluan pencetakan dan penjelasan legenda peta.

## Aplikasi Penerapan

- **Peta Album KLM**: Menampilkan seluruh unit KLM per provinsi dan fungsi-fungsinya.
- **Geoportal & WebGIS**: Simbolisasi berbasis tile map dan layer interaktif.
- **Laporan Teknis**: Peta berskala besar untuk analisis spasial, presentasi, dan publikasi.

---

Simbolisasi yang standar dan terdokumentasi akan memudahkan pemangku kepentingan dalam membaca, menafsirkan, dan menggunakan data KLM untuk berbagai kebutuhan tata kelola wilayah pesisir dan konservasi mangrove.
