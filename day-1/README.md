# Day 1 - Introduction To DevOps

## Theory
### Apa itu DevOps?
**DevOps** tersusun dari dua kata: *Development* dan *Operations*. *Development* merujuk pada bagaimana aplikasi dibangun, sedangkan *Operations* merujuk pada bagaimana aplikasi disajikan kepada pengguna. 

**DevOps** adalah sebuah penghubung atau pengawas yang berada di seluruh siklus hidup sebuah aplikasi, mulai dari awal perencanaan, sampai pemeliharaan aplikasi berjalan.

Umumnya, **DevOps** memiliki siklus sebagai berikut:

- **Plan:** Menentukan fitur apa yang akan dibuat atau ditambahkan
- **Code:** Implementasi fitur yang direncanakan ke dalam baris kode
- **Build:** Mengubah kode menjadi paket aplikasi yang siap digunakan
- **Test:** Melakukan pengujian fitur secara otomatis
- **Release:** Menandai versi dan menyimpan paket aplikasi
- **Deploy:** Mengirim dan mengaktifkan paket aplikasi agar dapat diakses
- **Operate:** Menjaga dan memelihara infrastruktur agar tetap stabil
- **Monitor:** Melakukan pengawasan untuk menangani error dan masalah

Setelah **Monitor**, siklus akan kembali ke **Plan** dan tidak akan benar-benar berakhir. karena itulah **DevOps** memiliki lambang "Infinity".

### Mengapa harus ada DevOps?
**DevOps** adalah solusi yang dapat memastikan kestabilan dan kualitas sebuah aplikasi, mulai dari *production* hingga *deployment* dengan lebih cepat dan otomatis. Tanpa adanya **DevOps**, sebuah aplikasi sangat mungkin memiliki ketidaksesuaian *environment* antara lokal dan publik, fitur baru yang merusak fitur lama, menurunnya performa server, dan sebagainya.

**DevOps** bukan sekedar alat atau *role* pekerjaan, melainkan sebuah budaya dalam pengembangan aplikasi yang memastikan setiap tim bekerja dengan baik.

### Apa itu CI/CD?
**CI/CD** adalah singkatan dari *Continuous Integration* dan *Continuous Deployment*. *Continuous Integration* artinya aplikasi akan terus dikembangkan dan diuji secara terus menerus, sedangkan *Continuous Deployment* artinya hasil kode akan dikirimkan ke dalam produksi dan dipantau secara terus menerus. Keduanya dilakukan secara otomatis, sehingga lebih cepat dan efisien.

### Apa itu Virtualization?
**Virtualization** adalah sebuah teknologi yang dapat pemecahan *resource* yang lebih besar menjadi beberapa bagian yang lebih kecil. Mulai dari daya CPU, memory bahkan storage akan terisolasi secara mandiri.

**VIrtualization** akan sangat berguna karena dapat dipindahkan atau dihancurkan dengan mudah tanpa memengaruhi resouce utama yang berada di luar sistem.

### Apa itu Virtual Machine?
**VM** atau **Virtual Machine** adalah sebuah aplikasi yang menggunakan teknologi **Virtualization** untuk membagi resource sesuai yang diinginkan pengguna. Umumnya, **VM** digunakan untuk menjalankan server atau sistem operasi di atas sistem operasi yang sudah ada.

### Apa itu Hypervisor?
**Hypervisor** bisa dianalogikan sebagai sebuah "program" atau "pengatur" yang melakukan pembagian resource berdasarkan keinginan pengguna.

## Practice
### Praktik yang dilakukan
Melakukan **VIrtualization** dengan menginstall Ubuntu menggunakan VirtualBox

### Alat yang digunakan
- ISO Ubuntu LTS
- VirtualBox

### Langkah-langkah
1. Membuka VirtualBox yang sudah terinstall
![Tampilan awal VirtualBox](<Screenshot 2026-05-06 170853.png>)

2. Membuat Virtual Machine baru, mengisi data serta file ISO yang dibutuhkan
![Pengisian data dan reference file ISO](<Screenshot 2026-05-06 171320.png>)

3. Melakukan konfigurasi Memory, CPU, dan Storage yang ingin ditanamkan ke dalam mesin.
![Konfigurasi pembagian resource](<Screenshot 2026-05-06 171518.png>)

4. Menjalankan mesin dan melakukan instalasi Ubuntu melalui BIOS
![Overview VM Ubuntu](<Screenshot 2026-05-06 171545.png>)
![Tampilan awal Instalasi](<Screenshot 2026-05-06 171721.png>)

5. Menghubungkan Internet dengan konfigurasi jaringan
![Mendapatkan data jaringan](<Screenshot 2026-05-06 171947.png>)
![Konfigurasi jaringan pada BIOS VM Ubuntu](<Screenshot 2026-05-06 172427.png>)

6. Melakukan partisi dari storage yang dimiliki
![Partisi Storage](<Screenshot 2026-05-06 172922.png>)

7. Menunggu Instalasi selesai dilakukan
![Instalasi berjalan](<Screenshot 2026-05-06 173218.png>)