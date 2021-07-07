---
title: Mencoba Cloudinary - Optimasi Media di Cloud
description: "Mencoba manajemen media untuk web menggunakan Cloudinary"
syntax: true
category: tech
tags: jekyll 
permalink: /blog/cloudinary-cloud-media
---

Efek _nyari_ dan akhirnya menemukan _template_ dan tema yang cocok untuk memudakan (??) blog ini (terima kasih [Derek Kedziora](derekkedziora.com)), ternyata saya dapat bonus pengetahuan baru. Saat lihat bagian `about` di web Derek, fotonya bisa berubah-ubah secara random, tapi bukan itu yang menarik. Yang menarik _malah_ pemanfaatan [Cloudinary](https://cloudinary.com/) untuk menyimpan foto-foto yang akan dirandom. Hasil ngecek webnya dibilang bahwa Cloudinary ini adalah layanan pengelolaan dan optimasi media yang mau dipakai di aplikasi atau web. Karena penasaran akhirnya saya coba _upload_ beberapa foto ke Cloudinary.

![Media Library Cloudinary](https://res.cloudinary.com/dm62lnxoi/image/upload/c_scale,w_800/v1625635974/articles/cloudinary_med_lcwcus.png)

Ternyata kita bisa _ngasih_ efek atau _ngedit_ gambar yang pengen kita tampilkan di web/blog, di contoh ini gambar saya bikin _grayscale_ dan di _resize_ dengan ukuran tertentu. Ada banyak _banget_ efek foto/media yang bisa kita pilih (silahkan dicoba sendiri hehehe) tapi kalo saya cuma butuh untuk _resize_ menjadi 400x400 px agar _loading_ web menjadi lebih cepat dan efektif:

![Editing in Cloudinary](https://res.cloudinary.com/dm62lnxoi/image/upload/c_scale,w_800/v1625635974/articles/cloudinary_edit_xfdoi5.png)

Kita mendapatkan URL dari gambar yang sudah diedit tersebut:

```html
https://res.cloudinary.com/dm62lnxoi/image/upload/c_scale,e_grayscale,w_400/v1625550453/blog/earth1_c_rfvv4i.png
```

Setelah kita edit, URL _https_ tinggal kita _copy_ dan selesai sudah hehehe, efek _grayscale_ akan tercermin dalam kode `e_grayscale` sedangkan efek _resize_ pada `c_scale,w_400`. Ada opsi lain dengan berbagai metode selain _https_. Dengan Cloudinary ini kita gaperlu ngedit gambar satu per satu di editor gambar, tinggal kita sesuaikan _syntax_ _editing_ (seperti `c_scale,e_grayscale,w_400`) yang akan diaplikasikan di URL gambar _https_ Cloudinary tadi, selamat mencoba! 😀.

