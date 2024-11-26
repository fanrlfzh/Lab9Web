# Lab9Web

#Header.php

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contoh Modularisasi</title>
<link href="style.css" rel="stylesheet" type="text/stylesheet"
media="screen" />
</head>
<body>
<div class="container">
<header>
<h1>Modularisasi Menggunakan Require</h1>
</header>
<nav>
<a href="home.php">Home</a>
<a href="about.php">Tentang</a>
<a href="kontak.php">Kontak</a>
</nav>
![Screenshot (531)](https://github.com/user-attachments/assets/aec8b188-9ab9-453c-b0a6-5bcd4073296b)

#Footer.php

<footer>
<p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
</footer>
</div>
</body>
</html>
<?php require('header.php'); ?>
<div class="content">
![Screenshot (532)(1)](https://github.com/user-attachments/assets/e9450e61-ae40-447f-912f-18865ee628f9)

#Home.php

<?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman Home</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
![Screenshot (534)](https://github.com/user-attachments/assets/7a3a22ee-4fb4-4d1e-8195-9baef39ea263)

#About.php

<?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman About</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
![Screenshot (536)](https://github.com/user-attachments/assets/72c3e425-269b-45e7-9e4e-bbde3db809e7)




