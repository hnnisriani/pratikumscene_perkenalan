Praktikum Scene Perkenalan Diri

Identitas Mahasiswa

Nama: Henni Suriani Sihombing

NIM: 2309020336

Program Studi: Teknologi Informasi

Deskripsi Project

Project ini merupakan scene perkenalan diri sederhana menggunakan A-Frame. Scene menampilkan langit, lantai, kubus, bola, silinder, teks identitas, dan cincin yang berputar secara otomatis.

Teknologi yang Digunakan

HTML

A-Frame

WebXR

Jawaban Refleksi

1. Mengapa posisi objek yang terlihat pertama kali oleh pengguna memakai nilai Z negatif?

Pada project ini, kamera menghadap ke arah sumbu Z negatif sehingga objek diletakkan pada koordinat Z negatif agar terlihat di depan kamera. Posisi objek harus disesuaikan dengan arah pandang kamera supaya dapat terlihat.

2. Mengapa WebXR hanya aktif pada HTTPS atau localhost?

WebXR umumnya membutuhkan secure context untuk mengakses fitur XR yang didukung browser dan perangkat. Oleh karena itu, HTTPS digunakan untuk website publik, sedangkan localhost dapat digunakan untuk pengembangan dan pengujian.

3. Jelaskan perbedaan peran WebXR Device API, three.js, dan A-Frame.

WebXR Device API menyediakan antarmuka untuk mengakses kemampuan VR dan AR yang didukung perangkat. Three.js digunakan untuk membuat grafis 3D, sedangkan A-Frame memudahkan pembuatan scene 3D melalui elemen HTML seperti a-scene, a-box, dan a-text.


## Fitur Scene
- Menampilkan tiga objek primitif berbeda.
- Menggunakan lantai dan langit.
- Menampilkan nama dan NIM mahasiswa.
- Memiliki objek cincin dengan animasi rotasi.