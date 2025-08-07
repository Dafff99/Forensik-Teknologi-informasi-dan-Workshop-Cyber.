# Belajar Cara Kerja GitHub

Repository ini dibuat untuk membantu pemula memahami dasar-dasar penggunaan Git dan GitHub.

## ✨ Tujuan
- Menjelaskan perbedaan Git dan GitHub
  Git adalah alat yang kamu gunakan untuk mengelola riwayat perubahan kode secara lokal.
➤ Contoh: kamu sedang ngoding dan ingin simpan perubahan tanpa overwrite.

   GitHub adalah tempat kamu menyimpan project Git secara online, sehingga:
   1.Bisa diakses dari mana saja
   2.Bisa kerja bareng tim
   3.Bisa pamerkan proyek ke dunia
  
- Mengenalkan perintah dasar Git
  | 🔧 Perintah     | 📄 Fungsi                               | 🧪 Contoh                                    |
| --------------- | --------------------------------------- | -------------------------------------------- |
| `git init`      | Membuat repository Git di folder lokal  | `git init`                                   |
| `git clone`     | Menyalin repo dari GitHub ke lokal      | `git clone https://github.com/user/repo.git` |
| `git status`    | Melihat status file yang berubah        | `git status`                                 |
| `git add`       | Menambahkan file ke area staging        | `git add index.html`                         |
| `git commit`    | Menyimpan perubahan ke repository       | `git commit -m "Pesan commit"`               |
| `git push`      | Mengirim perubahan ke GitHub            | `git push origin main`                       |
| `git pull`      | Mengambil perubahan terbaru dari GitHub | `git pull origin main`                       |
| `git log`       | Melihat riwayat commit                  | `git log`                                    |
| `git branch`    | Melihat daftar cabang (branch)          | `git branch`                                 |
| `git checkout`  | Berpindah ke branch lain                | `git checkout nama-branch`                   |
| `git merge`     | Menggabungkan branch ke branch aktif    | `git merge fitur-baru`                       |
| `git remote -v` | Menampilkan alamat remote GitHub        | `git remote -v`   

 Tips
      Gunakan git status sering-sering untuk melihat perubahan
      Gunakan git log --oneline untuk riwayat yang lebih ringkas
      Gunakan git checkout -b nama untuk buat dan langsung pindah ke branch baru


## 📚 Isi Repository

- Alur Kerja GitHub
  | Langkah                 | Perintah Git                  | Penjelasan                        |
| ----------------------- | ----------------------------- | --------------------------------- |
| 1️⃣ Inisialisasi        | `git init`                    | Membuat repository Git lokal      |
| 2️⃣ Tambah file         | `git add`                     | Menandai file untuk disimpan      |
| 3️⃣ Commit              | `git commit -m "pesan"`       | Menyimpan snapshot perubahan      |
| 4️⃣ Hubungkan ke GitHub | `git remote add origin <URL>` | Mengaitkan repo lokal ke GitHub   |
| 5️⃣ Push ke GitHub      | `git push -u origin main`     | Mengirim perubahan ke GitHub      |
| 6️⃣ Pull dari GitHub    | `git pull origin main`        | Mengambil update terbaru          |
| 7️⃣ Branch (opsional)   | `git checkout -b fitur-x`     | Buat cabang untuk fitur/percobaan |
| 8️⃣ Merge (opsional)    | `git merge fitur-x`           | Gabungkan fitur ke main branch    |

- Diagram Alur
  +-------------------+
|   git init        | ← Inisialisasi project
+-------------------+
          ↓
+-------------------+
|   git add .       | ← Tambah file ke staging
+-------------------+
          ↓
+-------------------+
| git commit -m ""  | ← Simpan perubahan lokal
+-------------------+
          ↓
+-----------------------------+
| git remote add origin URL  | ← Hubungkan ke GitHub
+-----------------------------+
          ↓
+--------------------------+
| git push -u origin main | ← Upload ke GitHub
+--------------------------+




## 📄 Lisensi
Proyek ini berlisensi MIT — silakan digunakan dan dikembangkan.
