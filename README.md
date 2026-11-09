# Analisis Pola Persebaran Catatan Keanekaragaman Hayati di Indonesia

## Deskripsi

Proyek UAS Data Science ini dirancang untuk menganalisis pola persebaran catatan kemunculan flora dan fauna di Indonesia. Data GBIF akan dikelompokkan berdasarkan karakteristik wilayah dan tahun pengamatan menggunakan metode *clustering*.

## Dataset

Dataset bersumber dari **Global Biodiversity Information Facility (GBIF)** dengan cakupan Indonesia dan periode pengamatan 2015–2025.

Sumber: [GBIF – Occurrence Data Indonesia](https://www.gbif.org/occurrence/search?country=ID&has_coordinate=true)

## Metode

Model yang direncanakan menggunakan pendekatan *Unsupervised Learning*:

- **K-Means** – model baseline.
- **Gaussian Mixture Model (GMM)** – model clustering probabilistik.
- **Deep Embedded Clustering (DEC)** – pendekatan clustering berbasis deep learning.

Evaluasi direncanakan menggunakan *Silhouette Score*, *Davies-Bouldin Index*, dan *Calinski-Harabasz Score*.

## Tujuan

Mengelompokkan wilayah berdasarkan jumlah catatan kemunculan, jumlah spesies, jumlah famili, dan komposisi kelompok organisme. Proyek ini berkaitan dengan **SDG 15 – Life on Land**, khususnya perlindungan keanekaragaman hayati.

> Catatan: jumlah catatan GBIF menunjukkan data pengamatan yang terdokumentasi, bukan jumlah populasi spesies yang sebenarnya.

## Struktur Repository

```text
Project-UAS-Data-Science/
├── Docs/
│   ├── 09_LAMPIRAN_B.md
│   ├── 09_minggu9.md
│   └── Laporan_Proyek_ML_LMOP.md
└── README.md
```

## Tim

- Alvina Nur L.A. — 244311003
- Julyo Firnanda — 244311016
- Nadia Tifara S. — 244311022

## Dokumentasi

Dokumentasi dan laporan proyek tersedia di folder [`Docs`](./Docs/).
