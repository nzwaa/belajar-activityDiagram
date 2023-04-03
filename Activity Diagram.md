# Activity Diagram 

Activity Diagram atau Diagram aktivitas adalah bentuk visual dari alur kerja yang berisi aktivitas dan tindakan, yang juga dapat berisi pilihan, atau pengulangan. Dalam Unified Modeling Language(UML), diagram aktivitas dibuat untuk menjelaskan aktivitas komputer maupun alur aktivitas dalam organisasi. Selain itu diagram aktivitas juga menggambarkan alur kontrol secara garis besar.

Activity diagram bisa juga dianggap sama seperti flowchart (diagram alur), namun meskipun diagram terlihat seperti sebuah diagram alur, tetapi sebenarnya berbeda. Diagram aktivitas menunjukkan aliran yang berbeda seperti paralel, bercabang, bersamaan dan tunggal.

## Fungsi Activity Diagram

Fungsi Activity Diagram, tidak hanya membantu dalam membuat alur sebuah sistem, tapi juga dapat mempermudah dalam mengembangkan sebuah perangkat lunak:

* Memperlihatkan urutan aktivitas proses pada sistem.
* Membantu memahami proses secara keseluruhan.
* Activity Diagram dibuat berdasarkan sebuah atau beberapa Use Case.
* Menggambarkan proses bisnis dan urutan aktivitas dalam sebuah proses. 

## Tujuan Activity Diagram

Berikut beberapa tujuan dari activity diagram:

1. Menjelaskan urutan aktivitas dalam suatu proses.
2. Di dalam dunia bisnis biasanya digunakan untuk modeling (memperlihatkan urutan proses bisnis).
3. Mudah dalam memahami proses yang ada dalam sistem secara keseluruhan.
4. Merupakan metode perancangan yang terstruktur, mirip dengan Flowchart maupun Data Flow Diagram (DFD).
5. Mengetahui aktivitas aktor/pengguna berdasarkan use case/diagram yang dibuat sebelumnya.

## Komponen Activity Diagram

![komponen](https://www.dicoding.com/blog/wp-content/uploads/2020/04/intern-rendi-komponen-ad.png)

penjelasan Activity diagram di atas:

* Start Point atau Initial State (Titik Mulai/Status Awal)
  Start Point adalah lingkaran hitam kecil. Biasanya digunakan untuk menandakan status awal, tindakan awal, atau titik awal aktivitas untuk setiap activity diagram.
* Activity (Aktivitas)
  Activity merupakan aktivitas yang dilakukan atau sedang terjadi dalam sistem. Biasanya diawali dengan “kata kerja” dari aktivitas yang dilakukan.
* Decision atau Percabangan
  Percabangan atau decision merupakan suatu titik atau point yang mengindikasikan suatu kondisi di mana adanya kemungkinan dalam perbedaan transisi. Hal tersebut diperlukan ketika sistem yang dimiliki memiliki beberapa kemungkinan atau jalan alternatif.
* Synchronization
  Synchronization dibagi menjadi 2 bagian, yaitu fork dan join.
    * Fork (percabangan) digunakan untuk memecah behaviour (tingkah laku) menjadi
      activity atau action (aksi) secara paralel.
    - Join (penggabungan) digunakan untuk menghubungkan kembali activity dengan action secara paralel.
* Merge
    Menggabungkan flow yang sudah dipecah menjadi beberapa bagian oleh suatu flow.
* Swimlanes
    Memecah activity diagram menjadi kolom dan baris untuk membagi tanggung jawab objek-objek yang melakukan suatu aktivitas.
* Transition
    Digunakan untuk menunjukan aktivitas selanjutnya dan sebelumnya.
* Notasi akhir (end state)
    Notasi akhir digunakan untuk menandakan proses tersebut berakhir. Pada UML, notasi akhir dapat  digambarkan dengan simbol sebuah bull’s eye (mata sapi).

Terkadang menggunakan percabangan (decision) dengan fork adalah hal yang keliru.Sebab Decision digunakan untuk memecah aktivitas yang bersifat kondisional. Contohnya pilihan Ya atau Tidak, jika opsi Ya, maka terjadi aksi baru dan jika Tidak, maka menolak aksi baru. Sedangkan fork digunakan untuk memecah behaviour menjadi aktivitas yang paralel, contohnya seperti pengguna dapat memilih, menambah, mengubah, serta bisa juga menghapus.

Berikut beberapa hal yang disiapkan untuk membuat activity diagram:  

1. Mulailah dengan node awal untuk start state atau titik awal.
2. Tambahkan partisi jika itu memang relevan untuk analisis yang akan dibuat.
3. Buatlah suatu aksi untuk setiap langkah utama dari use case.
4. Tambahkan alur (flow) dari setiap aksi ke aksi lainnya. Keputusan berada di node     akhir. Setiap aksi hanya mendapat satu alur masuk dan satu alur keluar yang          nantinya menuju ke forks, joins, decisions, dan merges.
5. Tambahkan juga percabangan atau decision bila alur dipecah menjadi suatu kondisi     pilihan. Jangan lupa untuk menggabungkannya kembali dengan merge.
6. Menambahkan forks dan joins jika aktivitas dilakukan secara paralel.
7. Langkah yang terakhir yaitu akhiri proses dengan notasi akhir atau end state.