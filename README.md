# Lab9web_
<table>
  <tr>
    <th colspan="2">DATA MAHASISWA</th>
  </tr>
  <tr>
    <td>Nama</td>
    <td>Aas Novitasari</td>
  </tr>
  <tr>
    <td>NIM</td>
    <td>312210167</td>
  </tr>
  <tr>
    <td>Kelas</td>
    <td>TI.22.A1</td>
  </tr>
</table>

## Tujuan
1. Mahasiswa mampu memahami konsep dasar Modularisasi Program.
2. Mahasiswa mampu memahami konsep dasar Fungsi pada PHP.
3. Mahasiswa mampu membuat program Modular sederhana menggunakan PHP.
4. Mahasiswa mampu mengimplementasikan penggunaan fungsi pada PHP
## Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab9_php_modular pada docroot webserver (htdocs)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya. 

## Langkah-langkah Praktikum
1. Buat file baru dengan nama header.php
   
   ```
       <h1>Modularisasi</h1>
    <nav>
        <a href="home.php">Home</a>
        <a href="about.php">Tentang</a>
        <a href="kontak.php">Kontak</a>
        <a href="index.php">Data Barang</a>
    </nav>
   ```
 
    ![Screenshot 2023-12-09 114126](https://github.com/aasnovita114/Lab9web_/assets/116045324/85bd96be-bb0b-4595-9f6e-ea82ebb711ae)

2. Buat file baru dengan nama footer.php
   ```
       <footer>
        <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
    </footer>
   ```
   ![Screenshot 2023-12-09 114958](https://github.com/aasnovita114/Lab9web_/assets/116045324/99eee949-25a1-4e0a-baae-dddfff5c5a65)

3. Buat file baru dengan nama Home.php
   ```
       html 
        <?php require('header.php'); ?>

        <div class="content">
        Modul Praktikum Pemrograman Web
        Agung Nugroho (agung@pelitabangsa.ac.id) 78
        Universitas Pelita Bangsa, Bekasi
            <h2>Ini Halaman Home</h2>
            <p>Ini adalah bagian content dari halaman.</p>
        </div>

        <?php require('footer.php'); ?
   ```
   ![Screenshot 2023-12-09 115339](https://github.com/aasnovita114/Lab9web_/assets/116045324/43ceed12-50df-4678-9437-ba9e1962c2f6)

4. Buat file baru dengan nama about.php
   ```
   <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
    <style>
</head>

<body>
        <?php require('header.php'); ?>
        <section id="about" class="about">
            <h2>About</h2>
            <div class="row">
                <div class="about-img">
                    <img src="c:\Users\aasno\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\E6ACF4B0F69F6F6E60E9A815938AA1FF\WhatsApp Image 2023-12-09 at 11.32.17_a13407d5.jpg">
                </div>
                <div class="content">
                    <h3>Hello!!</h3>
                    <p>perkenalkan nama saya Aas Novitasari dari kelas Ti.22.A1 di Universitas Pelita Bangsa,saya anak pertama dan satu - satunya yang orang tua saya sayangi,dan di perkuliahan saya di kelilingi dengan teman - teman yang baik.</p>
                </div>
        </section>
        <?php require('footer.php'); ?>
    </div>
</body>

</html>
```


