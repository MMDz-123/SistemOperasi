# Laporan Sistem Operasi Minggu4
## Tugas Pendahuluan

1. Apa yang dimaksud perintah-perintah directory: `pwd, cd, mkdir, rmdir`?
2. Apa yang dimaksud perintah manipulasi file: `cp, mv, rm` serta format yang digunakan
3. Jelaskan perbedaan *symbolic link* menggunakan *hard link* dan *soft link*
4. jelaskan maksud perintah-perintah `file, find, which, locate, grep`

## Jawab

1. `pwd` yakni Print Working Directory yang berfungsi menampilkan *path* direktori saat ini.
`cd` yakni Change Directory yang berfungsi untuk pindah direktori
`mkdir` yakni Make Directory berfungsi untuk membuat direktori baru
`rmdir` yakni Remove Directory berfungsi menghapus direktori dan isinya
2. `cp` yakni Copy yang berfungsi menyalin file atau direktori
`mv` yakni Remove berfungsi memindah direktori
`rm` yakni Remove berfungsi untuk menghapus file, biasanya penghapusan berssifat permanen.
3. Hard link langsung merujuk ke data fisik pada disk, sedangkan soft link merujuk nama file asal seperti *shortcut* pada windows. Selain itu, hard link tidak dapat dibuat antar partisi tidak seperti soft link yang memungkinkan untuk dibuat meskipun berada dalam partisi yang berbeda
4. `file` untuk menentukan tipe file seperti `pdf`, `png`, `bin`, dan lain-lain
`find` untuk mencari file dalam direktori
`which` menunjukkan lokasi file `.exe` yang ingin dijalankan saat perintah dimasukkan
`locate` mencari file dengan lebih cepat daripada `find` karena perintah tersebut menggunakan indeks database
`grep` untuk mencari pola tertentu dalam file atau hasil *output* perintah lain