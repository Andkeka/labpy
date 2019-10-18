> **#Latihan1 >> README.md**

**_Cara dan tutorial menggunakan bit_**


•	Pertama kita harus mendownload aplikasi git, dengan membuka website resminya 
[(git-scm.com) ](url)

![1](https://user-images.githubusercontent.com/56200287/66642740-846bc800-ec47-11e9-90a2-7f3d3380bb2d.PNG)

•	Setelah selesai mendownload , kita install terlebih dahulu
•	Setelah terinstall, kita lakukan configurasi user.name dan user.email. perintah yang harus ditulis adalah : _**(gitconfig -–global user.name “name_user”)
                          (gitconfig –-global user.emai “email_user")**_
                          
![2](https://user-images.githubusercontent.com/56200287/66642748-89307c00-ec47-11e9-81d6-8246280df052.PNG)                          
 
•	Membuat repository local
•	Buka directory aktif misalnya : **_D :/labs_pemograman1_** (buka menggunakan Windows explore)
•	Klik kanan pada directory aktif tersebut, dan pilih menu git bash, sehingga muncul **_Git Bash Commad_**

![3](https://user-images.githubusercontent.com/56200287/66642787-96e60180-ec47-11e9-9997-5e1ce23faacc.PNG)
 
•	Lalu ketikan perintah 
_**(mkdir latihan1)
(cd latihan1)**_
•	Directory aktif menjadi **_D:/Labs_pemograman1/latihan1_**

![4](https://user-images.githubusercontent.com/56200287/66641049-2d182880-ec44-11e9-9087-dc16f9b09e41.PNG)
 
•	Lalu jalan kan perintah git ini, untuk membuat repository local
                      **_(git init)_**
•	Menambahkan  File baru pada Repository
•	Kita akan mencoba membuat satu file README.md (text file) dengan menuliskan perintah
 **_(echo “#latihan 1 >> README.md)_**
•	Untuk menambahkan file tersebut kita gunakan perintah 
**_(git add README.md)_**

![5](https://user-images.githubusercontent.com/56200287/66641060-32757300-ec44-11e9-9314-23fbcbf191f5.PNG)
 
•	Commit (menyimpan perubahan ke database)
•	Untuk menyimpan perubahan tersebut kita ketikan perintah
 **_(git commit –m “komentar commit”)_**
•	Perubahan berasil tersimpan

![6](https://user-images.githubusercontent.com/56200287/66641075-399c8100-ec44-11e9-9fbd-f8c612f31361.PNG)
 
8.	Membuat repository server
•	Pertama kita akan membuka website (https://github.com)
•	kita harus membua takun terlebih dahulu di github
•	pada halaman github, klik tombol star a project, atau klik new Repository pada icon (+) kanan atas pada layar. 

![7](https://user-images.githubusercontent.com/56200287/66641076-399c8100-ec44-11e9-8010-fe1dfc8e2644.PNG)
 
•	isi name repostorynya **_labpy_**
•	lalu klik create repository
 
9.	Menambahkan Remote Repository 
•	Untuk menambahkan remote repository server, kita ketik perintah
 **_(git remote add origin [url])
Git  remote add origin https://github.com/Andkeka/labpy.git_**

![8](https://user-images.githubusercontent.com/56200287/66641077-3a351780-ec44-11e9-991f-0a10888c6595.PNG)

10.	Push (mengirim perubahan ke server)
•	Untuk melakukan perubahan kita perlu menggunakan perintah
 **_(git push –u origin master)_**
•	Perintah ini akan menyuruh kita memasukan username dan password pada akun github kita.

![9](https://user-images.githubusercontent.com/56200287/66641078-3a351780-ec44-11e9-999d-e209eb7daa0b.PNG)
 
11.	Melihat hasil pada server repository
•	Buka halaman github.com, arahkan pada repositorynya
•	Maka perubahan akan terlihat pada halaman tersebut

![10](https://user-images.githubusercontent.com/56200287/66641081-3acdae00-ec44-11e9-972e-c9c391985fe1.PNG)
 
12.	Clone repository
•	Untuk melakukan cloning, gunakan printah (git clone [url])
•	**_(git clone htpps://github.com/Andkeka/labpy.git)_**

![11](https://user-images.githubusercontent.com/56200287/66641083-3acdae00-ec44-11e9-84d3-15ea791958f6.PNG)
