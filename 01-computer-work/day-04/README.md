# Hari 04 - CPU Usage dan Bottleneck

Tanggal : 2 Juli 2026

# Tujuan Belajar

- Memahami perubahan CPU Usage saat komputer menjalankan aplikasi.
- Mengamati perubahan penggunaan RAM dan Storage.
- Mengenal konsep bottleneck pada komputer.

# Materi

- CPU Usage menunjukkan tingkat kesibukan CPU.
- Clock Speed dapat berubah sesuai beban kerja.
- RAM menyimpan data sementara aplikasi yang sedang digunakan.
- Storage membaca data aplikasi saat pertama kali dibuka.
- Bottleneck adalah komponen yang menjadi penghambat kinerja sistem.

# Praktik

## Tujuan

Mengamati perubahan penggunaan CPU, RAM, dan Storage saat membuka aplikasi.

## Alat

- Laptop
- Windows
- Task Manager

## Langkah

1. Membuka Task Manager.
2. Mengamati kondisi awal komputer.
3. Membuka Google Chrome dengan beberapa tab.
4. Mengamati perubahan CPU, RAM, dan Disk.
5. Menutup semua aplikasi.
6. Mengamati kondisi komputer setelah beban berkurang.

# Hasil Pengamatan

| Kondisi | CPU | Speed | RAM | Disk |
|---------|-----|--------|------|------|
| Sebelum membuka aplikasi | 22% | 1,54 GHz | 3,0 / 5,9 GB | 0% |
| Chrome dibuka | 74% | 1,70 GHz | 4,6 / 5,9 GB | 3% |
| Setelah aplikasi ditutup | 26% | 1,67 GHz | 3,1 / 5,9 GB | 0% |

# Analisis

Saat Google Chrome dibuka, CPU dan RAM meningkat karena harus memuat halaman web dan menjalankan beberapa proses secara bersamaan. SSD hanya aktif saat membaca data aplikasi pada awal pembukaan, kemudian aktivitasnya menurun karena data sudah berada di RAM. Setelah aplikasi ditutup, penggunaan CPU dan RAM kembali mendekati kondisi awal.

# Kesimpulan

CPU, RAM, dan Storage bekerja sama saat menjalankan aplikasi. CPU menjalankan instruksi, RAM menyimpan data sementara, sedangkan Storage menyediakan data aplikasi. Pada praktik ini tidak ditemukan bottleneck karena tidak ada komponen yang mencapai penggunaan maksimal.

# Pertanyaan

1. Mengapa CPU tidak selalu berjalan pada Base Speed?
2. Mengapa Chrome menggunakan RAM lebih banyak daripada aplikasi sederhana?
3. Dalam kondisi seperti apa bottleneck dapat terjadi?
