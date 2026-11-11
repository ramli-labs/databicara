# DATA BICARA · Modul 3 Informatika & KKA Kelas VIII

Web pembelajaran untuk Modul 3 gabungan Informatika (Lembar Kerja Pengolah Data, BK.8.13–8.18) dan KKA (Produksi Konten Audio & Video, LD.8.1–8.6), SMP Labschool Jakarta. Kelas VIII-A sampai VIII-G.

**Proyek:** "Bagaimana kita mengubah data kebiasaan warga kelas VIII menjadi video pendek yang membuat teman ingin hidup lebih sehat?"

| Pertemuan | Fokus | TP |
|---|---|---|
| P1 | Sel, Alamat & Rumus | BK.8.13–8.14 |
| P2 | Rapikan, Sort & Filter | BK.8.15–8.17 |
| P3 | Data Menjadi Temuan | BK.8.18 |
| P4 | Suara Data | LD.8.1–8.2 |
| P5 | Video Data | LD.8.3–8.5 |
| P6 | Tayang & Nilai | LD.8.6 |

## Isi repo

| Berkas | Fungsi |
|---|---|
| `index.html` | Seluruh web (satu berkas). |
| `data/Data_Kebiasaan_Kelas_8.xlsx` | Data **fiktif** 32 murid untuk Misi Data Kelas (P1). |
| `data/Data_Survei_Kelas_8_Berantakan.xlsx`, `data/Data_Survei_Kelas_8_Bersih.xlsx` | Data survei **fiktif** 70 murid (ID, tanpa nama) untuk P2. |

## Penyimpanan jawaban

Web ini memakai **Apps Script dan Google Sheet yang sama dengan JEJAK** (kelas IX). Kelas VIII cukup ditambahkan ke tab **Murid**:

1. Buka Google Sheet *JEJAK Modul 3 – Jawaban Murid* → tab **Murid**.
2. Tempel daftar kelas VIII (`Kelas | Absen | Nama`, contoh `VIII-A | 1 | ...`) di bawah baris kelas IX.
3. Buka Ekstensi → Apps Script → jalankan fungsi `siapkan`. Kode kelas VIII-A sampai VIII-G dibuat otomatis tanpa mengubah kode kelas IX.

Jawaban kelas VIII masuk ke tab **Jawaban** yang sama; rekap di Mode Guru selalu disaring per kelas. **Jangan menaruh daftar murid di repo ini** karena repo bersifat publik.

## Mode Guru

Buka `#guru`, isi kunci guru (sama dengan JEJAK), pilih kelas, pertemuan, dan kegiatan. Tombol **Kode kelas** hanya menampilkan kode kelas VIII.

## Catatan

- Penyimpanan di peramban memakai awalan `databicara.`, jadi tidak bercampur dengan JEJAK di komputer lab yang sama.
- Kegiatan kelompok cukup dikirim satu anggota (Operator) yang mencentang nama teman sekelompoknya.
- Survei Kebiasaanku (tugas rumah P1) berisi data pribadi ringan. Hapus kolom nama sebelum data kelas ditayangkan pada P2.
