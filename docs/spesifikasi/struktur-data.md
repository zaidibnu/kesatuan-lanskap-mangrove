# Struktur & Isi Data

Spesifikasi informasi geospasial Kesatuan Lanskap Mangrove (KLM) mencakup struktur dan klasifikasi data yang dirancang untuk menjamin interoperabilitas, konsistensi, dan akurasi dalam pengelolaan data tematik mangrove. Komponen struktur data disusun mengikuti prinsip klasifikasi hierarkis dan atribut deskriptif yang relevan terhadap kebutuhan tata ruang dan konservasi.

## Klasifikasi dan Struktur Data

Struktur data KLM terdiri dari entitas spasial poligon yang merepresentasikan unit lanskap mangrove pada skala minimum 1:50.000. Setiap fitur dilengkapi dengan atribut utama sebagai berikut:

| No | Field Name | Tipe Data | Deskripsi |
|----|------------|-----------|-----------|
| 1  | `OID`      | Integer   | Kode fitur objek unik |
| 2  | `WPEM`     | String    | Wilayah Pembentuk Ekosistem Mangrove |
| 3  | `KLM`      | String    | Nama Kesatuan Lanskap Mangrove |
| 4  | `SKLM`     | String    | Sub-Kesatuan Lanskap Mangrove |
| 5  | `UPM`      | String    | Unit Pengelolaan Mangrove |
| 6  | `TIPOLOGI` | String    | Tipologi mangrove (fringe, basin, riverine, overwash, dwarf) |
| 7  | `SLAH`     | String    | Sistem Lahan (misal: KJP, KHY) |
| 8  | `FKAWASAN`| String    | Fungsi kawasan hutan |
| 9  | `FKLM`     | String    | Fungsi KLM (lindung/budidaya) |
| 10 | `LUAS`     | Decimal   | Luas area dalam hektar |

## Hierarki Data

Struktur KLM juga mengikuti hierarki sebagai berikut:

- **WPEM (Wilayah Pembentuk Ekosistem Mangrove)**  
  Unit spasial awal yang terbentuk dari substrat, dinamika pesisir, dan potensi habitat.

- **KLM (Kesatuan Lanskap Mangrove)**  
  Unit lanskap utama yang mencerminkan batas ekosistem dan konteks sosial-ekonomi.

- **SKLM (Sub-Kesatuan Lanskap Mangrove)**  
  Unit analisis lanjutan untuk klasifikasi berdasarkan kedekatan tipologi dan geomorfologi.

- **UPM (Unit Pengelolaan Mangrove)**  
  Unit terkecil berupa mosaik vegetasi atau satuan pengelolaan spesifik.

## Format Data

Struktur data disajikan dalam format shapefile (.shp) dan/atau geodatabase (.gdb) dengan sistem koordinat yang sesuai. Setiap layer harus disertai metadata spasial dan referensi atribut yang konsisten.

## Catatan

Struktur dan isi data ini mengikuti standar minimum dari SNI ISO 19131 dan SNI ISO 19157, serta disesuaikan dengan kebutuhan pengelolaan kawasan berbasis ekosistem mangrove secara nasional:contentReference[oaicite:0]{index=0}.
