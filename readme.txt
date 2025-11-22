--- how to integrate GO project in Visual Studio Code to GitHub ---
https://www.google.com/search?q=how+to+integrate+project+in+visual+studio+code+to+github&oq=how+to+integrate+project+in+visual+studio+code+to+github&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIHCAEQIRigATIHCAIQIRifBTIHCAMQIRifBdIBCTE0OTM2ajBqN6gCALACAA&sourceid=chrome&ie=UTF-8

--- prasyarat ---
1. PC: Install Git
2. GitHub: Buat GitHub account / Sign in ke GitHub
3. PC: Install VS Code

--- Langkah-Langkah Integrasi dan Mengunggah Project ke GitHub ---
1. GitHub: setelah sign in, ke Repository, Create New Project,
   beri nama dan deskripsi, Confirmation. Misal nama Project "My-Project"
2. GitHub & PC: simpan HTTPS URL Project yang terbentuk.
   Misal: "GitHub.com/gidhsk/My-Project" (tanpa https://)
3. PC: buat folder "My-Project"
4. PC: Jalankan VS Code, buka folder "My Project", buka Terminal (Ctrl+J)
5. PC: Initialize a Git repository dengan command berikut:
	[git init]
6. PC: integrasikan dengan repository di GitHub:
	[git remote add origin GitHub.com/gidhsk/My-Project]
7. PC: Unggah Project (master / main branch) ke repository GitHub:
	[git push -u origin master]
8. PC: Autentikasi dengan GitHub (Sign in dengan browser atau
       gunakan Personal Access Token / PAT)
9. Langkah-Langkah menambahkan / mengupdate file di repository GitHub:
   a. Tambahkan semua file project ke GitHub:
	[git add .]
      atau file tertentu:
	[git add nama_file.ext]
   b. Commit perubahan, tambahkan keterangan:
	[git commit -m "pesan-pesan"]
   c. Unggah Project:
	[git push origin master]
