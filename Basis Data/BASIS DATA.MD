# PELATIHAN BASIS DATA (MYSQL)
[<-- Back](../README.MD)

# Shortcut
1. [Persiapan](#file-yang-perlu-dipersiapkan)
2. [Pemasangan](#pemasangan)
2. [Langkah Awal](#langkah-awal)
3. [Permasalahan](#permasalahan-yang-sering-terjadi)

## File Yang Perlu Dipersiapkan
- [SQLyog Community Edition](https://github.com/webyog/sqlyog-community/wiki/Downloads) Gratis Atau [SQLyog Ultimate Edition](https://webyog.com/product/sqlyog/) Berbayar By Webyog Inc.
![SQLyog Community Edition]()
![SQLyog Ultimate Edition]()
- [XAMPP](https://www.apachefriends.org/download.html) By Apache Friends.

## Pemasangan
**Pemasangan SQLyog**
1. Unduh SQLyog:
    Kunjungi situs resmi SQLyog di https://github.com/webyog/sqlyog-community/wiki/Downloads dan unduh versi terbaru dari SQLyog Community Edition sesuai dengan sistem operasi Anda (Windows).

2. Mulai Instalasi:
    Setelah proses unduhan selesai, buka file instalasi yang telah diunduh (biasanya berbentuk .exe).

3. Pilih Bahasa:
    Saat instalasi dimulai, Anda akan diminta untuk memilih bahasa. Pilih bahasa yang diinginkan dan klik "OK" atau "Next".

4. Persyaratan Sistem:
    Pastikan komputer Anda memenuhi persyaratan sistem yang dibutuhkan oleh SQLyog. Biasanya, persyaratan ini termasuk sistem operasi yang didukung dan ruang penyimpanan yang cukup.

5. Pilih Komponen:
    Pada layar "Select Components", biarkan pilihan default yang sudah dipilih dan klik "Next" atau "Install".

6. Pilih Lokasi Instalasi:
    Pada layar "Select Installation Folder", Anda dapat memilih lokasi di mana SQLyog akan diinstal. Biarkan lokasi default atau pilih lokasi yang Anda inginkan, kemudian klik "Next" atau "Install".

7. Mulai Instalasi:
    Setelah Anda memilih lokasi instalasi, klik "Install" atau "Next" untuk memulai proses instalasi.

8. Selesai Instalasi:
    Setelah proses instalasi selesai, Anda akan melihat pesan yang mengonfirmasi bahwa instalasi telah berhasil diselesaikan. Klik "Finish" untuk menutup instalator.

**Pemasangan XAMPP**
1. Unduh XAMPP:
    Kunjungi situs resmi XAMPP di https://www.apachefriends.org/index.html dan unduh versi terbaru XAMPP sesuai dengan sistem operasi Anda (Windows, macOS, atau Linux).

2. Mulai Instalasi:
    Setelah proses unduhan selesai, buka file instalasi yang telah diunduh (biasanya berbentuk .exe untuk Windows, .dmg untuk macOS, dan .run atau .tar.gz untuk Linux).

3. Pilih Bahasa (Jika Ada):
    Saat instalasi dimulai, Anda mungkin diminta untuk memilih bahasa. Pilih bahasa yang diinginkan dan klik "OK" atau "Next".

4. Persyaratan Sistem:
    Pastikan komputer Anda memenuhi persyaratan sistem yang dibutuhkan oleh XAMPP. Biasanya, persyaratan ini termasuk sistem operasi yang didukung dan ruang penyimpanan yang cukup.

5. Pilih Komponen (Opsional):
    Pada layar "Select Components", Anda dapat memilih komponen yang ingin diinstal. Biarkan pilihan default yang sudah dipilih atau sesuaikan sesuai kebutuhan Anda, kemudian klik "Next" atau "Install".

6. Pilih Lokasi Instalasi:
    Pada layar "Select Installation Folder", Anda dapat memilih lokasi di mana XAMPP akan diinstal. Biarkan lokasi default atau pilih lokasi yang Anda inginkan, kemudian klik "Next" atau "Install".

7. Mulai Instalasi:
    Setelah Anda memilih lokasi instalasi, klik "Install" atau "Next" untuk memulai proses instalasi.

8. Selesai Instalasi:
    Setelah proses instalasi selesai, Anda akan melihat pesan yang mengonfirmasi bahwa instalasi telah berhasil diselesaikan. Klik "Finish" untuk menutup instalator.

## Langkah Awal
1.  Mulai XAMPP:
    - Setelah instalasi selesai, Anda dapat menjalankan XAMPP dari desktop atau menu Start. Cari ikon aplikasi XAMPP dan klik dua kali untuk membukanya.

2. Mulai Layanan:
    - Setelah XAMPP terbuka, Anda perlu memulai layanan MySQL. Klik tombol "Start" di samping layanan tersebut untuk memulai layanan tersebut.

3. Menjalankan SQLyog:
    - Setelah instalasi selesai, Anda dapat menjalankan SQLyog dari desktop atau menu Start. Cari ikon aplikasi SQLyog dan klik dua kali untuk membukanya.

4. Konfigurasi Awal:
    - Setelah SQLyog terbuka, Anda akan melihat jendela utama. Klik pada opsi "New Connection" di pojok kiri atas atau pilih "File" > "New Connection" dari menu.

        - Di jendela "New Connection", Anda akan diminta untuk mengisi detail koneksi.

                - Connection Name: Beri nama koneksi Anda. Ini bisa apa pun yang mudah diingat, seperti "Localhost" atau nama proyek Anda.

                - Hostname/IP: Masukkan alamat IP atau nama host dari server database. Jika server database berjalan di komputer lokal, Anda dapat menggunakan "localhost".

                - Username: Masukkan nama pengguna MySQL Anda. Isi dengan "root".

                - Password: Masukkan kata sandi untuk pengguna MySQL yang Anda masukkan sebelumnya. dikarenakan kita menggunakan xampp sebagai mysql nya, maka di kosongkan saja.

                - Port: Port default untuk MySQL adalah 3306. Biarkan seperti itu kecuali Anda mengubahnya selama instalasi MySQL.

        - Setelah Anda mengisi detail koneksi, klik tombol "Test Connection" untuk memastikan bahwa SQLyog dapat terhubung ke server database.

        - Jika tes koneksi berhasil, klik "Save" untuk menyimpan detail koneksi Anda.

        - Setelah Anda menyimpan koneksi, Anda akan kembali ke jendela utama SQLyog. Sekarang, pilih koneksi yang baru saja Anda buat dari daftar koneksi di sebelah kiri dan klik "Open" untuk terhubung ke server database.

        - Setelah terhubung, Anda akan melihat berbagai tab dan fungsi di bagian atas jendela SQLyog. Anda sekarang dapat menjalankan kueri SQL, mengelola basis data, dan melakukan tugas-tugas lainnya sesuai kebutuhan Anda.

## Permasalahan Yang Sering Terjadi
- MySQL dari xampp tiba tiba terhenti atau tidak bisa di start, cara penyelesaian nya:
    ![image 1](Screenshot%202024-05-05%20173138.png)
    ![image 2](Screenshot%202024-05-05%20173157.png)
    ![image 3](Screenshot%202024-05-05%20173739.png)
    ![image 4](Screenshot%202024-05-05%20173205.png)
    ![image 5](Screenshot%202024-05-05%20173211.png)
    ![image 6](Screenshot%202024-05-05%20173218.png)
    ![image 7](Screenshot%202024-05-05%20173229.png)
    ![image 8](Screenshot%202024-05-05%20173249.png)