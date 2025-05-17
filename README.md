# Analisis Pasar Petani (FARMER.py)

## Gambaran Umum
Script Python ini menganalisis data pasar petani di seluruh Amerika Serikat, memberikan wawasan tentang distribusi pasar, penawaran produk, dan pola regional. Analisis ini menggunakan dataset yang telah dibersihkan (`markets_cleaned.csv`) yang berisi informasi tentang pasar petani di berbagai negara bagian.

## Persyaratan
- Python 3.x
- Library yang Dibutuhkan:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - folium
  - geopandas
  - branca

## Fitur
Analisis ini mencakup:

### 1. Distribusi Pasar
- Analisis distribusi pasar berdasarkan negara bagian
- 10 negara bagian teratas dengan pasar petani terbanyak
- Visualisasi diagram lingkaran dari distribusi pasar

### 2. Durasi Operasional
- Analisis bulan-bulan operasi
- Distribusi durasi operasi pasar
- Korelasi antara durasi operasi dan jumlah produk

### 3. Analisis Produk
- Analisis produk populer
- Analisis korelasi produk
- Pola distribusi produk regional
- Perbandingan negara bagian pesisir vs non-pesisir

### 4. Analisis Geografis
- Visualisasi peta interaktif menggunakan Folium
- Visualisasi kepadatan pasar
- Analisis efisiensi pasar berdasarkan negara bagian

### 5. Metrik Efisiensi Pasar
- Jumlah pasar per juta penduduk
- Analisis variasi produk
- Peringkat efisiensi berdasarkan negara bagian

## Temuan Utama

1. **Distribusi Pasar**
   - New York dan California memimpin dalam jumlah pasar
   - 10 negara bagian teratas menyumbang ~44,2% dari semua pasar

2. **Pola Operasional**
   - Sebagian besar pasar beroperasi selama 5-6 bulan
   - Jumlah pasar yang beroperasi sepanjang tahun cukup signifikan

3. **Tren Produk**
   - Sayuran adalah produk yang paling umum
   - Korelasi kuat antara pasangan produk tertentu
   - Variasi regional dalam penawaran produk

4. **Wawasan Geografis**
   - Negara bagian pesisir menunjukkan pola produk yang berbeda
   - Vermont memimpin dalam efisiensi pasar
   - Jumlah penduduk berkorelasi dengan jumlah pasar

## Sumber Data
Analisis menggunakan `markets_cleaned.csv`, yang berisi data yang telah dibersihkan tentang pasar petani termasuk:
- Informasi lokasi
- Jadwal operasional
- Penawaran produk
- Data populasi negara bagian

## Penggunaan
Untuk menjalankan analisis:
1. Pastikan semua library yang diperlukan telah terpasang
2. Tempatkan file `markets_cleaned.csv` di direktori yang sama
3. Jalankan script menggunakan Python:
   ```bash
   python FARMER.py
   ```

## Visualisasi
Script ini menghasilkan berbagai visualisasi termasuk:
- Grafik batang distribusi pasar
- Peta panas korelasi produk
- Visualisasi geografis
- Plot distribusi statistik
