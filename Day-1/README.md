# 🌐 Web Server - Administrasi Sistem Jaringan (ASJ)

Materi ini disusun untuk mendukung pembelajaran **Mata Pelajaran Administrasi Sistem Jaringan (ASJ)** SMK kelas 11. Fokus utama adalah pada instalasi, konfigurasi, dan manajemen layanan web server berbasis Linux.

---

## 📘 Pengertian Web Server

Web server adalah sebuah perangkat lunak (software) atau kombinasi perangkat keras (hardware) dan perangkat lunak yang berfungsi untuk menerima, memproses, dan merespons permintaan dari client (biasanya browser) melalui protokol HTTP atau HTTPS.

Web server menyajikan konten website seperti halaman HTML, gambar, video, dan file lainnya ke pengguna akhir. Ketika pengguna mengetikkan alamat website di browser, browser akan mengirim permintaan ke web server, dan web server akan mengirimkan kembali data yang diminta agar ditampilkan di browser.

---

![1676207646033](https://github.com/user-attachments/assets/83f9ca52-2aba-4ff1-92f4-ecfe7f49676e)

## Contoh Web Server Populer:

- Apache HTTP Server
- Nginx
- Microsoft IIS
- LiteSpeed

---
---

## 🌐 Untuk Apa Web Server?

Web server digunakan untuk menyimpan, mengelola, dan menyajikan konten website kepada pengguna melalui internet atau jaringan lokal.

---
---

## 📌 Fungsi Utama Web Server:

1. Menyajikan Halaman Website
   Web server merespon permintaan dari browser (client) dan mengirimkan file HTML, CSS, gambar, video, dan lainnya agar bisa ditampilkan di layar pengguna.
2. Menjalankan Script Sisi Server
   Web server bisa bekerja sama dengan bahasa pemrograman server-side seperti PHP, Python, atau Node.js untuk menghasilkan konten yang dinamis.
3. Mengelola Akses Pengguna
   Web server bisa mengatur siapa yang boleh mengakses halaman tertentu, seperti halaman admin atau konten yang dilindungi password.
4. Sebagai Reverse Proxy / Load Balancer
   Dalam sistem besar, web server digunakan untuk mendistribusikan trafik ke beberapa server aplikasi di belakangnya (misalnya menggunakan Nginx sebagai reverse proxy).
5. Mengelola Virtual Host
   Bisa menampung lebih dari satu website di satu server fisik menggunakan virtual host (contoh:
   `website1.com`, `website2.com` di server yang sama).
---

# 🎯 Contoh Penggunaan Web Server

Web server digunakan dalam berbagai kebutuhan di dunia nyata, mulai dari menampilkan halaman website hingga menjalankan layanan API. Berikut ini adalah beberapa contoh penggunaan web server dalam konteks praktis:

| 💼 Kegiatan                                      | 🌐 Web Server yang Terlibat            |
|--------------------------------------------------|----------------------------------------|
| Membuka website sekolah di browser               | Apache atau Nginx                      |
| Menjalankan sistem informasi berbasis web        | Apache + PHP                           |
| Hosting blog pribadi dengan WordPress            | Apache/Nginx + PHP + MySQL             |
| Akses API dari aplikasi mobile/web               | Nginx sebagai API gateway              |

> ✅ Web server memainkan peran penting dalam proses komunikasi antara client (browser atau aplikasi) dengan server yang menyimpan data dan aplikasi.

---

## 🛠️ Komponen Web Server

| Komponen        | Fungsi                                      |
|----------------|----------------------------------------------|
| Apache/Nginx    | Menyediakan layanan HTTP/HTTPS              |
| PHP             | Menjalankan skrip sisi server               |
| MySQL/MariaDB   | Menyimpan dan mengelola data website        |
| Webmin (opsional)| Panel administrasi berbasis web            |

---

## 💻 Instalasi Web Server di Linux (Ubuntu Server)

```bash
sudo apt update
```
![asj](https://github.com/user-attachments/assets/3f4e5f8b-11c9-4e7b-8328-036ec2801e1a)

```bash
sudo apt install nginx -y
```
![Screenshot 2025-04-17 233044](https://github.com/user-attachments/assets/d8ef49f7-11c4-456a-b700-5b02d0c90775)

```bash
systemctl status nginx 
```
![Screenshot 2025-04-17 233241](https://github.com/user-attachments/assets/9d51c599-81bf-4d9d-ac2e-582a004d898c)



### 📚 Materi Terkait

- [Pengertian Web Server](./pengertian-web-server.md)
- [Fungsi Web Server](./fungsi-web-server.md)
- [Web Server untuk DevOps](./devops-web-server.md)
- [Langkah Instalasi Web Server](./praktikum-install-apache.md)
