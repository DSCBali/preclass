# Instalasi Composer

- [Windows](#windows)
- [Mac](#mac)
- [Linux](#linux)


## Mac

Siapkan Terminal dan koneksi internet.
Akses direktori tmp pada terminal dengan perintah 
```
cd /tmp
```

Kemudian unduh berkas composer.phar dengan perintah berikut :
```
curl -sS https://getcomposer.org/installer | php  
```

Setelah itu pindahkan ke direktori /usr/local/bin agar dapat diakses secara global menggunakan perintah
```
mv composer.phar /usr/local/bin/composer 
```

Dan composer dapat diakses secara global

## Linux

Untuk proses installasi composer di Linux sama seperti Mac karena memiliki base Unix OS

## Windows

Download installernya di [Composer for Windows](https://getcomposer.org/Composer-Setup.exe).

Instalasi akan langsung melakukan setup pada PATH Environtment dan sudah dapat menggunakan command `composer` dari folder manapun.

<br>
<br>

### [Kembali ke awal](README.md)