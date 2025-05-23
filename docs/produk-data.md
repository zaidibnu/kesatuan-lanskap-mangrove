# Identifikasi Produk Data

Identifikasi produk data merupakan komponen penting untuk memastikan setiap set data Kesatuan Lanskap Mangrove (KLM) dapat dikenali, dilacak asal-usulnya, dan digunakan secara tepat sesuai konteks dan tujuannya. Hal ini mencakup penamaan, kode referensi, deskripsi tematik, wilayah cakupan, dan status publikasi.

## Tujuan Identifikasi

- Menjamin keterlacakan sumber data dan proses pembuatannya.
- Menyediakan informasi ringkas namun lengkap untuk kebutuhan katalog dan interoperabilitas.
- Mendukung sistem pencatatan dan pemantauan versi produk KLM.

## Komponen Identifikasi

| Elemen               | Penjelasan                                                                 |
|----------------------|---------------------------------------------------------------------------|
| Nama Produk          | Nama resmi unit data, misalnya `KLM_Provinsi_Kaltim_2024`                 |
| ID Unik              | Kode identifikasi sistematis, misalnya `KLM-KALTIM-2024-002`              |
| Provinsi             | Lokasi administratif utama                                                |
| Tahun Produksi       | Tahun data dikompilasi dan dipublikasi                                    |
| Tipe Data            | Vektor Poligon / Raster / Metadata / Dokumen Teknis                       |
| Fungsi Dominan       | Lindung / Budidaya / Campuran                                             |
| Status Verifikasi    | Draft / Diverifikasi / Final                                               |
| Institusi Penyusun   | Instansi pelaksana kegiatan (mis. PPEPD, UGM, IPB)                        |
| Instansi Pemilik Data| Pemegang hak pakai dan distribusi (mis. Kementerian Lingkungan Hidup)     |
| Nomor & Tanggal Rilis| Nomor surat atau dokumen pengesahan                                      |

## Contoh Identifikasi

```yaml
produk_id: KLM-SUMUT-2024-001
nama: Kesatuan Lanskap Mangrove Provinsi Sumatera Utara 2024
provinsi: Sumatera Utara
tahun: 2024
fungsi: Lindung dan Budidaya
status: Final
instansi_penyusun: Fakultas Kehutanan dan Lingkungan, IPB University
instansi_pemilik: Direktorat PPEPD, Kementerian Lingkungan Hidup
rilis: SK.123/KLM/PPEPD/2024 - 12 Januari 2024