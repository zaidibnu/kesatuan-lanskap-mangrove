# Konsistensi Logis

Konsistensi logis merujuk pada keteraturan dan kesesuaian internal dalam struktur dan nilai data. Dalam KLM, ini berarti hubungan antar atribut dan geometrinya tidak boleh bertentangan secara semantik maupun spasial.

## Aspek yang Diuji

| Aspek                    | Contoh Ketidakkonsistenan                         |
|--------------------------|--------------------------------------------------|
| Tipe Fungsi & Atribut    | KLM bertipe "Lindung" tetapi status RTRW = Budidaya |
| Overlap Geometri         | Poligon tumpang tindih antara dua KLM            |
| Nilai Atribut Ganda      | Nama KLM sama dengan ID berbeda                  |

## Validasi Konsistensi

- Uji atribut menggunakan domain kontrol (enumerasi nilai).
- Uji spasial: topologi, tumpang tindih, lubang tidak valid (`isValid()`).
- Periksa relasi spasial antar fitur, seperti nested atau overlap.

## Penanganan Inkonsistensi

- Lakukan pembersihan data (`data cleaning`) sebelum pemutakhiran.
- Gunakan log perubahan dan pengesahan ulang jika diperlukan.
