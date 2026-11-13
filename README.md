# PCD Assignment 04 (Laporan PCD Format IEEE Access)

Identitas : 

Nama : Muhammad Gauza Faliha 

NIM : 25/555851/PA/23315 

Kelas : KOM A 

Program Studi : Ilmu Komputer 

## Isi

Untuk laporan disini berisi tiga kasus yang dapat diselesaikan dengan teknik pengolahan citra
digital dengan identifikasi ciri (feature) yang sesuai untuk tiap kasus.
Pendekatan yang digunakan adalah morfologi matematis, deteksi tepi, dan deskriptor batas/wilayah.

| Kasus | Topik | Rujukan utama |
|-------|-------|---------------|
| Case 1 | Deteksi dan kuantifikasi retak beton | Talab dkk., *Optik*, 2016 |
| Case 2 | Segmentasi dan klasifikasi subtipe sel darah putih | Prinyakupt & Pluempitiwiriyawej, *BioMed. Eng. OnLine*, 2015 |
| Case 3 | Klasifikasi varietas beras | Cinar & Koklu, *IJISAE*, 2019 |

## Berkas

| Berkas | Keterangan |
|--------|------------|
| `main.tex` | Sumber laporan |
| `main.pdf` | Laporan hasil kompilasi, 7 halaman |
| `main.txt` | Laporan dalam format txt |
| `case1.txt`, `case2.txt`, `case3.txt` | Catatan : latar belakang, dataset, metode, hasil, dan temuan |
| `ieeeaccess.cls` | Kelas dokumen IEEE Access  |
| `IEEEtran.cls` | Kelas dasar yang dimuat oleh `ieeeaccess.cls` |
| `logo.png`, `bullet.png`, `notaglinelogo.png` | Grafik |
| `results/tables/*.tex` | Fragmen tabel dan makro angka yang disisipkan ke `main.tex` |

## Kompilasi

```bash
pdflatex main.tex
pdflatex main.tex
```


