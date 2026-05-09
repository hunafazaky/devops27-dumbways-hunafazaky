# Day 3 - Manage Server with Terminal

### **Q1 :**

Akses server menggunakan terminal (Windows Terminal/PuTTY/etc.)

### **A1 :**

![Akses Server dari Terminal](<Screenshot 2026-05-09 084815.png>)

---

### **Q2 :**

Konfigurasi ssh kalian agar bisa di akses hanya menggunakan publickey (password opsional, bisa dimatikan)

### **A2 :**

![Key yang tersimpan di Server](<Screenshot 2026-05-09 085033.png>)

![Key yang tersimpan di Local](<Screenshot 2026-05-09 085139.png>)

![Hapus akses password](<Screenshot 2026-05-09 090220.png>)

---

### **Q3 :**

Buat step by step penggunaan text manipulation! (grep, sed, cat, echo)

### **A3 :**

> **grep**
- singkatan dari "Global Regular Expression Print"
- fungsi: melakukan penyaringan teks di dalam file tujuan
- rumus: grep **<nama_kata_yang_dicari>** **<nama_file_tujuan>**
- ( grep hello text.txt ) akan menampilkan setiap teks "hello" di dalam file "text.txt"

> **sed**
- singkatan dari "Stream Editor"
- fungsi: melakukan manupulasi teks pada file tanpa membuka editor 
- rumus: sed 's/**<teks_lama>**/**<teks_baru>**/**<g | optional untuk efek global>**'
- ( sed 's/hello/hai/g' text.txt ) akan mengubah seluruh teks "hello" menjadi "hai" pada file "text.txt"

> **cat**
- singkatan  dari "Concatenate"
- fungsi: menampilkan isi teks suatu file
- jika kita memiliki "text.txt" dengan isi "text", ( cat text.txt ) akan menampilkan "text"
- jika kita memiliki "picture.jpg", ( cat picture.jpg ) akan menampilkan *gibberish* atau bahkan merusak tampilan terminal.
- ( cat > text.txt ) akan membuatkan file text.txt dan masuk ke mode penulisan. Kita bisa menuliskan apa pun setelahnya, lalu menekan "CTRL + D" untuk menyimpan dan keluar.

> **echo**
- fungsi: menampilkan sesuatu
- rumus: echo **<teks_bebas>**
- contoh: ( echo text ) akan menampilkan "text"
- ( echo text > text.txt ) akan membuat file "text.txt" pada dir aktif dan diisi dengan "text"

---

### **Q4 :**

Nyalakan ufw dengan memberikan akses untuk port 22, 80, 443, 3000, 5000 dan 6969!

### **A4 :**

![Status port yang diizinkan firewall](<Screenshot 2026-05-09 093523.png>)