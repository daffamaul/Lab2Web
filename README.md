# Lab2Web - Pertanyaan dan Tugas

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada _CSS Cheat Sheet_ yang diberikan pada file terpisah dari modul ini
![before_1](/img/before_1.jpg)
![after_1](/img/after_1.jpg)

2. Apa perbedaan pendeklarasian CSS elemen `h1 {...}` dengan `#intro {...}`? berikan penjelasannya!
>Perbedaan dari keduanya adalah ketika di dalam sebuah tag `body` terdapat beberapa elemen `h1`, penggunaan `class` maupun `id` sangat diperlukan untuk menentukan _style_ diantara salah satunya.

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
![img_1](/img/after_1.jpg)
![img_2](/img/after_3-1.jpg)
![img_3](/img/after_3-2.jpg)
>Dokumen HTML akan menampilkan _style_ mulai dari **inline style**, **internal style**, dan **eksternal style**

4. Pada sebuah elemen HTML terdapat _ID_ dan _Class_, apabila masing-masing _selector_ tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! (`<p id="paragraf-1" class="text-paragraf"></p>`)
![img_4](/img/after_4.jpg)
>Hal tersebut diakibatkan oleh _specificity_ atau pembobotan selector. Untuk sebuah _elemen_ memiliki bobot 1, _class_ memiliki bobot 10, _id_ memiliki bobot 100, _inline_ memiliki bobot 100. 