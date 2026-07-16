# Terminal Drawing Tool

Alat bantu penggambaran tata letak Terminal Petikemas (dermaga, container yard, peralatan, dan gate) di atas peta satelit.

Aplikasi ini berupa satu berkas `index.html` yang berjalan sepenuhnya di browser. Aplikasi tidak menyimpan data apa pun di dalam kode; data project disimpan terpisah oleh pengguna (di localStorage browser dan/atau berkas `.tpkdraw` di penyimpanan pribadi/kantor).

## Cara membuka
Buka `index.html` melalui URL GitHub Pages menggunakan Google Chrome atau Microsoft Edge. Membuka lewat URL `https://` membuat fitur "Simpan ke berkas" berjalan andal.

## Fitur utama
- Menggambar dermaga, container yard (CY), peralatan (QCC, RTG, HMC, dll), dan gate di atas peta.
- Mengubah warna tiap peralatan melalui panel Edit.
- Menyimpan/membuka project sebagai berkas `.tpkdraw`.
- Export tampilan ke PNG/PDF.
- Autosave lokal per terminal (localStorage) sebagai jaring pengaman.

## Catatan penting
Repositori ini hanya berisi aplikasinya, BUKAN data. Jangan mengunggah berkas `.tpkdraw` berisi rencana terminal ke repositori ini, karena situs GitHub Pages dapat diakses publik. Simpan data project di penyimpanan yang disetujui perusahaan (mis. OneDrive kantor).

## Memperbarui aplikasi
Untuk memperbarui, ganti berkas `index.html` dengan versi terbaru, lalu commit. GitHub Pages akan otomatis membangun ulang dalam beberapa menit.
