# Kali-Nethunter
Kali Linux NetHunter  Kali Linux NetHunter untuk Nexus dan OnePlus  Proyek Kali Linux NetHunter adalah platform pengujian penetrasi Android Open Source pertama untuk perangkat Nexus, yang dibuat sebagai upaya bersama antara anggota komunitas Kali "BinkyBear" dan Keamanan Ofensif.  NetHunter mendukung injeksi bingkai 802.11 Nirkabel, setup MANA Evil Access Point satu-klik, keyboard HID (serangan seperti Teensy), serta serangan BadUSB MITM - dan dibangun di atas bahu kokoh distribusi Kali Linux dan perangkat.  Apakah Anda memiliki Nexus 5, Nexus 6, Nexus 7, Nexus 9, Nexus 10 atau OnePlus One, kami telah membantu Anda.  Gambar kami yang dapat diunduh secara bebas hadir dengan mudah untuk mengikuti petunjuk pemasangan dan pengaturan untuk membuat Anda siap dan bekerja dalam waktu singkat.

# Features From Kali-Nethunter
````
 •802.11 Wireless Injeksi dan mode AP mendukung dengan beberapa kartu wifi USB yang didukung.
 •Mampu menjalankan serangan Keyboard HID USB, seperti yang dapat dilakukan perangkat Teensy.
 •Mendukung serangan BadUSB MITM.  Sambungkan Nethunter Anda ke PC korban, dan minta traffic Anda menyampaikannya.
 •Berisi perangkat Linux Kali penuh, dengan banyak alat tersedia melalui sistem menu sederhana.
 •Dukungan USB Y-cable di kernel Nethunter - gunakan kabel OTG Anda saat masih mengisi daya perangkat Nexus Anda!
 •Dukungan Radio untuk Perangkat Lunak.  Gunakan Kali Nethunter dengan HackRF Anda untuk menjelajahi ruang radio nirkabel.
````

# HID Keyboard and 'BadUSB'
Sebagai penguji penetrasi atau profesional keamanan yang berpengalaman, sangat penting bagi Anda untuk mempercayai alat yang Anda gunakan.  Salah satu cara untuk mencapai kepercayaan ini adalah dengan memiliki transparansi penuh dan keakraban dengan kode yang Anda jalankan.  Anda bebas untuk membaca, menyelidiki, dan mengubah skrip build kami untuk gambar NetHunter.  Semua kebaikan ini berasal dari rumah Keamanan Ofensif dan pengembang Kali Linux!

# Configuration Management 
Antarmuka konfigurasi Kali NetHunter memungkinkan Anda untuk dengan mudah mengkonfigurasi file konfigurasi yang rumit melalui antarmuka web lokal.  Fitur ini, bersama-sama dengan kernel khusus yang mendukung 802.11 injeksi nirkabel dan layanan koneksi balik VPN yang telah dikonfigurasikan sebelumnya, menjadikan NetHunter alat keamanan jaringan yang hebat atau kotak drop diskrit - dengan Kali Linux di ujung jari Anda di manapun Anda berada!

# How to install Kali-Nethunter in Termux
````
#What Must Be Required 

1.This Data Requires a minimum of 1.16GB of Storage 
2.Download Using Wifi or the Internet 
3.Files Drawn At Home Files Termux Because there the files will be processed

# How to Install Kali-Nethunter
1.pkg update && pkg upgrade
2.pkg install axel proot unzip zip tar wget curl
3.wget https://raw.githubusercontent.com/Mehanic385/Kali-Nethunter/master/Kali-Nethunter
4.chmod +x Kali-Nethunter && ./Kali-Nethunter
````
# Greetings From kali.org
Thank you kali.org because you have made Kali-Nethunter for android
files and data from kali.org

# Usage
Open Termux type one of the following 
````
Command	To
nethunter	        start Kali NetHunter command line interface
nethunter kex passwd	configure the KeX password (only needed before 1st use)
nethunter kex &	        start Kali NetHunter Desktop Experience user sessions
nethunter kex stop	stop Kali NetHunter Desktop Experience
nethunter <command>	run in NetHunter environment
nethunter -r	        start Kali NetHunter cli as root
nethunter -r kex passwd	configure the KeX password for root
nethunter -r kex &	start Kali NetHunter Desktop Experience as root
nethunter -r kex stop	stop Kali NetHunter Desktop Experience root sessions
nethunter -r kex kill	Kill all KeX sessions
nethunter -r <command>	run <command> in NetHunter environment as root
Note: The command nethunter can be abbreviated to nh. Tip: If you run kex in the background (&) without having set a password, bring it back to the foreground first when prompted to enter the password, i.e. via fg <job id> - you can later send it to the background again via Ctrl + z and bg <job id>

To use KeX, start the KeX client, enter your password and click connect Tip: For a better viewing experience, enter a custom resolution under “Advanced Settings” in the KeX Client

````

# sudo <root password>
sudo (/ˈsuːduː/[2] atau /ˈsuːdoʊ/[2][3]) adalah suatu program untuk sistem operasi komputer sejenis Unix yang memungkinkan para pengguna untuk menjalankan program-program hak keamanan pengguna lain, secara default merupakan "superuser".[4] Asalnya merupakan singkatan "superuser do"[5] karena sudo pada versi-versi yang lebih lama didesain untuk menjalankan program-program hanya sebagai superuser. Namun, versi-versi berikutnya menambah dukungan untuk menjalankan perintah-perintah bukan hanya sebagai superuser tetapi juga sebagai pengguna (restricted) lain, sehingga juga umumnya dikembangkan sebagai "substitute user do".[6][7] Meskipun kasus terakhir itu mencerminkan fungsionalistas saat ini secara lebih akurat, sudo masih sering disebut "superuser do" karena sering digunakan untuk tugas-tugas administratif.
````
Usage Command "sudo":

Pengguna "Root" adalah pengguna default dengan semua hak. Untuk mengubah password root Anda perlu login sebagai root pada command prompt dan jalankan perintah "passwd". Anda juga bisa menjalankan perintah "su". Perintah su (short for sub user) memungkinkan untuk mengubah pemilik sesi login (yaitu pengguna yang awalnya membuat sesi itu dengan masuk ke sistem) tanpa pemilik harus terlebih dahulu keluar dari sesi itu.
Berikut adalah demonstrasi bagaimana password Root bisa diubah.
Prasyarat
1. Sistem operasi Linux (Ubuntu, CentOS, Debian dll) - Dalam hal ini kita bekerja pada CentOS 7
2. Izin root
Mengubah Password Root
1. Buka Terminal sistem operasi Anda. Masuk sebagai "root" dengan mengetikkan perintah "su".
"Su" biasanya cara termudah dan paling mudah untuk mengubah kepemilikan sesi login menjadi root atau pengguna lainnya.
Permintaan kata sandi akan ditampilkan. Ketikkan kata sandi Anda saat ini untuk login sebagai root.
2. Setelah login sebagai root jalankan perintah "passwd". Baris perintah akan meminta password baru. Masukkan kata sandi baru di command prompt (Catatan: Kata sandi tidak akan ditampilkan di layar). Setelah mengetikkan kata sandi Anda akan diminta untuk mengetik ulang kata sandi dan kata sandi Anda akan berubah.

Cara mengganti password user di Kali-Nethunter 
Untuk mengganti password user pada sistem operasi
Berbasic GNU/Linux Pertama buka console terminal/termux 
Dengan cara menekan tombol CTRL+ALT+T Pada Keyboard <Ini Buat Di Pc/Laptop>
Lalu ketikan perintah berikut. 

kali@localhost:~$ sudo passwd kali

kali adalah username yg sy gunakan
Di Kali-Nethunter sy silahkan ganti
Dengan nama user yg kamu gunakan, 
Kemudian di minta untuk mengetikan paswwd root

kali@localhost:~$ sudo passwd kali
kali : #Password Lama kamu masukan

Setelah itu akan diminta untuk mengetik password baru
kali@localhost:~$ sudo passwd kali
kali : #Password Lama
Enter New Password: #Masukan Password baru
Retype New password: #Verify Password kamu tadi
passwd: password updated
successfully

Tada Udah selesai
````

# Tips From kali.org:
````
1.Jalankan "apt update && apt full-upgrade" hal pertama setelah instalasi.  Jika Anda memiliki banyak ruang penyimpanan yang tersedia, Anda mungkin ingin menjalankan "apt install kali-linux-default" juga.
2.Firefox tidak akan bekerja pada perangkat yang tidak di-unroot.  Ganti saja dengan Chromium melalui: "apt remove firefox-esr apt install chromium" Selanjutnya: ~ Temukan item "Chromium Web Browser" di menu aplikasi ~ klik kanan dan pilih "Edit Aplikasi" ~ Ubah "Command" menjadi "/ usr / bin  / chromium --no-sandbox% U"
3.Semua alat pengujian penetrasi harus berfungsi tetapi beberapa mungkin memiliki batasan, mis.  metasploit berfungsi tetapi tidak memiliki dukungan basis data.  Jika Anda mepnemukan alat apa pun yang tidak berfungsi, silakan kirim di forum kami.
4.Beberapa utilitas seperti "atas" tidak akan berjalan di ponsel yang tidak di-root.
5.Pengguna non-root masih memiliki akses root di chroot.  Itu hal yang wajar.  Sadarilah itu.
6.Ponsel Galaxy dapat mencegah pengguna non-root menggunakan sudo.  Cukup gunakan "su -c" sebagai gantinya.
7.Lakukan pencadangan rutin rootfs Anda dengan menghentikan semua sesi yang tidak diikuti dan ketikkan yang berikut dalam sesi termux: "tar -cJf kali-arm64.tar.xz kali-arm64 && mv kali-arm64.tar.xz storage / download "yang akan menempatkan cadangan  di folder unduhan Android Anda.  Catatan: pada perangkat yang lebih lama, ubah "arm64" menjadi "armhf"
8.Silakan bergabung dengan kami di forum kami untuk bertukar tips dan ide dan menjadi bagian dari komunitas yang berusaha menjadikan NetHunter lebih baik.
Link Forum Nethunter: https://forums.kali.org/forumdisplay.php?14-NetHunter-Forums

````
# Tips Solution Eror Nethunter-rootless
````
dpkg --configure -a
apt install -f
apt --fix-broken install
apt install clean
apt autoremove
apt remove libc6-dev libgcc-s1 
`````
