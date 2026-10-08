# Tugas_1_




1. <img width="1280" height="800" alt="VirtualBox_HadiFadhullah1_07_10_2026_12_54_14" src="https://github.com/user-attachments/assets/f25e9fa4-9c5b-4778-9aeb-6760482454d4" />

   <img width="1280" height="800" alt="VirtualBox_HadiFadhullah1_07_10_2026_12_55_39" src="https://github.com/user-attachments/assets/0da05c10-3b32-4806-9f6d-0d88ef6061db" />


  2. Analisislah pada gambar kenapa saat instalasi perlu dipilih “/” pada opsi Mount Point ? Mount point / atau root directory merupakan direktori utama dalam struktur filesystem Linux. Hampir seluruh direktori dan file sistem Linux berada di bawah struktur root /. Pada proses instalasi, partisi yang diberi mount point / digunakan sebagai lokasi utama filesystem sistem operasi. Dengan adanya mount point tersebut, sistem mengetahui bahwa partisi tersebut merupakan tempat utama untuk memasang dan menjalankan sistem Linux. Struktur direktori seperti /bin, /etc, /usr, /var, /boot, dan direktori sistem lainnya berada di bawah root /. Oleh karena itu, instalasi Linux membutuhkan filesystem yang memiliki mount point /. Dalam praktikum, opsi Something else digunakan agar partisi dapat diatur secara manual, kemudian salah satu partisi diberikan mount point / menggunakan filesystem Ext4. Modul juga menjelaskan bahwa opsi tersebut digunakan untuk mengelola partisi harddisk sebagai tempat filesystem dan penyimpanan data.
mount point / diperlukan karena merupakan titik utama/root dari filesystem Linux dan menjadi lokasi utama sistem operasi Linux diinstal serta menjalankan berbagai direktori system.

3. Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs !
   
a. Ext4  (Fourth Extended Filesystem) merupakan filesystem yang banyak digunakan pada sistem operasi Linux. Ext4 merupakan pengembangan dari Ext3 dan menyediakan kemampuan pengelolaan file serta penyimpanan yang lebih baik. Pada praktikum, Ext4 digunakan untuk partisi Linux seperti /home dan /. Modul secara khusus menggunakan Ext4 Journaling File System untuk partisi tersebut

b. Ext3  (Third Extended Filesystem) merupakan filesystem Linux yang merupakan pengembangan dari Ext2. Salah satu karakteristik penting Ext3 adalah penggunaan journaling, yaitu pencatatan perubahan filesystem untuk membantu menjaga konsistensi filesystem ketika terjadi gangguan seperti mati listrik atau sistem berhenti secara tiba-tiba

c. Swap merupakan ruang pada media penyimpanan yang digunakan Linux sebagai memori virtual. Swap dapat membantu ketika kebutuhan memori melebihi kapasitas RAM yang tersedia. Dalam praktikum, swap dibuat sebagai partisi tersendiri dengan memilih Use As: Swap Area. Contoh ukuran yang diberikan dalam modul adalah 1024 MB

d. NTFS (New Technology File System) merupakan filesystem yang dikembangkan dan banyak digunakan oleh sistem operasi Windows. NTFS mendukung ukuran file dan partisi yang besar serta menyediakan berbagai fitur seperti permission dan journaling. NTFS umumnya digunakan untuk partisi Windows dan penyimpanan yang membutuhkan kompatibilitas dengan Windows

e. FAT32  (File Allocation Table 32) merupakan filesystem yang memiliki kompatibilitas luas dengan berbagai sistem operasi dan perangkat. FAT32 sering digunakan pada flashdisk, kartu memori, dan media penyimpanan lain. Keterbatasan penting FAT32 adalah ukuran maksimum sebuah file sekitar 4 GB, sehingga kurang sesuai untuk menyimpan file individual yang berukuran sangat besar

f. Btrfs  (B-tree File System) merupakan filesystem Linux modern yang dirancang untuk mendukung fitur-fitur seperti snapshot, subvolume, checksum, dan pengelolaan storage yang lebih fleksibel. Btrfs dapat digunakan pada sistem Linux ketika dibutuhkan fitur manajemen filesystem yang lebih modern

