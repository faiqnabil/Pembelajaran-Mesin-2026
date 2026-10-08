# Praktikum Pembelajaran Mesin

Repository ini berisi hasil pengerjaan praktikum mata kuliah **Pembelajaran Mesin (RTI235004)** berdasarkan **Modul Praktikum Pembelajaran Mesin 2025–2026** dari Jurusan Teknologi Informasi.

## Tentang Mata Kuliah

Pembelajaran Mesin mempelajari bagaimana mesin dapat meniru kemampuan kognitif manusia untuk menyelesaikan berbagai permasalahan. Praktikum tidak hanya membahas pembuatan model kecerdasan buatan, tetapi juga memahami tahapan pengembangan model serta etika dalam penggunaan teknologi kecerdasan buatan.

## Tujuan Praktikum

Praktikum ini bertujuan untuk memberikan pengalaman langsung dalam:

- memahami konsep dasar pembelajaran mesin;
- memahami dan menganalisis data;
- melakukan pra-pengolahan data;
- melakukan ekstraksi fitur;
- membangun model regresi;
- melakukan clustering;
- membangun model klasifikasi;
- melakukan evaluasi model;
- memahami proses penyajian atau deployment model.

## Materi Praktikum

Materi yang dipelajari dalam modul meliputi:

1. **Pengenalan Pembelajaran Mesin**
2. **Data Understanding**
3. **Pre Processing**
4. **Features Extraction**
5. **Regression**
6. **Clustering**
7. **Classification**
8. **Model Evaluation**
9. **Model Deployment**

## Struktur Praktikum

Repository ini berisi hasil pengerjaan praktikum yang disusun berdasarkan urutan materi pada modul.

```text
Praktikum-Pembelajaran-Mesin/
│
├── JS01/
│   └── Pengenalan Pembelajaran Mesin
│
├── JS02/
│   └── Data Understanding
│
├── JS03/
│   └── Features Extraction
│
├── JS04/
│   └── Regression
│
├── JS05/
│   └── Clustering
│
├── JS06/
│   └── Classification
│
├── JS07/
│   └── Model Evaluation
│
└── JS08/
    └── Model Deployment
```

> Struktur folder dapat disesuaikan dengan pembagian jobsheet yang digunakan dalam perkuliahan.

## JS05 — Klasterisasi Hierarki

Salah satu materi yang dikerjakan dalam repository ini adalah **JS05 – Klasterisasi Hierarki**.

Pada JS05 dipelajari teknik clustering menggunakan **HDBSCAN (Hierarchical Density-Based Spatial Clustering of Applications with Noise)**.

Materi praktikum meliputi:

- penggunaan HDBSCAN;
- perbandingan HDBSCAN dengan DBSCAN;
- pengaruh skala terhadap hasil clustering;
- clustering pada data dengan kepadatan berbeda;
- eksperimen `min_cluster_size`;
- eksperimen `min_samples`;
- penggunaan `cut_distance`;
- evaluasi hasil clustering menggunakan Silhouette Score;
- evaluasi menggunakan Davies-Bouldin Index;
- visualisasi hasil clustering.

### Tugas JS05

Pada tugas JS05 digunakan dataset nyata dari `sklearn.datasets`. Proses pengerjaan meliputi:

1. memilih dataset;
2. melakukan clustering menggunakan HDBSCAN;
3. menentukan jumlah cluster;
4. menentukan jumlah noise;
5. melakukan visualisasi hasil clustering menggunakan reduksi dimensi jika diperlukan;
6. membandingkan hasil clustering dengan label asli dataset.

## Tools dan Library

Praktikum menggunakan Python beserta beberapa library yang digunakan sesuai kebutuhan setiap jobsheet, antara lain:

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- HDBSCAN

## Referensi

Modul utama yang digunakan dalam pengerjaan praktikum:

**Modul Praktikum Pembelajaran Mesin 2025–2026**  
Mata Kuliah: **RTI235004 – Pembelajaran Mesin**

[Modul Praktikum Pembelajaran Mesin](https://polinema.gitbook.io/jti-modul-praktikum-pembelajaran-mesin-2025-2026)

## Keterangan

Repository ini dibuat sebagai dokumentasi hasil pengerjaan praktikum mata kuliah **Pembelajaran Mesin**. Seluruh pengerjaan mengikuti instruksi dan materi yang terdapat pada modul praktikum.
