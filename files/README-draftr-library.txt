LIBRARY DWG DRAFTR — PAKET v3
==================================

Isi paket:
1. draftr-template-lembar-a3.dwg/.dxf — Template lembar kerja A3 draftr:
   grid lembar, blok kop, tabel revisi, kolom catatan. Standar lembar draftr.
2. draftr-katalog-simbol-referensi.dwg/.dxf — Katalog Simbol G-901:
   18 simbol referensi (bubble grid, penanda potongan/elevasi, panah utara, dll).
3. draftr-katalog-simbol-teks.dwg/.dxf — Katalog Simbol G-902: simbol teks & anotasi.
4. draftr-katalog-simbol-garis.dwg/.dxf — Katalog simbol garis & linetype.
5. draftr-blok-denah-dasar.dwg/.dxf — 12 simbol denah siap salin dalam satu lembar:
   pintu 1 daun, pintu 2 daun, pintu geser, jendela, WC duduk, WC jongkok,
   wastafel, bak mandi, shower, bubble grid, panah utara, tanda potongan.
6. Blok satuan (satu simbol per file, siap sisip):
   draftr-blok-pintu-1-daun, draftr-blok-pintu-2-daun, draftr-blok-pintu-geser,
   draftr-blok-jendela, draftr-blok-wc-duduk, draftr-blok-wc-jongkok,
   draftr-blok-wastafel, draftr-blok-bak-mandi, draftr-blok-shower,
   draftr-blok-bubble-grid, draftr-blok-panah-utara, draftr-blok-tanda-potongan
   (masing-masing .dwg + .dxf).
7. Elemen parametrik (BARU di v3) — digenerate dari parameter oleh generator
   draftr dan terverifikasi terhadap gambar standar; entitas semantik asli
   (HATCH, ARC, layer bernama) — bukan garis polos:
   draftr-A8-dinding-bata-merah (segmen dinding bata tebal 150, HATCH ANSI32),
   draftr-A17-pintu-swing-1-daun (daun 800, busur ayun ARC),
   draftr-A17-pintu-swing-2-daun (2 x 800),
   draftr-A17-pintu-lipat (5 panel kaca pitch 320),
   draftr-A18-jendela-1-daun (potongan, bukaan 600),
   draftr-A18-jendela-2-daun (potongan, bukaan 1140),
   draftr-A18-kaca-mati (potongan, bukaan 1140)
   (masing-masing .dwg + .dxf).

Cara pakai:
- Satuan semua file: milimeter (mm), digambar 1:1 di Model.
- Buka file katalog/blok, salin simbol yang diperlukan ke gambar kerja
  (COPYBASE dari titik acuan), atau jadikan BLOCK dengan WBLOCK.
- Template A3: buka, simpan sebagai file kerja atau .dwt, isi kop lewat atribut/teks.

Standar: mengikuti standar gambar draftr (adaptasi USNCS, metrik, teks Indonesia).
Gratis dipakai untuk pekerjaan pribadi & kantor. Jangan dijual ulang sebagai paket.

draftr — shop drawing parametrik untuk drafter Indonesia.
Threads: @draftr.dwg
