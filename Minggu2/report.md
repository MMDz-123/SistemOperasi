# Jobsheet 1

### Bab ini membahas cara Linux mendeteksi dan mengelola perangkat keras, modul
### kernel, driver perangkat, serta perintah-perintah dasar terminal Linux yang esensial
### untuk praktikum Ubuntu Server 22.04.

### praktikum ini dilakukan seluruhnya dalam WSL(Windows Subsystem for Linux)

## Praktikum 2.1 Identifikasi CPU dan Memori

praktikum ini bertujuan untuk memahami spesifikasi CPU dan memori pada VM.

## Langkah-langkah

### Melihat spesifikasi CPU
Spesifikasi CPU dapat dilihat dengan perintah sebagai berikut
```
~$ lscpu
```
Setelah perintah dijalankan, maka akan muncul status CPU seperti berikut:
![output perintah lscpu](images/perintah_lscpu.png "output perintah cpu")
informasi yang tampil berupa arsitektur cpu, merek, nama model, jumlah core dan thread, dan lain-lain.

### Melihat status memori(RAM)
Status RAM dapat dilihat dengan perintah terminal seperti berikut:
```
~$ free -h
```
Setelah perintah dijalankan, maka status RAM akan muncul seperti berikut:
![output perintah free -h](images/Screenshot%202026-02-18%20112213.png "status memori")
Dengan perintah tersebut, status RAM seperti total memori yang dialokasikan, memori yang digunakan hingga RAM virtual(swap) dapat dilihat dari terminal