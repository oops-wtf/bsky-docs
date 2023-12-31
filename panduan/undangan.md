---
title: Kode Undangan
description: Ada beberapa alasan mengapa Bluesky menerapkan sistem undangan tertutup.
layout: home
nav_order: 4
permalink: /undangan
last_modified_date: 2024-01-02 15:31
---

# Kode Undangan
Sejak peluncuran pertama hingga saat ini (20 Desembeer 2023), Bluesky masih berada dalam *private-closed beta*, sehingga tidak tersedia secara terbuka untuk semua orang.

Terdapat beberapa alasan mengapa Bluesky menerapkan sistem undangan tertutup, sebagai berikut:

* ### Membatasi agar tidak terkonsentrasi pada satu PDS
Harapannya adalah agar pengguna tidak terpusat hanya di server bluesky.social saja, sementara PDS lain disiapkan untuk bergabung ke dalam jaringan. Bagi Bluesky (team) memiliki lebih dari 1/3 pengguna di satu server perusahaan memiliki resiko besar dalam proyek ini.

    Kenyataan bahwa sudah ada beberapa *instance* selain [bsky.social](https://bsky.app) yang bisa didaftar tanpa perlu kode undangan. Sayangnya sebagian besar server ini masih dalam jaringan ujicoba terbatas ([*sandbox*]({% link atproto/sandbox.md %})) dan belum dapat terhubung secara penuh ke jaringan utama [ATProto]({% link atproto/0-atproto.md %}).

    ![Daftar PDS Bluesky dalam sandbox per 1 Agustus 2023](/assets/gambar/panduan/atproto/daftar-pds.jpg){:width="100%"}
    <small>*Daftar PDS Bluesky dalam sandbox per 1 Agustus 2023*</small>

    Ketika Bluesky terdesentralisasi dan terbuka untuk umum, orang-orang bisa membuat servernya sendiri. Penggunaan kode undangan seperti Bluesky sekarang berfungsi sebagai pengendali bagi operator (admin) PDS untuk membatasi servernya untuk pengguna baru. Meskipun tidak bersifat publik, operator (admin) PDS dapat melihat *invite-code graph* berguna untuk hal-hal yang berkaitan dengan kepercayaan dan reputasi pengguna.

* ### Membatasi sebelum menyelesaikan moderasi dan desentralisasi
Sistem kode undangan saat ini memungkinkan kapasitas Bluesky ditingkatkan secara bertahap, mengurangi ganguan dan beban jaringan, sambil tetap meningkatkan fitur dan infrastruktur layanan.

    Bluesky (app) bukan merupakan produk akhir. Bluesky (team) mempertahankan sistem undangan sebelum melakukan [desentralisasi]({% link atproto/desentralisasi.md %}) dimaksudkan untuk memprioritaskan keselamatan pengguna sementara menyelesaikan protokol dan sistem [moderasi]({% link moderasi/0-moderasi.md %}).

# Mendapatkan dan Membagikan Kode Undangan
Setidaknya ada dua cara terbaik untuk mendaftar ke platform:
0. Mendaftarkan diri ke [bsky.app](https://bsky.app) dan menunggu kode undangan dikirim melalui surel.
0. Menggunakan kode dari orang lain yang sudah berhasil mendaftar di Bluesky. Pengguna Bluesky menerima satu kode undangan setiap minggunya, jadi cobalah meminta undangan kepada pengguna Bluesky saat ini.
0. Admin Bluesky dapat melihat dan melacak rantai code undangan. Mengundang atau membuat akun yang melanggar ketentuan atau yang memberikan dampak negatif bagi pengguna lain meskipun secara tidak sengaja akan menurunkan nilai reputasi akun Anda.
0. Cobalah untuk memberikan kode undangan kepada orang atau di lingkungan yang dapat dipercaya.
0. Jika Anda seorang pengembang aplikasi (developer) atau pegiat teknologi yang masih menunggu undangan, isi daftar tunggu berikut khusus untuk developer dan Anda akan menerima kode undangan dalam satu minggu: [https://atproto.com/blog/call-for-developers](https://atproto.com/blog/call-for-developers)

{: .peringatan}
Hati-hati terhadap penipu yang menawarkan untuk menjual kode undangan Bluesky, karena kode-kode ini mungkin tidak berfungsi. Bluesky menggunakan sistem kode undangan berantai, admin bisa melihat siapa yang diundang dan siapa yang mengundang.