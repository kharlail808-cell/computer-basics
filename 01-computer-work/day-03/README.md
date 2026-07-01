# Hari 03 - CPU Dasar

 **Tanggal:** 1 Juli 2026

---

# Tujuan Belajar

* Memahami pengertian CPU dan fungsinya.
* Mengetahui bagaimana CPU menjalankan instruksi.
* Memahami konsep **Core**, **Thread**, dan **Clock Speed (GHz)**.
* Mengetahui hubungan CPU dengan RAM dan Storage saat menjalankan aplikasi.

---

# Materi

## Apa itu CPU?

CPU (**Central Processing Unit**) adalah komponen utama yang bertugas menjalankan instruksi dan mengolah data pada komputer. Semua perintah yang diberikan kepada komputer akan diproses oleh CPU.

---

## Cara Kerja CPU

Saat sebuah aplikasi dibuka, CPU bekerja melalui tiga tahap utama:

1. **Fetch** → Mengambil instruksi dari RAM.
2. **Decode** → Memahami instruksi yang diterima.
3. **Execute** → Menjalankan instruksi tersebut.

Contoh saat membuka Google Chrome:

1. Pengguna mengklik ikon Google Chrome.
2. Storage (SSD) membaca file aplikasi.
3. Data dipindahkan ke RAM.
4. CPU mengambil data dari RAM.
5. CPU menjalankan instruksi.
6. Google Chrome ditampilkan pada monitor.

---

## Core

Core adalah inti pemrosesan pada CPU.

Semakin banyak Core, semakin banyak pekerjaan yang dapat diproses secara bersamaan sehingga kemampuan multitasking menjadi lebih baik.

Contoh:

* 2 Core → mampu menangani lebih sedikit pekerjaan secara bersamaan.
* 8 Core → mampu menangani lebih banyak pekerjaan secara bersamaan.

---

## Thread

Thread adalah jalur kerja yang dapat ditangani oleh setiap Core.

Beberapa CPU memiliki teknologi yang memungkinkan satu Core menangani lebih dari satu Thread sehingga pekerjaan dapat dilakukan dengan lebih efisien.

Contoh:

* 4 Core 4 Thread
* 4 Core 8 Thread

---

## Clock Speed (GHz)

Clock Speed menunjukkan kecepatan kerja CPU.

Kecepatan CPU dapat berubah sesuai beban kerja.

Contoh:

* Saat komputer sedang idle → GHz rendah.
* Saat membuka aplikasi atau bermain game → GHz meningkat.

---

# Ringkasan Materi

* CPU bertugas menjalankan instruksi komputer.
* CPU bekerja melalui tiga tahap: Fetch, Decode, dan Execute.
* Core adalah inti pemrosesan CPU.
* Thread merupakan jalur kerja yang dapat ditangani oleh Core.
* Clock Speed (GHz) menunjukkan kecepatan kerja CPU dan dapat berubah sesuai kebutuhan.

---

# Hasil Pemahaman

Setelah mempelajari materi hari ini, saya memahami bahwa:

* CPU tidak bekerja sendiri, tetapi bekerja sama dengan RAM dan Storage.
* CPU mengambil data dari RAM, bukan langsung dari Storage, karena RAM memiliki kecepatan akses yang jauh lebih tinggi.
* Semakin banyak Core, semakin baik kemampuan komputer dalam menjalankan banyak aplikasi secara bersamaan.
* Thread membantu Core menangani lebih banyak alur pekerjaan secara efisien.
* Clock Speed tidak selalu tetap karena CPU akan menyesuaikan kecepatannya dengan beban kerja.

---

# Kesimpulan

Saya memahami bahwa CPU merupakan komponen utama yang menjalankan seluruh instruksi pada komputer. Dalam menjalankan aplikasi, CPU bekerja sama dengan Storage dan RAM melalui urutan proses yang benar, yaitu **Storage → RAM → CPU → Monitor**.

Saya juga memahami bahwa jumlah Core memengaruhi kemampuan multitasking, sedangkan Thread membantu Core menangani lebih banyak jalur pekerjaan. Selain itu, kecepatan CPU (Clock Speed) dapat berubah secara otomatis sesuai dengan kebutuhan sistem.

---

# Pertanyaan

1. Mengapa satu Core dapat memiliki lebih dari satu Thread?
2. Apa perbedaan Hyper-Threading dan SMT?
3. Mengapa CPU modern tidak hanya meningkatkan Clock Speed, tetapi juga menambah jumlah Core?
4. Faktor apa saja selain GHz yang memengaruhi performa CPU?

