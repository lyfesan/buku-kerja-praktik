# Buku Laporan Kerja Praktik ITS

Repositori ini berisi buku laporan kerja praktik menggunakan [LaTeX](https://www.latex-project.org/) yang disesuaikan dengan format yang diberlakukan oleh [Institut Teknologi Sepuluh Nopember](https://www.its.ac.id/) (ITS).
Buku ini dibuat menggunakan template dari repositori [b201lab/template-buku-kp-its](https://github.com/b201lab/template-buku-kp-its) dengan beberapa perubahan yang menyesuaikan laporan kerja praktik ITS serta penggunaan compiler xelatex untuk memudahkan penggunaan beberapa format dan font yang tidak tersedia dengan compiler pdflatex biasa.
Buku yang dibuat saat ini baru mengikuti aturan yang diberlakukan oleh [Departemen Teknik Informatika](https://www.its.ac.id/informatika/) FTEIC - ITS dengan sedikit penyesuaian, sehingga, secara penuh template buku ini ini belum mewakili aturan yang berlaku secara umum di setiap departemen yang ada di ITS.

## Fitur

- Format ukuran halaman, margin, dan font yang disesuaikan dengan aturan yang berlaku di ITS.
- Disertai halaman-halaman yang diperlukan seperti sampul, lembar pengesahan, kata pengantar, dsb.
- Pembuatan daftar isi, daftar gambar, daftar tabel, dan daftar pustaka secara otomatis.
- Penomoran halaman, gambar, tabel, dan referensi secara otomatis.
- Penambahan gambar dengan format JPEG, PNG, maupun format lain pada dokumen.
- Penambahan persamaan ilmiah, tabel, dan kode program pada dokumen. 
- Kompilasi dokumen dengan compiler xelatex untuk mendukung penggunaan font Times New Roman dan Trebuchet MS secara otomatis menggunakan [GitHub Actions](https://github.com/features/actions).

## Cara Menggunakan Template

Disarankan menggunakan distribusi [TeXLive](https://www.tug.org/texlive/) dan editor [TeXstudio](https://www.texstudio.org/) untuk memudahkan proses kompilasi dan editing isi file template.
Bagian utama dokumen terletak pada file [`main.tex`](./main.tex) yang digunakan untuk mengatur package LaTeX yang digunakan serta file lain yang akan diinputkan pada dokumen.
Setelah kompilasi dilakukan, hasilnya akan ada beberapa file `main` dengan format yang berbeda.
Yang paling utama adalah file `main.pdf` yang merupakan hasil akhir dari proses kompilasi dokumen.

Selain file `main.tex`, ada juga beberapa bagian lain dari buku ini yang bisa diubah, seperti:
- **[`bab`](./bab)**, berisi file `*.tex` dari setiap bab yang akan dimasukkan pada buku laporan kerja praktik.
- **[`pengesahan`](./pengesahan)**, berisi file `*.tex` dari lembar pengesahan untuk buku laporan kerja praktik.
- **[`sampul`](./sampul)**, berisi file `*.tex` dari sampul luar dan dalam untuk buku laporan kerja praktik.
- **[`lainnya`](./lainnya)**, berisi file `*.tex` dari halaman lain yang akan dimasukkan pada buku laporan kerja praktik.
- **[`gambar`](./gambar)**, berisi file `*.jpg`, `*.png`, maupun format gambar lain yang akan dimasukkan pada dokumen.
- **[`tabel`](./tabel)**, berisi file `*.tex` dari tabel yang akan dimasukkan pada dokumen.
- **[`program`](./program)**, berisi file kode program yang akan dimasukkan pada dokumen.
- **[`pustaka/pustaka.bib`](./pustaka/pustaka.bib)**, berisi daftar referensi yang akan dimasukkan pada dokumen.

> Penjelasan lebih lanjut mengenai penggunaan template ini akan dijelaskan dengan comment yang tersedia pada setiap file yang ada.

## Lisensi

Kode sumber yang ada di repositori ini dilisensikan berdasarkan ketentuan [Lisensi MIT](./LICENSE).

Copyright © 2026 [lyfesan](https://github.com/lyfesan)
