<p align="center" >
  <b>POINT UTAMA</b>
</p>

---

> #### INSTALASI
> - PHP 8.1.0
> - LARAVEL 10.2.5
>   ```
>   composer create-project laravel/laravel=v10.2.5 belajar-laravel-RESTful-api
>   ```
---
> #### APA ITU RESTFUL API?
> - RESTful API adalah jenis API (Application Programming Interface) yang menggunakan prinsip REST (Representational State Transfer) untuk memungkinkan komunikasi antara berbagai sistem perangkat lunak melalui HTTP.
>
> Berikut adalah kode http verbs :
> ```
> GET = Untuk mengambil data dari server.
> POST = Untuk mengirim data ke server dan biasanya digunakan untuk membuat sumber daya baru.
> PUT = Untuk memperbarui sumber daya yang ada di server.
> DELETE = Untuk menghapus sumber daya dari server.
> ```
>
> Berikut fungsi restful api
> ```
> Create = Menambah data baru
> Read: Mengambil data yang ada
> Update: Memperbarui data yang ada
> Delete: Menghapus data yang ada
> ```
> #### STATELESS
> - Setiap permintaan dari klien ke server harus berisi semua informasi yang diperlukan untuk memahami dan memproses permintaan tersebut. Server tidak menyimpan konteks apapun dari permintaan sebelumnya.
>
> #### UNIFORM INTERFACE
> - RESTful API harus memiliki antarmuka yang konsisten dan standar yang memungkinkan interaksi yang mudah antara sistem yang berbeda, dan dapat menidentifikasi sumber daya melalui URL 
>
> #### CLIENT SERVER ARCHITECTURE
> - Klien dan server harus saling terpisah sehingga masing-masing dapat dikembangkan dan diskalakan secara independen.
> 
> #### CACHEABLE
> - Respons dari server dapat di-cache oleh klien untuk meningkatkan performa dan efisiensi.
---
> #### INTEGRASI LAYANAN 
> - RESTful API memungkinkan integrasi berbagai layanan dan aplikasi pihak ketiga. Misalnya, sebuah aplikasi e-commerce dapat menggunakan RESTful API untuk terhubung dengan layanan pembayaran atau layanan pengiriman.
>
> #### SKALABILITAS 
> -  Dengan arsitektur klien-server yang terpisah, RESTful API membantu pengembang untuk mengembangkan, mengelola, dan menskalakan aplikasi secara lebih mudah.
> 
> #### PLATFORM AGNOSTIC
> - RESTful API dapat digunakan oleh berbagai jenis klien yang menggunakan berbagai platform.
> 
> #### KEAMANAN DAN KONTROL AKSES
> - RESTful API sering dilengkapi dengan mekanisme keamanan seperti autentikasi dan otorisasi.
>
> #### MODULARITAS
> - RESTful API memungkinkan pengembang untuk membuat komponen yang dapat digunakan kembali di berbagai bagian aplikasi atau bahkan di aplikasi lain.
> 
> #### MICROSERVICES
> - Dalam arsitektur microservices, RESTful API digunakan untuk menghubungkan berbagai layanan kecil yang bekerja sama untuk membentuk aplikasi yang lebih besar. 
>
<p align="center" >
  <b>PERTANYAAN DAN CATATAN TAMBAHAN</b>
</p>
---
> - 
---
<p align="center" >
  <b>KESIMPULAN</b>
</p>
