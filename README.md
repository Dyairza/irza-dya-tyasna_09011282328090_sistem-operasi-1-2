1. Buka aplikasi VirtualBox (saya sudah mendownload Linux dan VirtualBox sebelumnya).
   ![Buka VirtualBox](https://github.com/Dyairza/irza-dya-tyasna_09011282328090_sistem-operasi-1-2/blob/main/1.png)

2. Saat masuk ke aplikasi akan muncul seperti ini.
   ![Tampilan VirtualBox](https://github.com/Dyairza/irza-dya-tyasna_09011282328090_sistem-operasi-1-2/blob/main/2.png)

3. Klik start pada pojok kanan atas.
   ![Klik Start](https://github.com/Dyairza/irza-dya-tyasna_09011282328090_sistem-operasi-1-2/blob/main/3.png)

4. Setelah itu Linux yang sudah diinstal akan ditampilkan.
   ![Linux Ditampilkan](https://github.com/Dyairza/irza-dya-tyasna_09011282328090_sistem-operasi-1-2/blob/main/4.png)

### Analisis pada Gambar Kenapa Saat Instalasi Perlu Dipilih `/` pada Opsi Mount Point:

Direktori root (`/`) adalah akar dari sistem berkas dalam sistem operasi Linux. Saat menginstal sistem operasi berbasis Linux, direktori root ini harus dipasang (mount) ke partisi tertentu. Memilih `/` sebagai mount point berarti partisi ini akan berfungsi sebagai pusat sistem berkas, tempat di mana direktori lainnya seperti `/home`, `/var`, dan `/usr` bercabang. Ini penting agar sistem dapat berfungsi dengan baik karena Linux membutuhkan lokasi yang jelas untuk file dan folder intinya.

- **ext4**: Ini adalah sistem berkas yang sering digunakan di Linux karena bisa diandalkan, cepat, dan memiliki fitur "journaling" yang membantu memulihkan data jika terjadi masalah.
- **ext3**: Merupakan versi lama dari ext4. Meski juga punya fitur "journaling," kinerjanya sedikit lebih lambat dibanding ext4.
- **swap**: Partisi ini digunakan untuk memperluas memori RAM. Jika RAM penuh, data sementara akan dipindahkan ke swap ini di hard drive.
- **ntfs**: Sistem berkas yang dibuat oleh Microsoft, umumnya digunakan di Windows. Bisa menyimpan file yang sangat besar dan kompatibel dengan sistem Windows.
- **fat32**: Sistem berkas yang lebih sederhana dan sering digunakan di perangkat seperti flash drive karena bisa dipakai di berbagai sistem. Namun, tidak bisa menyimpan file yang ukurannya lebih dari 4GB.
- **btrfs**: Sistem berkas modern untuk Linux yang punya fitur-fitur canggih seperti snapshot (untuk mengembalikan data ke kondisi sebelumnya), pooling (menggabungkan beberapa disk), dan checksum (untuk memastikan data tidak rusak), yang membuatnya lebih aman dan bisa berkembang seiring kebutuhan.
