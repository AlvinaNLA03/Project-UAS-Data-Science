## LAMPIRAN B. FORMULIR PENGAJUAN IDE (DIKUMPULKAN PADA CHECKPOINT 1)

| Komponen | Isian Mahasiswa |
|----------|-----------------|
| Nama / NIM |  Alvina nur L.A. (244311003) <br> Julyo Firnanda (244311016) <br> Nadia Tifara S. (244311022) |
| Judul ide | Analisis Pola Persebaran Catatan Keanekaragaman Hayati di Indonesia Menggunakan Metode Clustering. |
| SDG & target yang dipilih | SDG 15-Life on Land (Ekosistem Daratan), berfokus pada perlindungan habitat alami,penghentian keanekaragaman hayati, dan perlindunan spesies terancam punah. |
| Masalah nyata yang diangkat | Karena indonesia memiliki keanekaragaman hayati yang tinggi, tetapi informasi mengenai kemunculan dan persebaran spesies belum terdokumentasi secara merata di seluruh wilayah. Data pengamatan yang tersedia juga memiliki perbedaan jumlah catatam berdasarkan lokasi dan waktu. Oleh karena itu, diperlukan analisis untuk mengetahui pola persebaran catatan spesies serta mengelompokkan wilayah berdasarkan karakteristik dan keanekaragaman hayati yang tercatat. |
| Tugas ML (Target & jenis tugas) | Menggunakan pendekatan Unsupervised Learning dengan jenis tugas clustering. Targetnya mengelompokkan unit wilayah berdasarkan karakteristik catatan kemunculan spesies, seperti jumlah catatan, jumlah spesies, jumlah famili, dan komposisi kelompok organisme. |
| Objective & metrik utama | Menghasilkan pengelompokkan wilayah berdasarkan karakteristik catatan keanekaragaman hayati serta membandingkan performa tiga model clustering. Evalusia mengunakan silhouette score sebagai metrikutama, serta davies-bouldin index dan calinski harahabz score sebagai metrik pendukung. |
| Dataset (sumber, URL, ukuran, jenis data) | Global Biodiversity Information Facility (GBIF) – Indonesia Occurrence Data. URL: https://www.gbif.org/occurrence/search?country=ID&has_coordinate=true. Acuan unduhan GBIF pada 26 Februari 2026 memiliki 3.699.109 catatan dari 1.549 dataset sumber. Jumlah akhir disesuaikan dengan filter periode 2015–2025 dan hasil preprocessing. Jenis data: tabular terstruktur dengan atribut spasial dan temporal. Format unduhan: Simple CSV/TSV. |
| Rencana tiga model (baseline / advanced / deep learning) | 1. Baseline: K-Means Clustering, untuk pengelompokan dasar berdasarkan kemiripan karakteristik data. <br> 2. Advanced: Gaussian Mixture Model (GMM), untuk pengelompokan berdasarkan probabilitas keanggotaan cluster. <br> 3. Deep Learning: Deep Embedded Clustering (DEC), untuk mempelajari representasi fitur menggunakan neural network dan melakukan clustering. |
| Risiko & pertimbangan etika (bias, privasi) | Data GBIF berpotensi memiliki bias karena perbedaan intensitas pengamatan, kelengkapan dokumentasi, lokasi, dan kelompok spesies. Jumlah catatan tidak selalu menggambarkan jumlah populasi sebenarnya. Data dengan lokasi spesies sensitif akan ditampilkan dalam bentuk agregasi wilayah untuk menghindari penyalahgunaan informasi. Sumber dan lisensi data akan tetap dicantumkan. |
| Referensi awal (minimal 2) | 1. Setiawan (2022), Keanekaragaman Hayati Indonesia: Masalah dan Upaya Konservasinya. https://doi.org/10.15294/ijc.v11i1.34532 <br> 2. Sanjaya et al. (2017), Pemanfaatan Layanan Web Keanekaragaman untuk Pengelolaan Informasi Tumbuhan Obat Indonesia.https://doi.org/10.29244/jika.4.1.29-34 <br> 3. Turnip dan Fitriana (2023), Clustering Kabupaten Berdasarkan Luas Hutan Menggunakan Metode K-Means di Provinsi Jawa Tengah.https://doi.org/10.24961/j.tek.ind.pert.2023.33.1.1
 

**Kriteria persetujuan dosen:**
- [ ] Ide berasal dari mahasiswa dan tidak duplikat
- [ ] Selaras jelas dengan satu SDG dan targetnya
- [ ] Dapat dirumuskan sebagai masalah ML dengan target yang jelas
- [ ] Dataset tersedia, legal/etis digunakan, dan cukup besar
- [ ] Layak untuk tiga model termasuk deep learning dalam 6 minggu
