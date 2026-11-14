# **Stitch Studio** 

Stitch Studio adalah editor berbasis browser untuk membuat carousel Instagram seamless. Aplikasi ini berjalan sebagai satu file HTML statis dan tidak memerlukan server aplikasi atau proses build. 

## Fitur 

- 100 template carousel dalam 10 kategori, termasuk Gallery Exhibition. 

- Kanvas panorama dengan pembagi slide untuk membantu menyusun desain seamless. 

- Unggah beberapa foto sekaligus, termasuk foto HEIC/HEIF dari iPhone. 

- Isi slot template dengan foto, lalu atur bagian foto yang terlihat dengan menggeser dan memperbesar foto di dalam frame. 

- Tambahkan teks, stiker, bentuk masking, latar, dan tekstur. 

- Undo/redo, pengaturan layer, tema gelap/terang, dan autosave lokal di browser. 

- Ekspor setiap slide sebagai JPG 1080 × 1350 piksel dan unduh semua slide sebagai ZIP jika JSZip tersedia. 

- Tombol Traktir Kopi menuju Saweria: https://saweria.co/aksa30. 

## Menjalankan secara lokal 

1. Unduh scrl_studio_fixed.html . 

2. Buka file tersebut di browser modern, misalnya Chrome, Edge, Firefox, atau Safari. 

3. Untuk menguji hasil export dan aset eksternal dengan lebih konsisten, gunakan koneksi internet karena beberapa pustaka, font, dan foto stok dimuat dari CDN. 

Aplikasi tidak memerlukan instalasi paket atau perintah build. 

## Deploy sebagai website statis 

Unggah scrl_studio_fixed.html ke layanan hosting statis yang Anda gunakan, seperti GitHub Pages, Netlify, atau Cloudflare Pages. Pastikan nama file utama sesuai dengan konfigurasi hosting Anda. Jika layanan mengharuskan file bernama index.html , ubah nama salinan file tersebut menjadi index.html saat deploy. 

README.md hanya dokumentasi dan tidak perlu diunggah ke folder publik website, kecuali memang ingin ditampilkan. 

## Cara menggunakan 

### Memilih template 

1. Buka tab Template. 

2. Cari berdasarkan nama atau pilih kategori, misalnya Gallery Exhibition. 

3. Klik template untuk menerapkannya. Penerapan template mengganti susunan kanvas yang sedang aktif; gunakan Undo bila ingin kembali. 

### Mengisi dan mengatur foto 

1. Klik tombol + pada slot foto, lalu pilih foto dari perangkat. 

2. Setelah foto dimasukkan, mode Geser Foto akan aktif otomatis. 

3. Tarik foto di dalam frame untuk memilih area yang ingin terlihat. Gunakan kontrol zoom atau slider X/Y jika diperlukan. 

4. Tekan Selesai Geser Foto setelah framing sesuai. 

5. Untuk mengatur ulang crop, pilih foto dan gunakan tombol Reset di panel posisi/zoom. 

Untuk foto yang sudah ada di kanvas, klik fotonya lalu pilih Geser Foto di toolbar. 

### Mengedit desain 

- Seret elemen untuk memindahkannya. 

- Pilih elemen untuk menampilkan kontrol yang sesuai. 

- Gunakan tab Foto, Teks, Stiker, Latar, dan Layer untuk menambahkan atau mengatur konten. 

- Gunakan tombol Undo/Redo untuk membatalkan atau mengulangi perubahan. 

### Mengekspor carousel 

1. Klik Export Slides. 

2. Periksa pratinjau setiap slide. 

3. Unduh slide satu per satu atau pilih Download ZIP Semua. 

4. Unggah slide ke Instagram sesuai urutan nomor slide. 

## Penyimpanan dan privasi 

Autosave menggunakan penyimpanan lokal browser ( localStorage ) pada perangkat dan browser yang sedang digunakan. Data tersebut tidak otomatis tersinkron ke perangkat lain 

atau server. Menghapus data situs/browser dapat menghapus workspace yang tersimpan, jadi ekspor hasil penting dan jangan menghapus data situs jika ingin mempertahankan workspace lokal. 

Foto yang dipilih dari perangkat diproses di browser untuk digunakan pada kanvas. File ini tidak menyediakan backend untuk menyimpan project di server. 

## Catatan teknis 

- Rasio slide: 4:5. 

- Resolusi ekspor: 1080 × 1350 piksel per slide. 

- Beberapa library dan aset dimuat dari CDN; koneksi internet diperlukan untuk memuatnya. 

- Jika CDN tidak tersedia, fitur yang bergantung pada library atau aset tersebut dapat tidak berfungsi penuh. 

## Dukungan 

Jika ingin mendukung pengembangan Stitch Studio, gunakan tombol Traktir Kopi di aplikasi atau kunjungi https://saweria.co/aksa30. 

