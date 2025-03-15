<p align="center">
<img width="512" alt="tugas git" src="https://github.com/user-attachments/assets/91160d40-4127-4bd9-bae1-f6d3dcdf7c73" />
</p>

<div align="center">

  # Implement GIT and Explaination

</div>

Hi there,I will inform you about,How to use GIT
## Initializing a Repository

Langkah-langkah untuk membuat dan menginisialisasi repository Git baru di komputer Anda:

1. **Buat Direktori Baru**  
   Jalankan perintah berikut untuk membuat folder baru dan masuk ke dalamnya:  
   ```bash
   mkdir nama-proyek
   cd nama-proyek

2. **Inisialisasi Repository Git**

   Untuk menginisialisasi repository Git di folder tersebut, jalankan perintah:
   ```bash
   git init

3. **Tambahkan Beberapa File**
   Buat file baru, misalnya Helloworld.js (untuk JavaScript) atau Helloworld.ts (untuk TypeScript):
   ```bash
   echo "console.log('Hello World');" > Helloworld.js

4. **Cek Status Repository**
   Periksa status repository untuk melihat perubahan yang belum dikomit:
   ```bash
   git status

5. **Tambahkan File ke Staging Area**
   Jalankan perintah berikut untuk menambahkan semua file ke staging area:
   ```bash
   git add .

6. **Lakukan Commit Pertama**
  Simpan perubahan dengan membuat commit pertama:
   ```bash
   git commit -m "Initial commit"


  **Ketika kita implementasi di VScode :**
  
  ![image](https://github.com/user-attachments/assets/ff0c28c1-96d8-40f5-b279-0f579e1bc9e7)


## 📂 Making Changes and Pushing to GitHub

Berikut adalah langkah-langkah untuk melakukan perubahan pada file, menambahkannya ke staging area, melakukan commit dengan pesan deskriptif, dan mengirimkannya ke GitHub.

### 1. Buat atau Ubah File
Lakukan perubahan pada file yang ada atau tambahkan file baru. Misalnya, edit file `index.js`:

```javascript
// Helloworld.js
console.log('Hello, TypeScript!');
console.log('Hello, TypeScript!');
```

**Kita Ubah Menjadi**

```javascript
// Helloworld.js
console.log('Hello, Javascript');
console.log('Hello, TypeScript!');
```
**Ketika kita implementasi di VScode :**

![image](https://github.com/user-attachments/assets/cdc1a154-4a0d-46a7-bee0-4926a58858f9)

**Lalu Kita lakukam:**
 ```bash
 git add .
```

## 2. **Lakukan Commit Perubahan**
  Simpan perubahan dengan menjalankan commit :
   ```bash
   git commit -m "Nama Perubahan/Nama File/"
   ```

## 3. **Push Perubahan ke GitHub**
   Untuk mengirim perubahan ke repository di GitHub, jalankan perintah berikut:
   ```bash
   git push origin main
   ```
   **Ketika kita implementasi di VScode :**


   ![image](https://github.com/user-attachments/assets/0a626485-7067-43b4-9fbf-4ca41053637f)

   ## 🌿 Working with Branches and Pushing to GitHub

Langkah-langkah berikut akan memandu Anda untuk membuat branch baru, melakukan perubahan pada file, menambahkannya ke staging area, melakukan commit dengan pesan deskriptif, dan mengirimnya ke GitHub.

---

### 1. Buat Branch Baru
Untuk membuat branch baru dan langsung berpindah ke branch tersebut, gunakan perintah berikut:

```bash
git checkout -b nama-branch-baru
```
### 2. Buat atau Ubah File
Lakukan perubahan pada file yang ada atau tambahkan file baru. Misalnya, edit file Helloworld.js:
```bash
console.log('Hello, Javascript');
console.log('Hello, TypeScript!');
console.log('New Output For New Branch'); // (+) menambahkan file 
```

### 3. **Cek Status Repository**
   Periksa status repository untuk melihat perubahan yang belum dikomit:
   ```bash
   git status
   ```

### 4. **Tambahkan File ke Staging Area**
   Jalankan perintah berikut untuk menambahkan semua file ke staging area:
   ```bash
   git add .
   ```

### 5. **Lakukan Commit di branch baru**
   Simpan perubahan dengan membuat commit branch baru:
   ```bash
   git commit -m "New branch commit"
   ```
### 6. Push Branch ke GitHub
  Untuk mengirim branch baru ke GitHub, jalankan perintah berikut:
  ```bash
  git push origin nama-branch-baru
  ```
  
  ![image](https://github.com/user-attachments/assets/6e802860-28a8-4f41-bd0a-b1eddc694a07)



   





   






  














  


