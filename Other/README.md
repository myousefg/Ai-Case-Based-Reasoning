Sistem Pemilihan Restoran Terbaik Menggunakan Fuzzy Logic Inference

Deskripsi :
Aplikasi ini adalah implementasi Fuzzy Logic Inference untuk memilih 5 restoran terbaik di kota Bandung berdasarkan dua kriteria:

- Kualitas Servis (nilai 1-100)
- Harga (Rp25.000 - Rp55.000)

Sistem membaca data dari file `restoran.xlsx`, menghitung skor kelayakan restoran menggunakan metode Fuzzy, dan menghasilkan output `peringkat.xlsx` berisi daftar 5 restoran terbaik.

Dokumen Terkait

- Laporan Tugas:  
  [Google Docs - Laporan Tugas](https://docs.google.com/document/d/1peOni9VaHyYl-QOo1QHVRQ-8cwOqSuRV_xcOrykrUwc/edit?tab=t.0)
- Slide Presentasi:
  [Canva - Slide Presentasi](https://www.canva.com/design/DAGl6R2lXQA/yihFzBos-xFJyk-l3BC3_g/edit?utm_content=DAGl6R2lXQA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

Cara Menjalankan Aplikasi

1. Pastikan Anda sudah menginstall Python (versi 3.x).
2. Install library yang diperlukan (hanya `pandas` dan `openpyxl`):
   pip install pandas openpyxl
3. Pastikan file restoran.xlsx berada dalam satu folder dengan reasoning.py.
4. Jalankan program menggunakan command berikut :
   python reasoning.py
5. Hasil output akan tersimpan di file peringkat.xlsx di folder yang sama.
