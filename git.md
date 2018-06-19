# Instalasi Git

- [Windows](#windows)
- [Mac](#mac)
- [Linux](#linux)

Untuk memastikan apakah **git** sudah terinstall bisa coba jalankan *command* di bawah:
```shell
git --version
```

## Linux
Untuk mengetahui apa jenis distribusi linux anda bisa dilihat disini: [List of Linux distributions – Wikipedia](http://en.wikipedia.org/wiki/List_of_Linux_distributions). Rata-rata sistem *Linux* merupakan berbasis *Debian*.

## Sistem linux berbasis *Debian*

**Buka Terminal. Copy & paste code di bawah** ke terminal anda lalu tekan **Enter**. Anda mungkin akan diminta untuk memasukkan *password*.

```shell
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install git
```

## Sistem linux berbasis *Red Hat*

**Buka Terminal. Copy & paste code di bawah** ke terminal anda lalu tekan **Enter**. Anda mungkin akan diminta untuk memasukkan *password*.

```shell
sudo yum upgrade
sudo yum install git
```

## Mac

Buka terminal anda.
Cara termudah adalah dengan menginstall **homebrew**.

### Langkah 1 – Install [*Homebrew*](http://brew.sh/)

**Buka Terminal. Copy & paste code di bawah** ke terminal anda lalu tekan **Enter**.

```shell
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew doctor
```

Anda mungkin akan diminta untuk install *Command Line Developer Tools* from *Apple* (Pastikan anda pilih *Install* / *Confirm*.

## Step 2 – Install *Git*

**Buka Terminal. Copy & paste code di bawah** ke terminal anda lalu tekan **Enter**.

```shell
brew install git
```

## Windows
Kamu bisa gunakan beberapa tools untuk membuka terminal:
- Command Prompt (tidak dianjurkan)
- Powershell
- Git Shell (biasanya sudah ada ketika install git)
- [Cygwin](https://www.cygwin.com/)

**Download** *Git* dari [Git for Windows](http://msysgit.github.io/).

<br>
<br>

### [Kembali ke awal](README.md)
