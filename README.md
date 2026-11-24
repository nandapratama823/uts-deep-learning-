# UTS Deep Learning — Google Colab

Folder ini disusun mengikuti komponen pengumpulan UTS dan dapat dipakai sebagai isi repository GitHub kelompok. Dataset tidak disertakan karna berada d gdrive.

## Menjalankan ulang di Colab

1. Unggah `notebooks/uts_deep_learning.ipynb` ke Google Colab.
2. Pilih **Runtime → Change runtime type** dan aktifkan GPU bila tersedia.
3. Pilih **Runtime → Run all**.
4. Saat diminta, unggah `uts_dl_solution_colab_source.zip` dan izinkan akses Google Drive. Gunakan akun yang memiliki akses ke folder data kelompok.
5. Notebook mencari `data_uts_dl.zip`, menampilkan datasheet, dan melatih semua tiga task. Hasil baru akan disimpan di `MyDrive/uts_dl_colab/hasil_uts_dl`.

Menjalankan semua sel notebook mereproduksi pipeline penuh. Pipeline mencatat versi pustaka dan seed yang digunakan serta menghasilkan ulang metrik dan laporan.

## Komponen wajib

- `laporan.pdf` — 8 halaman, di bawah batas 18 halaman.
- `kode/` — seluruh source code, requirements, dan README.
- `prediksi_klasifikasi.csv` — kolom `id_unit,kelas`.
- `prediksi_rul.csv` — kolom `id_unit,rul`.
- `cluster.csv` — kolom `id_sampel,cluster`.
- `kontribusi.md` — perlu diisi untuk peran aktual, PR, dan persetujuan penggunaan AI.

Notebook, folder `artifacts/` (termasuk bobot model), laporan Word, dan ZIP source disertakan sebagai pendukung. Jangan unggah arsip dataset. Label hidden test dan label acuan material tidak tersedia; hidden-test score dan ARI dinilai oleh pengajar.
