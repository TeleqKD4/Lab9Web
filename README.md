## PHP Modular 
## header.php
```php
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
```

## footer.php
```php
        <footer>
            <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

## home.php
```php
<?php require('header.php'); ?>
<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
```

## about.php
```php
<?php require('header.php'); ?>
<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
```

## Halaman Home 
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/fd1f157c-05ac-4c59-91d3-a149f5dd1b76" />

## Halaman Abaout
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/24d75604-e200-48c0-9067-429e868569e4" />

