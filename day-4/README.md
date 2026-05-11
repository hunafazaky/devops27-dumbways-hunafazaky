# Day 4 - Version Control System with GIT

### **Q1 :**

Penjelasan tentang git

### **A1 :**

**Git** adalah salah satu *Version Control* yang dapat menyimpan setiap perubahan versi. Dengan teknologi ini, penggunanya dapat berpindah ke versi mana pun yang sudah pernah disimpan. Ini diperlukan, khususnya saat terjadi kesalahan pada versi terbaru atau butuhnya referensi di masa lalu, sehingga perlu melakukan *rollback*.

---

### **Q2 :**

Buat sebuah repositori bernama "devops27-dumbways-\<nama>", lalu tambahkan 3 file yang berisi text

### **A2 :**

File ini disimpan di Repository Github: **devops27-dumbways-hunafazaky**.

---

### **Q3 :**

Manage repository tugas kalian menggunakan terminal!

### **A3 :**

Seluruh file tugas sudah disimpan di **devops27-dumbways-hunafazaky** menggunakan perintah:
1. git add .
2. git commit -m 'pesan'
3. git push -u origin main

---

### **Q4 :**

Demokan cara untuk mencari perubahan text pada suatu file di GitHub!

### **A4 :**

Untuk mencari perubahan teks pada file tertentu, ada beberapa pendekatan yang dapat dilakukan.
- Menggunakan GUI melalui GitHub secara langsung.
  1. Kunjungi file tujuan dan klik "History"
  ![Halaman file GitHub](<Screenshot 2026-05-11 201211.png>)
  2. Pilih salah satu hash untuk melihat detail perubahan
  ![Halaman history](<Screenshot 2026-05-11 201337.png>)
  3. Anda bisa melihat teks apa yang ditambahkan dan file apa yang dihapus.
  ![Halaman detail perubahan](<Screenshot 2026-05-11 201537.png>)

- Menggunakan CLI melalui terminal
  Di dalam terminal proyek yang kita kerjakan, ada beberapa perintah yang dapat membantu kita mencari perubahan yang sudah tersimpan:
  
  1. ```git log```

  perintah ini dapat memperlihatkan seluruh perubahan yang pernah dilakukan pada seluruh file di dalam proyek.

  ![Halaman log](<Screenshot 2026-05-11 203319.png>)

  2. ```git log <path_file>```

  perintah ini dapat memperlihatkan seluruh perubahan yang pernah dilakukan file yang dituju.

  ![Halaman log file tertentu](<Screenshot 2026-05-11 203700.png>)

  3. ```git log -S "teks_yang_dicari" -- <path_file>```

  perintah ini dapat memperlihatkan perubahan spesifik berdasarkan kata kunci, pada file yang dituju. 

  ![Halalam log file tertentu dengan kata kunci tertentu](<Screenshot 2026-05-11 203852.png>)