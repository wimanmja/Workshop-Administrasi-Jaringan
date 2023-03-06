LAPORAN RESMI PRAKTIKUM
WORKSHOP ADMINISTRASI JARINGAN
LINUX UBUNTU/DEBIAN

Dosen Pengampu : Dr. Ferry Astika Saputra ST, M.Sc

Nama : Wiman Mahroja
Kelas : 2 D4 IT B
NRP : 3121600031

Program Studi D4 Teknik Informatika
Politeknik Elektronika Negeri Surabaya
2022/2023

Isi

A. Evolusi OS
1. GM-NAA I/O (1956): Sistem operasi pertama yang dikembangkan oleh General Motors Research Laboratories untuk digunakan pada komputer mainframe Univac.
2. IBM OS/360 (1960): Sistem operasi yang dikembangkan oleh IBM untuk digunakan pada mainframe IBM System/360. OS/360 menjadi sistem operasi yang populer pada akhir 1960-an dan awal 1970-an.
3. UNIX (1969): Sistem operasi yang dikembangkan oleh Ken Thompson dan Dennis Ritchie di Bell Labs. UNIX menjadi sistem operasi yang populer pada akhir 1970-an dan awal 1980-an, terutama pada komputer mini dan workstation.
4. MS-DOS (1981): Sistem operasi yang dikembangkan oleh Microsoft untuk digunakan pada komputer IBM PC. MS-DOS menjadi sistem operasi yang populer pada tahun 1980-an dan awal 1990-an.
5. Microsoft Windows (1985): Sistem operasi yang dikembangkan oleh Microsoft sebagai pengembangan dari MS-DOS. Windows menjadi sistem operasi yang paling populer di dunia pada tahun 1990-an dan masih dominan hingga saat ini.
6. Mac OS (1984): Sistem operasi yang dikembangkan oleh Apple untuk digunakan pada komputer Macintosh. Mac OS mengalami beberapa iterasi dan pengembangan selama bertahun-tahun dan kemudian digantikan oleh macOS pada tahun 2016.
7. Linux (1991): Sistem operasi yang dikembangkan oleh Linus Torvalds. Linux adalah sistem operasi open-source yang populer di kalangan pengembang dan sistem operasi server.
8. Android (2008): Sistem operasi yang dikembangkan oleh Google untuk digunakan pada perangkat mobile. Android menjadi sistem operasi mobile yang paling populer di dunia.
9. iOS (2007): Sistem operasi yang dikembangkan oleh Apple untuk digunakan pada perangkat mobile iPhone dan iPad.
10. Windows 10 (2015): Versi terbaru dari sistem operasi Windows yang dirilis pada tahun 2015. Windows 10 adalah sistem operasi yang paling populer di dunia pada saat ini.

B. Ubuntu dan Debian
Ubuntu dan Debian adalah dua sistem operasi Linux yang populer dan sering digunakan oleh pengguna di seluruh dunia. Meskipun keduanya berasal dari kode sumber yang sama dan memiliki banyak kesamaan, ada beberapa perbedaan antara keduanya.
Debian adalah sistem operasi Linux yang pertama kali dirilis pada tahun 1993 dan dikembangkan oleh komunitas besar pengembang dan kontributor. Debian mengikuti prinsip "free software" dan menyediakan ribuan paket perangkat lunak gratis dan open source untuk digunakan oleh pengguna. Debian terkenal karena kestabilan dan keamanannya yang tinggi serta dukungan untuk banyak arsitektur komputer.
Ubuntu adalah turunan Debian dan dikembangkan oleh Canonical Ltd. Ubuntu pertama kali dirilis pada tahun 2004 dan dirancang untuk menjadi sistem operasi yang mudah digunakan dan diinstal. Ubuntu menggunakan perangkat lunak bebas dan sumber terbuka seperti Debian, tetapi juga menyediakan dukungan dan pembaruan paket perangkat lunak yang lebih terpusat dan terorganisir dengan baik. Ubuntu juga menawarkan fitur seperti tampilan desktop yang modern dan mudah digunakan serta dukungan untuk banyak perangkat keras yang berbeda.
Perbedaan utama antara Debian dan Ubuntu adalah dalam hal filosofi dan pengembangan. Debian lebih berfokus pada prinsip "free software" dan pengembangan yang terbuka dan kolaboratif oleh komunitas besar pengembang, sedangkan Ubuntu lebih berfokus pada kenyamanan pengguna dan dukungan yang terpusat dari perusahaan Canonical. Namun, karena Ubuntu didasarkan pada Debian, keduanya memiliki banyak kesamaan dalam hal manajemen paket dan struktur sistem file. Kedua sistem operasi ini dapat digunakan untuk berbagai keperluan, dari server web dan database hingga desktop pengguna akhir dan sistem komputasi ilmiah.

C. Perintah "SU" dan "SUDO" 
Perintah su dan sudo adalah perintah yang digunakan di sistem operasi Unix/Linux untuk mengizinkan pengguna untuk menjalankan perintah atau skrip sebagai pengguna lain dengan hak istimewa.
su (substitute user) adalah perintah yang memungkinkan pengguna untuk beralih ke akun pengguna lain, biasanya akun root (superuser) atau akun pengguna lain yang memiliki hak istimewa. Setelah pengguna memasukkan perintah su, ia diminta untuk memasukkan kata sandi untuk akun pengguna yang dituju. Jika kata sandi benar, pengguna dapat menjalankan perintah sebagai pengguna yang dituju. Misalnya, jika pengguna ingin menjalankan perintah yang membutuhkan hak akses root, ia dapat menggunakan perintah su - untuk beralih ke akun root dan menjalankan perintah sebagai root.
sudo (superuser do) adalah perintah yang memungkinkan pengguna untuk menjalankan perintah sebagai superuser atau pengguna lain dengan hak istimewa tanpa harus beralih ke akun pengguna lain. Untuk menggunakan perintah sudo, pengguna hanya perlu menambahkan kata "sudo" sebelum perintah yang ingin dijalankan. Setelah itu, pengguna diminta memasukkan kata sandi untuk akun pengguna saat ini. Jika kata sandi benar dan pengguna memiliki hak akses yang diperlukan, perintah akan dijalankan dengan hak istimewa yang diperlukan.
Perbedaan utama antara perintah su dan sudo adalah cara mereka memberikan hak istimewa. Perintah su memberikan hak istimewa secara permanen, sedangkan perintah sudo memberikan hak istimewa hanya untuk satu perintah atau skrip tertentu. Ini membuat perintah sudo lebih aman karena pengguna harus secara spesifik memasukkan kata sandi untuk setiap perintah atau skrip yang membutuhkan hak istimewa.
D. Package Maintenance di Linux
Package maintenance di Linux adalah proses mengelola paket perangkat lunak di sebuah sistem operasi Linux. Paket perangkat lunak adalah sekumpulan file dan informasi yang terkait dengan program yang memungkinkan pengguna untuk menginstal, menghapus, dan mengelola program di sistem operasi Linux. Dalam package maintenance di Linux, pengguna dapat melakukan beberapa tindakan seperti:
1. Memperbarui paket: Pengguna dapat memperbarui paket perangkat lunak yang sudah terinstal di sistem operasi Linux untuk mendapatkan versi terbaru dari perangkat lunak tersebut. Hal ini dapat dilakukan dengan menggunakan perintah seperti apt-get atau yum.
2. Menginstal paket baru: Pengguna dapat menginstal paket perangkat lunak baru di sistem operasi Linux. Hal ini dapat dilakukan dengan menggunakan perintah seperti apt-get atau yum.
3. Menghapus paket: Pengguna dapat menghapus paket perangkat lunak yang sudah terinstal di sistem operasi Linux untuk membersihkan ruang penyimpanan dan menghilangkan perangkat lunak yang tidak lagi dibutuhkan. Hal ini dapat dilakukan dengan menggunakan perintah seperti apt-get atau yum.
4. Mencari paket: Pengguna dapat mencari paket perangkat lunak yang tersedia untuk diinstal di sistem operasi Linux. Hal ini dapat dilakukan dengan menggunakan perintah seperti apt-cache search atau yum search.
5. Menjaga sistem operasi Linux tetap aman: Pengguna dapat memastikan bahwa sistem operasi Linux selalu aman dengan memperbarui paket perangkat lunak yang berisi patch keamanan terbaru.
Pada umumnya, distribusi Linux seperti Debian dan Ubuntu menggunakan perangkat manajemen paket APT (Advanced Packaging Tool), sementara distribusi seperti Red Hat dan Fedora menggunakan perangkat manajemen paket RPM (Red Hat Package Manager). Ada juga perangkat manajemen paket yang dapat diunduh dan diinstal secara manual seperti Snap, Flatpak, dan AppImage yang digunakan untuk mengelola paket perangkat lunak di sistem operasi Linux.

E. Mengatur repository di Ubuntu
Untuk mengatur repository di Ubuntu, ikuti langkah-langkah berikut:
1. Buka Terminal dengan menekan tombol Ctrl + Alt + T secara bersamaan.
2. Ketikkan perintah berikut untuk membuka file sources.list:
    "sudo nano /etc/apt/sources.list"
3. Kita akan melihat daftar repository di file tersebut. Kita dapat menambahkan atau menghapus repository sesuai dengan kebutuhan. Untuk menambahkan repository, kita dapat menambahkan baris baru ke file tersebut dengan mengetikkan URL repository pada baris tersebut. Misalnya, jika ingin menambahkan repository Universe, tambahkan baris berikut ke file sources.list:
    "deb http://archive.ubuntu.com/ubuntu/ focal universe"
    Di sini, "focal" adalah kode nama versi Ubuntu yang kita gunakan. Kita dapat menggantinya dengan kode nama versi Ubuntu yang digunakan, seperti "bionic", "xenial", dll.
4. Setelah menambahkan atau menghapus repository, simpan perubahan dengan menekan tombol Ctrl + X, lalu ketikkan "Y" untuk menyimpan perubahan, kemudian tekan Enter.
5. Agar perubahan yang baru diaplikasikan, jalankan perintah berikut di Terminal:
    "sudo apt update"
Perintah ini akan mengupdate daftar paket dan repository pada sistem. Sekarang, repository di Ubuntu sudah diatur dan siap digunakan. Kita dapat menginstall atau mengupdate paket perangkat lunak melalui perintah apt atau melalui manajer paket grafis seperti Ubuntu Software Center.

F. Versi di Repo
"Versi di repo" dapat merujuk pada versi suatu perangkat lunak yang tersedia di repositori atau sumber paket yang diinstal pada sistem operasi Linux. Repositori adalah tempat penyimpanan paket perangkat lunak untuk sistem operasi Linux dan memungkinkan pengguna untuk menginstal dan mengelola paket perangkat lunak yang berbeda.
Dalam konteks ini, "versi di repo" mengacu pada nomor versi perangkat lunak yang tersedia di repositori Linux. Nomor versi ini biasanya terdiri dari tiga atau empat bagian yang terpisah oleh titik. Bagian-bagian ini umumnya merujuk pada versi utama, versi minor, dan versi revisi perangkat lunak, yang digunakan untuk menentukan tingkat pembaruan dan perbaikan yang terkait dengan suatu perangkat lunak.
Misalnya, jika versi perangkat lunak adalah 2.1.0, itu artinya versi utama adalah 2, versi minor adalah 1, dan versi revisi adalah 0. Ketika pengguna memperbarui paket perangkat lunak mereka, mereka akan memperbarui ke versi yang tersedia di repositori Linux, yaitu "versi di repo" terbaru yang tersedia pada saat itu.

G. APT di Linux
APT (Advanced Package Tool) adalah manajer paket yang umumnya digunakan pada sistem operasi Linux berbasis Debian, seperti Ubuntu, Debian, dan Linux Mint. APT memungkinkan pengguna untuk menginstal, menghapus, dan mengelola paket perangkat lunak pada sistem operasi Linux dengan mudah. Berikut adalah beberapa perintah APT yang sering digunakan pada sistem operasi Linux:
1. sudo apt update: Memperbarui daftar paket pada sistem operasi Linux.
2. sudo apt upgrade: Memperbarui semua paket yang telah terinstal pada sistem operasi Linux ke versi terbaru.
3. sudo apt install <nama_paket>: Menginstal paket perangkat lunak pada sistem operasi Linux.
4. sudo apt remove <nama_paket>: Menghapus paket perangkat lunak dari sistem operasi Linux.
5. sudo apt search <kata_kunci>: Mencari paket perangkat lunak yang tersedia pada repositori Linux dengan menggunakan kata kunci tertentu.
6. sudo apt list: Menampilkan daftar paket perangkat lunak yang telah terinstal pada sistem operasi Linux.
7. sudo apt autoremove: Menghapus paket yang tidak lagi dibutuhkan oleh sistem operasi Linux.

APT juga memiliki banyak opsi yang dapat digunakan untuk mengelola paket perangkat lunak pada sistem operasi Linux dengan lebih baik, seperti pengaturan preferensi paket dan sinkronisasi dengan repositori jarak jauh. APT adalah alat yang kuat dan efektif untuk mengelola paket perangkat lunak pada sistem operasi Linux dan sangat direkomendasikan bagi pengguna Linux yang ingin memperbarui atau menginstal perangkat lunak baru pada sistem operasi mereka.

H. Instalasi Midnight Commander (MC)
MC atau Midnight Commander adalah file manager teks yang umum digunakan pada sistem operasi Linux. Berikut adalah cara instalasi paket MC di Linux menggunakan manajer paket apt:
1. Buka Terminal dengan menekan tombol Ctrl + Alt + T secara bersamaan.
2. Jalankan perintah berikut untuk memperbarui daftar paket pada sistem:
"sudo apt update"
3. Setelah selesai memperbarui daftar paket, jalankan perintah berikut untuk menginstal MC:
"sudo apt install mc"
4. Setelah proses instalasi selesai, Anda dapat menjalankan MC dengan mengetikkan perintah berikut di Terminal:
"mc"

I. Instalasi Net-Tools
Net-tools adalah kumpulan perangkat lunak utilitas jaringan yang berguna untuk menampilkan informasi jaringan dan memodifikasi konfigurasi jaringan pada sistem operasi Linux. Berikut adalah cara instalasi paket Net-tools di Linux menggunakan manajer paket apt:
1. Buka Terminal dengan menekan tombol Ctrl + Alt + T secara bersamaan.
2. Jalankan perintah berikut untuk memperbarui daftar paket pada sistem:
"sudo apt update"
3. Setelah selesai memperbarui daftar paket, jalankan perintah berikut untuk menginstal Net-tools:
"sudo apt install net-tools"
4. Setelah proses instalasi selesai, Anda dapat menjalankan perintah seperti ifconfig, netstat, route, dan arp untuk menampilkan informasi jaringan dan memodifikasi konfigurasi jaringan pada sistem operasi Linux.

J. Instalasi Htop
Htop adalah utilitas teks untuk memonitor sistem operasi Linux yang lebih canggih dan interaktif daripada utilitas bawaan top. Berikut adalah cara instalasi htop di Linux menggunakan manajer paket apt:
1. Buka Terminal dengan menekan tombol Ctrl + Alt + T secara bersamaan.
2. Jalankan perintah berikut untuk memperbarui daftar paket pada sistem:
"sudo apt update"
3. Setelah selesai memperbarui daftar paket, jalankan perintah berikut untuk menginstal htop:
"sudo apt install htop"
4. Setelah proses instalasi selesai, Anda dapat menjalankan htop dengan mengetikkan perintah berikut di Terminal:
"htop"
Htop akan terbuka dan menampilkan informasi tentang penggunaan CPU, memori, dan proses pada sistem operasi Linux.
