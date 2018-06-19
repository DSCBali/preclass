Kita tidak akan terlalu fokus ke NodeJS tapi kita akan membutuhkannya untuk install beberapa modules yang akan dipakai nanti pada saat kelas.

Berikut adalah cara termudah untuk install NodeJS, jika kalian ingin cara yang lebih advance bisa coba kunjungin di 
[Advance](#advance)

# Instalasi NodeJS

- [Windows](#windows)
- [Mac](#mac)
- [Linux](#linux)

## Linux

Panduan untuk distro berbasis **Debian** dan **Ubuntu**

Termasuk: Linux Mint, Linux Mint Debian Edition (LMDE), elementaryOS, bash pada Windows dan lainnya.

Buka terminal dan jalankan perintah berikut untuk menginstall NodeJS LTS v.8.11.3:
```
curl -sL https://deb.nodesource.com/setup_8.11.3 | sudo -E bash -
sudo apt-get install -y nodejs
```

Pastikan nodejs sudah terinstall dengan menjalankan perintah berikut untuk melihat versinya:
```
node -v
```

Setelah NodeJS terinstall, upgrade NPM ke versi terbaru dengan perintah berikut:
```
sudo npm install npm@latest -g
```

Selanjutnya install build tools untuk dapat mengcompile dan menginstall native addons dari npm dengan perintah berikut:
```
sudo apt-get install -y build-essential
```

Untuk distro lainnya bisa kunjungi [disini](https://nodejs.org/en/download/package-manager)


## Mac

Buka link berikut: [Node JS](https://nodejs.org/en/download/).

Pilihlah intaller yang `.pkg`.
Lalu tinggal ikuti saja langkah-langkah installernya.

Setelah selesai pastikan node sudah terinstall dengan membuka terminal dan jalankan perintah berikut:
`node -v`

Terakhir kalian perlu update `npm`. Bisa dengan cara berikut di terminal:
`npm install npm --global`

## Windows

Buka link berikut: [Node JS](https://nodejs.org/en/download/).

Pilihlah intaller yang `.msi` dan versi bit yang sesuai dengan OS Windows yang kamu pakai.
Lalu tinggal ikuti saja langkah-langkah installernya.

Setelah selesai pastikan node sudah terinstall dengan membuka terminal dan jalankan perintah berikut:
`node -v`

Terakhir kalian perlu update `npm`. Bisa dengan cara berikut di terminal:
`npm install npm --global`


## Advance
Kalian bisa pilih diantara 2 pilihan version manager berikut:
- [nvm](https://github.com/creationix/nvm)
- [n](https://github.com/tj/n)

<br>
<br>

### [Kembali ke awal](README.md)
