# Bahan latihan Quiz Maker: bank soal pecahan

[Tutorial penggunaan](../panduan/03-demo-multi-agent.md)

**Untuk fasilitator/guru. File ini berisi kunci.** Jangan unggah ke agent yang dapat diakses siswa dalam deployment nyata. Soal ditulis untuk workshop dan bukan kutipan bank soal penerbit.

## Lembar soal

1. Hitung `2/7 + 3/7`.
2. Hitung `5/6 - 1/6` dan sederhanakan.
3. Hitung `1/2 + 1/3`.
4. Hitung `3/4 - 1/2`.
5. Sebuah pita dipotong `1/3` meter, lalu `1/4` meter. Berapa meter jumlah potongan pita?
6. Seorang siswa menulis `1/2 + 1/3 = 2/5`. Jelaskan kesalahannya dan perbaiki.

## Kunci dan pembahasan guru

| Nomor | Kunci | Pembahasan |
|---|---|---|
| 1 | `5/7` | Penyebut sama; pembilang 2 + 3 = 5 |
| 2 | `2/3` | 5/6 - 1/6 = 4/6, sederhanakan dengan membagi pembilang dan penyebut oleh 2 |
| 3 | `5/6` | 1/2 = 3/6; 1/3 = 2/6; hasil 5/6 |
| 4 | `1/4` | 1/2 = 2/4; 3/4 - 2/4 = 1/4 |
| 5 | `7/12` meter | 1/3 = 4/12; 1/4 = 3/12; total 7/12 |
| 6 | `5/6` | Penyebut bukan untuk dijumlahkan; samakan penyebut sebelum menjumlahkan pembilang |

## Penggunaan oleh agent

- Jika diminta lima soal dari bank ini, pilih tepat lima, tidak harus menampilkan seluruh enam.
- Pisahkan lembar siswa dari kunci dan pembahasan.
- Jika membuat soal baru, tandai sebagai variasi baru.
- Periksa operasi, satuan, penyederhanaan, dan konsistensi jawaban.
- Pemeriksaan agent tidak menggantikan perhitungan ulang oleh guru.
