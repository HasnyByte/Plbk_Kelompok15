# Map Marker

Proyek ini adalah aplikasi web sederhana yang menampilkan peta interaktif dengan marker lokasi menggunakan library Leaflet. Peta menunjukkan berbagai lokasi menarik di wilayah Aceh dengan informasi deskripsi untuk setiap marker.

## Struktur Proyek

- `Kelompok15/`: Folder utama proyek
  - `index.html`: Halaman web utama yang menampilkan peta
  - `marker.js`: File JavaScript yang berisi data marker lokasi

## Cara Menjalankan

1. Buka folder `Kelompok15`
2. Klik dua kali pada file `index.html` untuk membukanya di browser web
3. Peta akan dimuat dengan marker-marker yang telah ditambahkan

## Menambah Marker

Untuk menambah marker baru:

1. Buka file `marker.js`
2. Tambahkan objek baru ke array `markersNamaAnggota` dengan format:
   ```javascript
   {
     nama: "Nama Lokasi",
     lat: 5.5497,
     lng: 95.3175,
     deskripsi: "Deskripsi lokasi"
   }
   ```
3. Simpan file dan refresh halaman `index.html` di browser

## Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript
- Leaflet (library peta)
- OpenStreetMap (tiles peta)

Proyek ini dibuat untuk tujuan pembelajaran dan tracking commit harian.
