# Soal 3

Conan adalah seorang detektif terkenal. Suatu hari, Conan menerima beberapa laporan tentang hewan di kebun binatang yang tiba-tiba hilang. Karena jenis-jenis hewan yang hilang banyak, maka perlu melakukan klasifikasi hewan apa saja yang hilang.

A. Untuk mempercepat klasifikasi, Conan diminta membuat program untuk membuat 2 directory di “/home/[USER]/modul2/” dengan nama “darat” lalu 3 detik kemudian membuat directory ke 2 dengan nama “air”. 

B. Kemudian program diminta dapat melakukan extract “animal.zip” di “/home/[USER]/modul2/”.

C. Tidak hanya itu, hasil extract dipisah menjadi hewan darat dan hewan air sesuai dengan nama filenya. Untuk hewan darat dimasukkan ke folder “/home/[USER]/modul2/darat” dan untuk hewan air dimasukkan ke folder “/home/[USER]/modul2/air”. Rentang pembuatan antara folder darat dengan folder air adalah 3 detik dimana folder darat dibuat terlebih dahulu. Untuk hewan yang tidak ada keterangan air atau darat harus dihapus.

D. Setelah berhasil memisahkan hewan berdasarkan hewan darat atau hewan air. Dikarenakan jumlah burung yang ada di kebun binatang terlalu banyak, maka pihak kebun binatang harus merelakannya sehingga conan harus menghapus semua burung yang ada di directory “/home/[USER]/modul2/darat”. Hewan burung ditandai dengan adanya “bird” pada nama file.

E. Terakhir, Conan harus membuat file list.txt di folder “/home/[USER]/modul2/air” dan membuat list nama semua hewan yang ada di directory “/home/[USER]/modul2/air” ke “list.txt” dengan format UID_[UID file permission]_Nama File.[jpg/png] dimana UID adalah user dari file tersebut file permission adalah permission dari file tersebut.
Contoh : conan_rwx_hewan.png

## Penjelasan Code Soal 3
Dalam soal ini, kita diminta untuk meng-unzip file yang telah diberikan yaitu **animal.zip**. Kemudian, buat dua direktori yang bernama darat dan air pada folder **/home/[USER]/modul2/** . Dari hasil unzip tersebut, bagi file yang mengandung nama darat, maka akan dimasukkan ke direktori darat. Begitu juga dengan file yang mengandung nama air akan masuk ke direktori air. Selanjutnya, kita diminta untuk menghapus file yang mengandung nama `bird` dan file yang tidak memiliki klasifikasi darat maupun air. Terakhir, kita diminta untuk membuat file yang bernama **list.txt** di folder **/home/[USER]/modul2/air** dengan isi nama semua hewan yang berada di direktori **/home/[USER]/modul2/air** dengan format "**UID_[UID file permission]_Nama File.[jpg/png]**" dimana UID adalah user dari file tersebut file permission adalah permission dari file tersebut.
