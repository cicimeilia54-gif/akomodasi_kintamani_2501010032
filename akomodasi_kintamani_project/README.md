# Akuisisi Data Akomodasi Kecamatan Kintamani

Repositori ini dibuat untuk memenuhi tugas praktikum mata kuliah **BIFP-243 Akuisisi dan Manajemen Data**.

## Tujuan Tugas
Mengakuisisi data akomodasi (hotel, villa, guest house, dll.) di Kecamatan Kintamani dari OpenStreetMap (OSM) secara etis, membersihkannya, melakukan uji kelengkapan terhadap data resmi BPS, serta mendokumentasikannya secara lengkap[cite: 9, 10, 15].

## Sumber Data
1. **OpenStreetMap (Overpass API):** Data spasial titik akomodasi[cite: 10].
2. **BPS Kabupaten Bangli / Kecamatan Kintamani Dalam Angka:** Sebagai pembanding jumlah akomodasi (46 unit, tingkat kelengkapan 69.57%)[cite: 3, 10].

## Atribusi
> "© OpenStreetMap contributors"[cite: 10, 15]
Lisensi data mengikuti Open Database License (ODbL)[cite: 10, 15].

## Struktur Direktori
- `data/raw/`: Berisi respons mentah JSON dari Overpass API.
- `data/interim/`: Berisi dataset CSV bersih (`akomodasi_kintamani.csv`).
- `notebooks/`: Berisi script Jupyter Notebook utama (`akuisisi_akomodasi.ipynb`).
- `docs/`: Berisi query, provenance, data dictionary, etika data, dan perbandingan BPS.
- `reports/`: Berisi laporan akhir format PDF.

## Cara Menjalankan Ulang
1. Buka file utama di folder `notebooks/` menggunakan Google Colab.
2. Pilih menu **Runtime > Run All** untuk menjalankan seluruh sel dari awal sampai akhir[cite: 16].
