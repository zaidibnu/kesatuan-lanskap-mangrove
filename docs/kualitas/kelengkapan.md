# Kelengkapan Data

Kelengkapan data adalah ukuran sejauh mana seluruh elemen yang diperlukan dalam satu unit data geospasial telah tersedia dan terdokumentasi dengan baik. Dalam konteks KLM, kelengkapan mencakup informasi spasial (geometri) dan non-spasial (atribut) yang dibutuhkan untuk pemetaan, pengelolaan, dan analisis lanjutan.

## Komponen yang Wajib Ada

| Komponen            | Deskripsi                                               |
|---------------------|---------------------------------------------------------|
| Geometri            | Poligon valid tanpa kesalahan topologi                 |
| Nama KLM            | Identifikasi unit lanskap yang unik                    |
| Fungsi Ekosistem    | Klasifikasi (Lindung, Budidaya, Zona Transisi)         |
| Tipologi Ekologis   | Informasi geomorfologi, substrat, salinitas            |
| Metadata            | Dokumen deskriptif sesuai SNI ISO 19115               |

## Standar Kelengkapan

- **≥ 95%** fitur wajib memiliki nilai atribut yang lengkap.
- Data geometris tidak boleh memiliki `NULL` atau `MULTIPART` tidak valid.
- Semua entitas harus memiliki metadata yang memadai dan up-to-date.

## Penanganan Kekurangan

Fitur yang belum lengkap harus:
- Ditandai dengan `status = 'tidak lengkap'`
- Diberi catatan pada metadata untuk proses pemutakhiran
