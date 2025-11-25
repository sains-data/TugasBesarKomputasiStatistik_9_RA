# ⚡ Analisis Proyeksi dan Tren Kebutuhan Daya Listrik Provinsi Lampung Tahun 2025-2030

## 🧑‍💻 Tim Komstat 9 RA

Repositori ini adalah hasil dari Tugas Besar mata kuliah Komputasi Statistika. [cite_start]Fokus utama proyek adalah prediksi (forecasting) kebutuhan daya listrik Provinsi Lampung menggunakan metode statistik sederhana yang diimplementasikan melalui **Pemrograman Fungsi R**.

---

## 🎯 Ringkasan Tujuan dan Hasil

### Tujuan Proyek
1.  Menganalisis pola historis kebutuhan daya listrik di Provinsi Lampung.
2.  Menghasilkan proyeksi kebutuhan listrik untuk tahun 2025–2030 menggunakan metode pemrograman R.
3.  Menentukan tingkat pertumbuhan konsumsi listrik setiap tahun dalam periode proyeksi tersebut.

### Hasil Kunci (Periode 2025–2030)
* **Tren:** Kebutuhan daya listrik mengalami tren kenaikan yang **konsisten dan linier**.
* **Proyeksi Kebutuhan:** Meningkat dari **4.285,308 kVA** (2025) menjadi **4.500,209 kVA** (2030).
* **Pertumbuhan Tahunan:** Rata-rata pertumbuhan tahunan diproyeksikan sekitar **1%**[cite: 503].
* **Pemodelan:** Model Regresi Linier berhasil menjelaskan **99,95%** variasi dalam data kebutuhan daya (Adjusted R-squared 0,9995).

---

## 🛠️ Struktur Repositori

| Folder/File | Deskripsi |
| :--- | :--- |
| `data/` | Berisi dataset asli (*data\_listrik.xlsx*) dan data hasil transformasi/agregasi yang digunakan untuk pemodelan. |
| `kode/` | Berisi seluruh script program **R** yang mencakup fungsi-fungsi untuk impor data, transformasi, statistik deskriptif, pertumbuhan tahunan, dan model regresi linier (termasuk implementasi kelas S3 `ListrikData`). |
| `presentasi/` |  file presentasi tugas ( `Presentasi_Komstat_9_RA.pptx`). |
| `dokumentasi/` | [Berisi Laporan Akhir  (`Laporan_9_RA.docx` atau PDF). |
| `README.md` | Halaman panduan utama repositori ini. |

---

## 👥 Anggota Tim

| Nama Anggota | Peran dalam Proyek | NIM | GitHub (Placeholder) |
| :--- | :--- | :--- | :--- |
| **Zahra Putri Salsabila** | **Maintainer & Code Implementation** | 123450026 | @[ZahraPutriSababila] |
| Nydia Manda Putri | Data Acquisition & Preprocessing | 123450018 | @[Nydia\_Manda] |
| Lia Hana Ichisasmita | Statistical Analysis & Interpretation | 123450089 | @[Lia\_Hana] |
| Arielva Simon Siahaan | Documentation & Report Drafting | 123450105 | @[Arielva\_Simon] |

---

--
