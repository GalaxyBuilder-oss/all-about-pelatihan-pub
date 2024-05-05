# PELATIHAN LOGIKA DAN ALGORITMA PEMROGAMAN (BAHASA C)
[<-- Back](../README.MD)
## Shortcut
- [Persiapan](#file-yang-diperlukan)
- [Pemasangan](#pemasangan)
## File Yang Diperlukan
- [MinGW](https://winlibs.com/)
- [Visual Studio Code](https://code.visualstudio.com/download) dan extensinya:
    - [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools) by Microsoft
    - [C/C++ Runner by Divdik PUB](https://marketplace.visualstudio.com/items?itemName=DivdikPUB.cpp-runner) By Divdik PUB 
## Pemasangan
**Visual Studio Code**
1. Unduh Instalasi:
    - Kunjungi situs web resmi Visual Studio Code di https://code.visualstudio.com/ dan unduh versi terbaru sesuai dengan sistem operasi yang Anda gunakan (Windows, macOS, atau Linux).
![Pilih Sesuai Sistem Operasi Di Laptop](Screenshot%202024-05-05%20162504.png)
    - Instalasi di Windows:
        - Buka file instalasi yang telah diunduh (.exe).
        - Ikuti langkah-langkah instalasi standar dengan mengklik "Next" atau "Selanjutnya" sampai proses instalasi selesai.
        - Pastikan untuk memberi centang pada opsi "Add to PATH" agar dapat menjalankan VSCode dari baris perintah.
        ![Tampilan Windows](Screenshot%202024-05-05%20164036.png)
    - Instalasi di macOS:
        - Buka file instalasi yang telah diunduh (.dmg).
        - Seret ikon Visual Studio Code ke folder "Applications" untuk menginstal aplikasi.
        - Setelah selesai, Anda bisa membuka VSCode dari folder "Applications" atau dengan mencarinya di Spotlight.
        ![Tampilan MacOs](#)
    - Instalasi di Linux (Debian/Ubuntu):
        - Unduh paket .deb dari situs web VSCode.
        - Buka terminal dan navigasi ke folder tempat Anda menyimpan file .deb.
        - Jalankan perintah 
            ```shell
            sudo dpkg -i <nama_file>.deb 
            ```
          Untuk Memulai Penginstalan.
        - Jika muncul pesan tentang dependensi yang tidak terpenuhi, jalankan sudo apt-get install -f untuk memperbaikinya.
        ![Tampilan Linux](#)
2. Menjalankan Visual Studio Code:
    - Setelah instalasi selesai, buka VSCode dari menu aplikasi atau dari ikon yang muncul di desktop.
    - Saat pertama kali dijalankan, Anda akan disuguhi dengan tampilan sambutan dan dapat mengkustomisasi pengaturan sesuai kebutuhan.


**MinGW Untuk Windows**
1. Unduh Instalasi:
    - Kunjungi situs resmi MinGW di https://osdn.net/projects/mingw/ dan unduh versi terbaru(untuk saat ini per 05 Mei 2024 versi terbaru dari MinGW adalah 13.2.0).
    ![Download MinGW](Screenshot%202024-05-05%20161327.png)
2. Ekstrak File:
    - Setelah proses unduhan selesai, ekstrak file zip yang telah diunduh ke lokasi yang mudah diakses, seperti C:\MinGW atau direktori lain yang Anda pilih.
    ![Lokasi MinGW](Screenshot%202024-05-05%20164816.png)
3. Tambahkan ke PATH:
    - Klik kanan pada "This PC" atau "My Computer", lalu pilih "Properties".
    ![Properties](Screenshot%20(4).png)
    - Di jendela System Properties, pilih "Advanced system settings" di panel kiri.
    ![Advance system settings](Screenshot%20(5).png)
    - Di jendela System Properties yang muncul, klik tombol "Environment Variables" di bagian bawah.
    ![Environment variables](Screenshot%20(6).png)
    - Di bagian "System variables" Atau "User variables", cari variabel "Path", lalu klik "Edit".
    ![Path](Screenshot%20(7).png)
    - Tambahkan jalur direktori tempat Anda mengekstrak MinGW ke dalam daftar. Misalnya, C:\MinGW\bin.
    - Klik "OK" untuk menyimpan perubahan.
    ![Jalur Direktori MinGW](Screenshot%20(8).png)
4. Verifikasi Instalasi:
    - Buka Command Prompt (cmd) dengan menekan tombol "Windows + R", ketik "cmd", lalu tekan Enter.
    - Di jendela Command Prompt, ketik:
    ```shell
    gcc --version
    ```
    dan tekan Enter. Jika MinGW telah terinstal dengan benar, Anda akan melihat versi dari GNU Compiler Collection (GCC) yang terpasang.