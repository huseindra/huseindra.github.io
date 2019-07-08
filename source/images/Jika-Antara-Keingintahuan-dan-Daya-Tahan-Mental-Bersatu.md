---
title: 'Mengenal Swift #1 : Hello, Swift ! !'
author: Husein Indra Kusuma
date: 2018-10-11 01:01:18
categories:
- Self Development
tags:
- Swift Programming
- Belajar Swift
cover_image: images/swift-image.jpg
---
Saya tertarik belajar pemograman yang besut oleh Apple ini. Menurut saya, Swift merupakan bahasa pemograman yang unik, kenapa ?

<!-- more -->
{% asset_img img-fluid swift-image.jpg %}
Swift malah menawarkan solusi yang lebih dekat ke mesin namun tetap menawarkan hal-hal modern dan abstraksi tingkat tinggi. Sebenarnya saya baru saja memulai belajar Swift dan tulisan ini merupakan salah satu cara saya untuk merawat sebuah ingatan.

### Welcome to Swift !

Swift merupakan gabungan dari bahasa pemograman C dan C# yang diciptakan untuk mengembangkan aplikasi dari produk Apple seperti iOS, Mac, Apple TV dan Apple Watch. Swift bersifat open source. Tak perlu menunggu lama, mari ke bahasan pertama yaitu “Hello World”.
### Hello World

Mencetak hasil di Swift tidak jauh berbeda dengan pemograman C atau Java.

> print(“Hello, world!”)

Tentu saja akan mencetak kalimat Hello, World!. Untuk mencetak nilai variabel didalam teks, letakkan backslash(“\”) sebelum kurung buka.

>var iniVariabel = 212
>print(“Wirosableng terkenal dengan sebutan pendekar \(iniVariabel)”)

Ada yang perlu diperhatikan, ketika Anda hanya ingin mencetak variable tidak perlu menggunakan backslash(“\”).

>var iniVariabel = 212
>print(iniVariabel)

Disisi lain, penggunaan tanda titik koma (;) merupakan hal yang opsional di Swift, kecuali Anda ingin menempatkan beberapa kondisi pada satu baris, dalam hal ini titik koma diperlukan.

### Komentar

Compiler Swift mengabaikan komentar, hal ini dapat membantu Anda untuk membuat catatan didalam koding. Komentar satu baris dibuka dengan dua garis miring ke depan (//).

>//Ini adalah komentar

Sedangkan untuk komentar multiline menggunakan dimulai dengan satu garis miring ke depan, diikuti oleh tanda bintang (/ *), lalu diakhiri dengan tanda bintang, diikuti dengangaris miring ke depan (* /).

>/*Ini adalah komentar multiline bro , jangan nggak fokus gitu dong. Mari memulai dari abjad A. hehe*/

Komentar multiline di Swift juga, dapat disarangkan di dalam komentar multilain lainnya atau gampangnya sih di nested-in.

### Perangkat Perang

Untuk membangun aplikasi dengan Swift, Anda memerlukan komputer Mac (OS X 10.10 atau lebih baru). Buat Anda pengguna Mac, dapat mengunduh dan menginstal versi terbaru.

> developer.apple.com/xcode/downloads/.

Sekian ilmu pertama seputar Swift yang bisa saya bagikan. Terimakasih
