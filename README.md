# PRAKTIKUM PEMPROGRAMAN WEB
Nama  : Komarudin <p>
NIM   : 312010068 <p>
Kelas : TI.20.D.1 <p>
## Praktikum 9: PHP Modular<p>
### Langkah-langkah Praktikum<p>
  Membuat Folder Baru dengan nama <b> lab9_php_modular </b>
  ![image](https://user-images.githubusercontent.com/101499377/170850638-5b2f4cba-fc00-4b35-b9cf-5954d275cd62.png)<p>
  Buat File baru dengan nama <b> header.php </b><p>
  ![image](https://user-images.githubusercontent.com/101499377/170850678-b772b111-9c2f-4726-91ae-4f7273393302.png)<p>
  Buat file baru dengan nama <b> footer.php</b><p>
  ![image](https://user-images.githubusercontent.com/101499377/170850750-25c40576-9f0a-45c1-b809-22f02e7841ba.png)<p>
  Buat file baru dengan nama <b> home.php </b><p>
  ![image](https://user-images.githubusercontent.com/101499377/170850835-ed9f9634-faf4-4454-b770-66d9368efd97.png)<p>
  Buat file baru dengan nama <b> about.php </b><p>
  ![image](https://user-images.githubusercontent.com/101499377/170850877-0c292015-f5a5-44c9-bec8-ae998e417865.png)<p>
  lalu buka link : http://localhost/lab9_php_modular/home.php untuk melihat hasilnya.<p>
    ![image](https://user-images.githubusercontent.com/101499377/170858960-f6bb6f4b-ed82-4549-8151-e0b16a7b9b79.png)<p>

## Pertanyaan dan Tugas.<p>
### Implementasikan konsep modularisasi pada kode program praktikum 8 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.<p>
Buat folder baru dengan nama <b> Modular </b> didalam folder <b>lab9_php_modular </b><p>
      ![image](https://user-images.githubusercontent.com/101499377/170859251-ec1f2d1f-617b-431d-82c0-485e568e98ae.png)<p>
Copy/salin file koneksi.php dan hapus.php dari praktikum 8 lalu simpan dalam folder lab9_php_modular/modular<p>
      ![image](https://user-images.githubusercontent.com/101499377/170859416-89313c99-0116-475d-81f2-090b1b81c1ef.png)<p>
![image](https://user-images.githubusercontent.com/101499377/170859433-e665596e-b1d5-48a3-b6c8-40bf8eda94c1.png)<p>
  Buat file baru dengan nama <b>header_index.php</b> <p>
  ![image](https://user-images.githubusercontent.com/101499377/170860011-c78efbb3-a376-4126-b735-8cf27493a593.png)<p>
  Buat file baru dengan nama <b> footer_index.php</b><p>
  ![image](https://user-images.githubusercontent.com/101499377/170860095-62a9e7da-cb55-4eb5-afb8-c07e0cb164fb.png)<p>
Buat file index.php. dan kemudian tambahkan syntax <?php require('header_index.php'); ?> pada bagian atas dan bawah body index.php<p>
  ![image](https://user-images.githubusercontent.com/101499377/170860211-1c209a6b-916f-4c84-b812-20784c78342b.png)<p>
![image](https://user-images.githubusercontent.com/101499377/170860644-009ddea3-51c7-4645-a7f1-fcfd0357131e.png)<p>
  Lalu buka link : http://localhost/lab9_php_modular/modular/index.php untuk melihat hasilnya.<p>
  ![image](https://user-images.githubusercontent.com/101499377/170860668-267171aa-26dc-4371-aa22-07af7ac99c89.png)<p>
  Selanjutnya kita modularkan halaman tambah dengan membuat file baru <b>header_tambah.php</b><p>
  ![image](https://user-images.githubusercontent.com/101499377/170860692-d7b1f729-5813-4a18-b421-cc75e70aee50.png)<p>
![image](https://user-images.githubusercontent.com/101499377/170861292-dac7d3ce-f09e-4436-be5f-d0aea2a67766.png)<p>
  Buat file <b>footer_tambah.php</b><p>
  ![image](https://user-images.githubusercontent.com/101499377/170860743-7219bb57-a72c-499d-808e-fc47e7622207.png)<p>
  Buat file <b>tambah.php</b>. kemudian tambahkan <?php require('footer_tambah.php'); ?> pada bagian bawah body tambah.php<p>
  ![image](https://user-images.githubusercontent.com/101499377/170860819-d5126f2c-e630-48f7-a401-81a12ad1920b.png)<p>
![image](https://user-images.githubusercontent.com/101499377/170860829-8069dfd6-5545-47b9-aa7c-dc1542affe06.png)<p>
  Lalu buka link : http://localhost/lab9_php_modular/modular/tambah.php untuk melihat hasilnya.<p>
  ![image](https://user-images.githubusercontent.com/101499377/170861479-dbb673df-71ef-448d-aaff-f574fa7e8b4a.png)<p>
 modularkan halaman ubah dengan membuat file baru <b>header_ubah.php</b><p>
   ![image](https://user-images.githubusercontent.com/101499377/170861547-eada4d6b-c5bc-49ab-ad46-5b691867bb46.png)<p>
![image](https://user-images.githubusercontent.com/101499377/170861562-a55a1b3f-dbb6-45cf-8cce-32da92e6203c.png)<p>
![image](https://user-images.githubusercontent.com/101499377/170861880-8bf88bdd-02c7-4ef5-962b-cb60362fc302.png)<p>
Buat file <b>footer_ubah.php</b><p>
  ![image](https://user-images.githubusercontent.com/101499377/170861638-f6021a85-c8ea-4285-b631-9a96a44e81fe.png)<p>
Buat file <b>ubah.php</b> dan kemudian tambahkan <?php require('footer_ubah.php'); ?> pada bagian bawah body ubah.php <p>
  ![image](https://user-images.githubusercontent.com/101499377/170861729-1b30a78e-5138-496d-a773-4b5cdd4d446b.png)<p>
    ![image](https://user-images.githubusercontent.com/101499377/170861750-c5397032-099b-4b9c-bd7d-23a9b5bc9a9e.png)<p>
Lalu buka link : http://localhost/lab9_php_modular/modular/ubah.php?id=3 untuk melihat hasilnya.<p>
  ![image](https://user-images.githubusercontent.com/101499377/170861948-76195178-3224-456d-9e1e-3030d1fdbf79.png)
