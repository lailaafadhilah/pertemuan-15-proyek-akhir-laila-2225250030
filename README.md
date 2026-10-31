# Program Rekap dan Analisis Nilai Matematika Kelas

## Identitas Proyek

| Keterangan | Identitas |
|---|---|
| Nama | Laila fadhilah |
| NIM | 2225250030 |
| Kelas | 3A |
| Program Studi | Pendidikan Matematika |
| Mata Kuliah | Algoritma dan Pemrograman |
| Pertemuan | 15 |
| Jenis Proyek | Individu |

## Deskripsi Proyek

Program Rekap dan Analisis Nilai Matematika Kelas merupakan program yang digunakan untuk mengolah data nilai siswa.

Program membaca data siswa dari file, melakukan validasi nilai, menghitung rata-rata, menentukan nilai tertinggi dan terendah, serta menentukan status kelulusan berdasarkan KKM.

Hasil pengolahan data ditampilkan pada terminal dan disimpan dalam file laporan.

## Tujuan

| No. | Tujuan |
|---|---|
| 1 | Mengimplementasikan rancangan proyek dari Pertemuan 14. |
| 2 | Mengolah data nilai siswa menggunakan Python. |
| 3 | Menerapkan fungsi dan struktur data. |
| 4 | Menerapkan pengolahan file. |
| 5 | Melakukan pengujian terhadap program. |
| 6 | Mendokumentasikan hasil implementasi proyek. |

## Fitur Program

| No. | Fitur |
|---|---|
| 1 | Membaca data nilai siswa dari file. |
| 2 | Memvalidasi nilai siswa pada rentang 0 sampai 100. |
| 3 | Menghitung rata-rata nilai. |
| 4 | Menentukan nilai tertinggi dan terendah. |
| 5 | Menentukan status kelulusan siswa. |
| 6 | Menampilkan hasil analisis nilai. |
| 7 | Menyimpan laporan hasil analisis ke file. |

## Kebutuhan

| No. | Kebutuhan |
|---|---|
| 1 | Python 3 |
| 2 | Visual Studio Code |

## Struktur Folder

```text
pertemuan-15-proyek-akhir-ziana-2225250076/
├── README.md
├── .gitignore
├── main.py
├── src/
│   ├── __init__.py
│   ├── input_data.py
│   ├── proses.py
│   └── output.py
├── data/
│   └── contoh_data.txt
├── tests/
│   └── test_case.md
├── docs/
│   └── screenshot/
└── output/
```

## Cara Menjalankan

| No. | Langkah |
|---|---|
| 1 | Buka folder proyek di Visual Studio Code. |
| 2 | Pastikan Python 3 sudah tersedia. |
| 3 | Buka terminal pada folder proyek. |
| 4 | Jalankan perintah `python main.py`. |
| 5 | Program membaca data dari `data/contoh_data.txt`. |
| 6 | Hasil analisis ditampilkan pada terminal. |
| 7 | Laporan disimpan pada `output/laporan_nilai.txt`. |

## Pengujian

| No. | Kondisi Pengujian | Tujuan |
|---|---|---|
| 1 | Input data normal | Memastikan data diproses dengan benar. |
| 2 | Nilai minimum (0) | Memastikan nilai 0 diterima. |
| 3 | Nilai maksimum (100) | Memastikan nilai 100 diterima. |
| 4 | Nilai di luar batas | Memastikan nilai tidak valid ditolak. |
| 5 | Input bukan angka | Memastikan data selain angka ditangani. |
| 6 | File tidak ditemukan | Memastikan kesalahan file ditangani. |
| 7 | Data kosong | Memastikan program menangani data kosong. |

Hasil pengujian dicatat pada file `tests/test_case.md`.

## Debugging

Apabila ditemukan kesalahan saat program dijalankan, dilakukan pemeriksaan terhadap kode program dan perbaikan pada bagian yang bermasalah.

Program kemudian dijalankan kembali untuk memastikan perbaikan berjalan sesuai kebutuhan.

## Kontribusi

Proyek ini dikerjakan secara individu oleh Ziana Alfia Zahra.

Seluruh proses perancangan, implementasi, pengujian, debugging, dan dokumentasi dilakukan secara mandiri.

## Referensi

1. Bahan Ajar Pertemuan 14: Perancangan Proyek dengan VS Code dan GitHub.
2. Bahan Ajar Pertemuan 15: Implementasi, Pengujian, dan Dokumentasi Proyek.