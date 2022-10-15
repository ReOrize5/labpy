
Nama : Fabian Eka Prasetyo

NIM : 312210301

Kelas : TI. 22 A.3

1. Pertama tama konfigurasi dengan cara masukan username dan email
![Screenshot 2022-10-14 085302](https://user-images.githubusercontent.com/115756982/195963446-7283e927-83cf-4d53-95b7-a0b6091c3c5a.png)

2. Pilih direktori yang aktif contoh nya c:/labs_pemograman1, klik kanan lalu pilih "git bash here"
![Screenshot 2022-10-14 085753](https://user-images.githubusercontent.com/115756982/195963493-d0557c0b-7d1d-4d9c-95fd-07787ef10af1.png)

3. Buat direktori dengan perintah "mkdir" dan masuk ke direktori nya menggunakan perintah "cd" lalu gunakan perintah git init untuk membuat repository local

![Screenshot 2022-10-14 085948](https://user-images.githubusercontent.com/115756982/195963507-f70fff37-1307-423b-a58b-9f0bf096993f.png)

4. Lalu buat file readme menggunakan perintah "echo" agar filenya terbaca
![Screenshot 2022-10-14 090215](https://user-images.githubusercontent.com/115756982/195963531-cb438144-1e7d-48e6-a3a3-3ccce1a21f8e.png)

setelah berhasil memasukan filenya jangan lupa kalian mengecek status jika ada file yang ditambahkan dengan perintah " git status"

![Screenshot 2022-10-14 091305](https://user-images.githubusercontent.com/115756982/195963635-17452f76-99bf-4337-9346-f95a86bc712a.png)


5. Gunakan Perintah "nano" untuh mengubahnya

![Screenshot 2022-10-14 091434](https://user-images.githubusercontent.com/115756982/195963662-8dc4d476-157a-48d7-b641-2013ddeb59d5.png)


didalamnya kosong contoh isi dengan " latihan menggunakna Git "


![Screenshot 2022-10-14 091355](https://user-images.githubusercontent.com/115756982/195963678-9768ae5f-2fad-4a3e-a8da-5109b384e661.png)

6. Gunakan perintah "git commit -m" untuk menyimpan perubahan kedalam data base repository local
![Screenshot 2022-10-14 091517](https://user-images.githubusercontent.com/115756982/195963767-248d63bf-d491-4adc-9d97-e966709fe414.png)

7. Buatlah repository server menggunakan GitHub (membuat akun terlebih dahulu) dengan cara klik ikon (+) lalu New Repository
![Screenshot 2022-10-15 085637](https://user-images.githubusercontent.com/115756982/195963918-341b0ae0-6680-4b84-a4d9-0c7c9ab61f8b.png)

Beri nama Repository Server kalian

![Screenshot 2022-10-15 085801](https://user-images.githubusercontent.com/115756982/195963956-d3bb61ac-2adb-4bc6-b3a3-511ffe0edf7d.png)

8. Kembali ke GitBash, lalu gunakan perintah git remote add origin (URL) untuk menambakan Remote Repository, Remote Repository adalah repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository agar diakses oleh banyak user.

![Screenshot 2022-10-14 091600](https://user-images.githubusercontent.com/115756982/195964010-c34161f8-126e-44a4-963a-2db926853b16.png)

9. Untuk mengirim perubahan repository local ke server gunakan perintah "git push -u origin master" biasanya akan dimintai akses menggunakan username dan password

![Screenshot 2022-10-14 091632](https://user-images.githubusercontent.com/115756982/195964029-80d710d7-2bee-44c1-8766-ba48c108307a.png)

cek repositorynya di github yang kalian buat

![Screenshot 2022-10-15 090447](https://user-images.githubusercontent.com/115756982/195964107-728edb2e-2f6f-4486-9d9d-1b6c56f1e930.png)

jika berhasil maka ada file yang ditambhkan di Githubnya

10. Untuk menyalin Repository server gunakan perintah "git clone (url)"

![Screenshot 2022-10-14 091822](https://user-images.githubusercontent.com/115756982/195964211-63cff1c9-24ff-4230-b1c9-49a1848a7ff4.png)

Jika berhasil maka satu direktori nya secara muncul secara otomatis pada direktori yang tertuju
