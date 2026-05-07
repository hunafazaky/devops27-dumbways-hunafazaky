# Day 2 - Basic Shell and Computer Network

### **Q1 :**

Buat sebuah diagram sebuah jaringan komputer dengan 4 device dengan kondisi :

- IP Class C : 192.168.4.xxx

- CIDR Block : 192.168.4.0/24

### **A1 :**

![Diagram Jaringan Komputer dengan 4 Device](Network-01.drawio.png)

---

### **Q2 :**

Jelaskan perbedaan antara SH (Shell) dan BASH (Bourne-Again Shell)

### **A2 :**

**SH (Shell)** adalah sintaks atau bahasa paling mendasar yang digunakan pada sistem UNIX. Karena kesederhanaannya, SH kompatibel di seluruh sistem UNIX walaupun minim fitur.

Di sisi lain, **Bash (Bourne-Again Shell)** bisa dibilang merupakan modifikasi dari **Shell** yang memiliki banyak fitur tambahan. Misalnya seperti _autocomplete_, _history_, beberapa algoritma pemrograman, dan sebagainya. Hanya saja, tidak seperti **Shell** yang bisa langsung dipakai _out-of-the-box_, **Bash** harus diinstall terlebih dahulu jika ingin dipakai. Walaupun demikian, umumnya semua distro Linux sudah secara default menyertakan **Bash** di dalamnya.

---

### **Q3 :**

Buat dokumentasi/kumpulan command linux yang kalian ketahui! (Command diluar materi akan diberi nilai ++)

### **A3 :**

> **echo**
- fungsi: menampilkan sesuatu
- ( echo text ) akan menampilkan "text"
- ( echo text > text.txt ) akan membuat file "text.txt" pada dir aktif dan diisi dengan "text"

> **pwd**
- singkatan dari "Print Working Directory"
- fungsi: menampilkan alamat directory
- ( pwd ) akan menampilkan alamat dir aktif

> **cd**
- singkatan dari "Change Directory"
- fungsi: pindah directory
- ( cd folder ) akan maju ke dir "folder" **jika tersedia**
- ( cd .. ) akan mundur ke dir sebelumnya
- ( cd / ) akan pindah ke root dir
- ( cd /home/user ) akan pindah ke "/home/user2"

> **ls**
- singkatan dari "List Directories"
- fungsi: menampilkan list dir dan file
- ( ls ) akan menampilkan list dir dan file pada dir aktif
- ( ls /home/user ) akan menampilkan list dir dan file pada "/home/user"

> **touch**
- fungsi: membuat file
- ( touch file1 ) akan membuat file1 pada dir aktif
- ( touch file1 file2 file3 ) akan membuat file1, file2 dan file3 pada dir aktif

> **file**
- fungsi: menampilkan deskripsi isi file
- jika kita memiliki "text.txt" dengan isi "text", ( file text.txt ) akan menampilkan "text.txt: ASCII text"

> **cat**
- singkatan  dari "Concatenate"
- fungsi: menampilkan isi teks suatu file
- jika kita memiliki "text.txt" dengan isi "text", ( cat text.txt ) akan menampilkan "text"
- jika kita memiliki "picture.jpg", ( cat picture.jpg ) akan menampilkan *gibberish* atau bahkan merusak tampilan terminal.
- ( cat > text.txt ) akan membuatkan file text.txt dan masuk ke mode penulisan. Kita bisa menuliskan apa pun setelahnya, lalu menekan "CTRL + D" untuk menyimpan dan keluar.

> **cp**
- singkatan dari "Copy"
- fungsi: menyalin dan menyimpan file
- ( cp file1 file2 ) akan membuat menyalin file1 dengan nama file2
- ( cp file1 folder ) akan membuat menyalin file1 ke dalam dir "folder"

> **mv**
- singkatan dari "Move"
- fungsi: memindahkan atau mengubah nama file
- ( mv file1 folder/ ) memindahkan file1 ke dalam dir "folder" **jika tersedia**
- ( mv file1 file2) mengubah file1 menjadi file2

> **mkdir**
- singkatan dari "Make DIrectory"
- fungsi: membuat dir baru
- ( mkdir new ) akan membuat dir new
- ( mkdir new1 new2 ) akan membuat dir new1 dan new2

> **rm**
- singkatan dari "Remove"
- fungsi: menghapus file
- ( rm file1 ) akan menghapus file1