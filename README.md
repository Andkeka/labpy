#Latihan1 >> README.md

#Cara menggunakan bit


•	Pertamakitaharusmendownloadaplikasigit, denganmembuka website resminya (git-scm.com) 

![1](https://user-images.githubusercontent.com/56200287/66642740-846bc800-ec47-11e9-90a2-7f3d3380bb2d.PNG)

•	Kita install terlebihdahulu
•	Setelahterinsltall, kitalakukanconfigurasi user.name dan user.emai. perintah yang harus ditulisialah : (gitconfig –global user.name “name_user”)
                          (gitconfig –global user.emai “email_user)
                          
![2](https://user-images.githubusercontent.com/56200287/66642748-89307c00-ec47-11e9-81d6-8246280df052.PNG)                          
 
•	Membuat repository local
•	Buka directory aktifmisalnya : D :/labs_pemograman1 (bukamenggunakan Windows explore)
•	Klikkananpada directory aktiftersebut, danpilih menu git bash, sehinggamunculgit bash commad

![3](https://user-images.githubusercontent.com/56200287/66642787-96e60180-ec47-11e9-9997-5e1ce23faacc.PNG)
 
•	Laluketikanperintah (mkdir latihan1)
                                       (cd latihan1)
•	Directory aktifmenjadi C:/Labs_pemograman1/latihan1

![4](https://user-images.githubusercontent.com/56200287/66641049-2d182880-ec44-11e9-9087-dc16f9b09e41.PNG)
 
•	Lalujalankanperintahgitini, untukmembuatrepositorynlocal
                      (gitini)
•	Menambahkan  File barupada Repository
•	Kita akanmencobamembuatsatu file README.md (text file) denganmenuliskanperintah (echo “#lathan 1 >> README.md)
•	Untukmenambahkan file tersebutkitakitagunakanperintah (git add README.md)

![5](https://user-images.githubusercontent.com/56200287/66641060-32757300-ec44-11e9-9314-23fbcbf191f5.PNG)
 
•	Commit (menyimpanperubahanke database)
•	Untukmenyimpanperubahantersebutkitaketikanperintah (git commit –m “komentar commit”)
•	Perubhanberasiltersimpan

![6](https://user-images.githubusercontent.com/56200287/66641075-399c8100-ec44-11e9-9fbd-f8c612f31361.PNG)
 
8.	Membuat repository server
•	Pertamakitaakanmembuka website https://github.com
•	kitaharusmembuatakunterlebihdahulu di github
•	padahalamangithub, kliktombol star a project, atauklik new Repository pada icon (+)

![7](https://user-images.githubusercontent.com/56200287/66641076-399c8100-ec44-11e9-8010-fe1dfc8e2644.PNG)
 
•	isi name repostorynya :labpy
•	laluklikcreate repository
 
9.	Menambahkan Remote Repository 
•	Untukmenambahkan remote repository server, kitaketikperintah (git remote add origin [url])
Git  remote add origin https://github.com/Andkeka/labpy.git

![8](https://user-images.githubusercontent.com/56200287/66641077-3a351780-ec44-11e9-991f-0a10888c6595.PNG)

10.	Push (mengirimperubahanke server)
•	Untukmelakukanperubahankitaperlumenggunakanperintah (git push –u origin master)
•	Perintahiniakanmenyuruhkitamemasukan username dan password pad akungithub

![9](https://user-images.githubusercontent.com/56200287/66641078-3a351780-ec44-11e9-999d-e209eb7daa0b.PNG)
 
11.	Melihathasilpada server repository
•	Bukahalaman github.com, arahkanpadarepositorynya
•	Makaperubahanakanterlihatpadahalamntersebut

![10](https://user-images.githubusercontent.com/56200287/66641081-3acdae00-ec44-11e9-972e-c9c391985fe1.PNG)
 
12.	Clone repository
•	Untukmelakukan cloning, gunakanprintah (git clone [url
•	(git clone htpps://github.com/Andkeka/labpy.git

![11](https://user-images.githubusercontent.com/56200287/66641083-3acdae00-ec44-11e9-84d3-15ea791958f6.PNG)
