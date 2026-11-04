# Pertemuan 11 - Dictionary/Map

**Nama:** Sela Widiyanti 
**NIM:** 2225250176 
**Kelas:** 3F

## 1. Tujuan

Mempelajari penggunaan dictionary dalam Python untuk menyimpan data menggunakan pasangan key-value, mengakses data berdasarkan key, menambah dan mengubah data, serta mengolah data mahasiswa menggunakan fungsi.

## 2. Materi yang Dipelajari

Materi pada pertemuan 11 meliputi:
- Membuat dictionary dengan pasangan key-value.
- Mengakses data menggunakan key.
- Menggunakan `get()` untuk mengakses data dengan aman.
- Menambah, mengubah, dan menghapus data.
- Menggunakan `keys()`, `values()`, dan `items()`.
- Membuat dictionary bersarang.
- Menggunakan dictionary di dalam fungsi.
- Mengolah data mahasiswa menggunakan dictionary.

## 3. Struktur Data

Program menggunakan dictionary untuk menyimpan data mahasiswa.

NIM digunakan sebagai **key utama**, sedangkan value berupa dictionary yang berisi:
- Nama mahasiswa.
- Kelas mahasiswa.
- Nilai mahasiswa.

Contoh:

```python
"A001": {
    "nama": "Ayu",
    "kelas": "A",
    "nilai": 85
}
```

Dengan struktur tersebut, data mahasiswa dapat dicari secara langsung menggunakan NIM.

## 4. Struktur Folder

```text
pertemuan-11-dictionary-NIM/
│
├── README.md
├── .gitignore
│
├── latihan/
│   ├── 01_dasar_dictionary.py
│   ├── 02_akses_get.py
│   ├── 03_manipulasi_dictionary.py
│   ├── 04_iterasi_dictionary.py
│   ├── 05_dictionary_bersarang.py
│   └── 06_fungsi_dictionary.py
│
└── praktik/
    └── data_mahasiswa.py
```

## 5. Cara Menjalankan Program

Pastikan Python sudah terpasang dan folder proyek sudah dibuka melalui VS Code.

Untuk menjalankan program utama, buka terminal kemudian ketik:

```bash
python praktik/data_mahasiswa.py
```

Untuk menjalankan file latihan, gunakan perintah sesuai nama file. Contoh:

```bash
python latihan/01_dasar_dictionary.py
```

## 6. Test Case

| No. | Pengujian | Input/Aksi | Hasil |
|---|---|---|---|
| 1 | Pencarian tersedia | A003 | Data Citra ditampilkan |
| 2 | Pencarian tidak tersedia | A999 | Data tidak ditemukan |
| 3 | Pembaruan nilai | A002 menjadi 82 | Nilai berubah menjadi 82 |
| 4 | Penambahan data | A006 | Data Fajar berhasil ditambahkan |
| 5 | Rekap data | Menggunakan items() | Seluruh data mahasiswa ditampilkan |
| 6 | Rata-rata nilai | Seluruh data mahasiswa | 83.50 |

## 7. Refleksi

Dari kegiatan praktik ini, saya memahami bahwa dictionary dapat digunakan untuk menyimpan data dengan pasangan key-value sehingga pencarian menjadi lebih mudah. Kesalahan yang dapat terjadi adalah KeyError ketika mengakses key yang tidak tersedia. Untuk mengatasinya, saya menggunakan metode `get()` agar program dapat mengakses data dengan lebih aman.

Selain itu, saya juga memahami cara menambahkan, mengubah, dan menampilkan data menggunakan dictionary serta menggabungkannya dengan fungsi untuk mengolah data mahasiswa.

## 8. Kesimpulan

Dictionary merupakan salah satu struktur data Python yang berguna untuk menyimpan informasi berdasarkan key. Melalui praktik ini, saya dapat menerapkan dictionary dalam pengelolaan data mahasiswa, mulai dari pencarian, penambahan, perubahan, hingga menghitung rata-rata nilai.

## 9. Sumber

1. Bahan Ajar Algoritma dan Pemrograman Pertemuan 11 - Dictionary/Map.
2. Python Software Foundation - Python 3 Documentation: Data Structures - Dictionaries.
3. Visual Studio Code Documentation - Python in Visual Studio Code.