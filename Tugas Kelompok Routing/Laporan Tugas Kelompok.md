
# Tugas Kelompok Routing & Linux
![](https://www.seekpng.com/png/detail/416-4164571_logo-pens-png-electronic-engineering-polytechnic-institute-of.png)
-
## Anggota Kelompok :

- Alan Tri Arbani Hidayat (3121600056)
- Wiman Mahroja (3121600031)
- Emha Aji Putra Zaman (3121600042)
- Cantika Putri Romadhona (3121600051)

## Roadmap
 - Check Ip PC
 - Catat IP Address
 - Akses Router RB301 dengna winbox via Wine
 - Routing table pada RB301 ke seluruh subnet 192.168.x.x
 - Install Vbox
 - Install Ubuntu di Virtual Box

## Check IP PC dengan dhclient -v

Check apakah PC sudah mendapatkan ip address secara dhcp dengan `ip a`

![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/fd1ee5ae3e1a3b7a80e2fc5376aba72899df012c/Tugas%20Kelompok%20Routing/Screenshots/ip%20a.png)

Apabila masih belum mendapatkan Ip gunakan 
```
dhclient -v
```

## Catat IP Address

Setelah mendapatkan Ip address dari Router, catatlah ipnya dan juga catat ip RB301 Eth1 dan Eth2.

- IP PC
    - enps2s0
        <br> ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/fd1ee5ae3e1a3b7a80e2fc5376aba72899df012c/Tugas%20Kelompok%20Routing/Screenshots/ip%20pc.png)
- IP Router
    - Eth1 & Eth 2
        <br> ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/fd1ee5ae3e1a3b7a80e2fc5376aba72899df012c/Tugas%20Kelompok%20Routing/Screenshots/ip%20all.png)

## Akses Router RB301 dengan Winbox via Wine

Untuk menggunakan Winbox di Debian dibutuhkanlah dependency yaitu [**Wine**](https://www.winehq.org/). Berikut ini cara untuk install Wine dan Winbox

- Install Wine
    ```
    sudo apt install wine
    ```
- Download file winbox64.exe diwebsite [mikrotik](https://mikrotik.com/download)
    ```
    https://mikrotik.com/download
    ```
- Jalankan program winbox
    ```
    wine winbox64.exe
    ```
- Jangan lupa rubah winbox ke mode legacy agar bisa masuk ke interface

     ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/legacy.png)
     
- Masuk ke interface winbox

    ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/interface.png)

## Routing table pada RB301 ke seluruh subnet 192.168.x.x

Masuk ke `IP -> Route` untuk membuka konfigurasi Routing dan masukkan Dst Address dan Gaeteway masing-masing Kelompok

- Tabel Route 1

    ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/Route%201.png)

- Tabel Route 2

    ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/Route%202.png)

Hasil dari Seluruh Routing

<center><img src="https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/Route%202.png" alt="Kitten" title="A cute kitten" width="350" height="200" /> </center>


## Install Virtual Box

Untuk Install Virtual Box di Debian cukup sedikit rumit, dikarenakan menginstall beberapa dependecy dan juga command untuk memperbaiki dependency. Berikut Caranya

- Install Virtual Box
    - Via CLI
        ```
        sudo apt install virtualbox
        ```
    - Via .deb package
        > Masuk ke website download [virtualbox](https://www.virtualbox.org/wiki/Linux_Downloads) dan download untuk versi Debian 11
    - Install Package
        ```
        sudo dpkg -i (nama file virtualbox)
        ```
    - Install dependency build-essentials
        ```
        sudo apt install build-essentials dkms
        ```
    - Bila menemukan error saat menjalankan virtualbox. Masukkan command berikut
        ```
        sudo apt install -f
        ```
    - Jalankan Virtualbox
        ```
        virtualbox
        ```
    

Tampilan awal VirtualBox setelah dijalankan
    ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/virtualbox%20interface.png)

## Install Ubuntu di Virtual Box

Sebelum memulai penginstallan, persiapkanlah file .ISO ubuntu untuk memulai penginstallan

Berikut cara penginstallan Ubuntu di Virtual Box
- Membuat Nama Virtual machine dan memasukkan .ISO image Ubuntu

    ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/name%20vm.png)

- Tentukan Username Password serta nama Hostname

    ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/host.png)

- Tentukan Ukuran RAM dan CPU, Untuk perobaan kali ini diberikan 4 GB dan 4 core CPU

    ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/ram.png)

- Berikan Storage Virtual secukupnya. contoh dipercobaan ini adalah 40 GB

    ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/storage.png)

- Berikut ini adalah summary dari opsi konfigurasi pembuatan Virtual Ubuntu

    ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/summary.png)

- Tunggu hingga Selesai dan Ubuntu Siap digunakan

    ![](https://github.com/wimanmja/Workshop-Administrasi-Jaringan/blob/5d67322f40da63465b6428eef611cab318336493/Tugas%20Kelompok%20Routing/Screenshots/install.png)
