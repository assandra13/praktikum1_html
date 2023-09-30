# praktikum1_html
# **Lab 1 Web**

```
Nama    : Assandra Julyant Firdausy
NIM     : 312210384
Kelas   : TI.2.A.4
MATKUL  : Pemrograman Web 1
```

## **Daftar Isi**

**1. [Instruksi Praktikum](#instruksi-praktikum)**  
**2. [Langkah-langkah Praktikum](#langkah-langkah-praktikum)**  
**3. [Jawab Pertanyaan Berikut](#jawab-pertanyaan-berikut)**

## **Instruksi Praktikum**

1. Persiapkan text editor, di sini saya menggunakan VSCode
2. Buat file baru dengan nama lab1_tag_dasar.html
3. Buat struktur dasar dari dokumen HTML.
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
5. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org

## **Langkah-langkah Praktikum**

1. Buka VSCode atau text editor, disini saya menggunakan VSCode karena saya terbiasa menggunakan VSCode.
   ![img](img)

2. Kemudian buat sebuah file dengan nama **tag_dasar.html**

3. Buatlah struktur dasar HTML

   ```html
   !DOCTYPE html>
   <html>
     <head>
       <title>Tag HTML Dasar</title>
     </head>

     <body></body>
   </html>
   ```

4. Lalu buka file tersebut pada web browser disini saya menggunakan web browser chrome.
   

**5. Membuat Paragraf**

```html
!DOCTYPE html>
<html>
  <head>
    <title>Tag HTML Dasar</title>
  </head>

  <body>
    <!-- Ini adalah paragraf pertama -->
    <p align="justify">
      Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
      Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami
      dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag
      dasar HTML.
    </p>
    <!-- Ini adalah paragraf kedua -->
    <p align="justify">
      Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang
      saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan
      menggunakan tag dasar html.
    </p>
  </body>
</html>
```

Dalam HTML, atribut <b>align</b> digunakan untuk mengatur atau mengendalikan tata letak atau penempatan elemen tertentu dalam halaman web. Penggunaan atribut <b>align</b> bervariasi tergantung pada elemen HTML yang akan di gunakan. Pada elemen teks, <b>align</b> digunakan untuk mengatur penyebaran atau perataan teks. Nilai yang umum digunakan adalah "left" (kiri), "right" (kanan), "center" (tengah), dan "justify" (rata kiri dan kanan). Namun, perlu diperhatikan bahwa penggunaan atribut <b>align</b> telah usang dalam HTML versi yang lebih baru seperti HTML5. Sebaiknya, Anda menggunakan CSS untuk mengendalikan tata letak elemen dalam halaman web. CSS memberikan lebih banyak fleksibilitas dan kontrol dalam mengatur tata letak dan penampilan elemen.

**6. Menambahkan Judul**
h1 sampai h6 (opsional)

```html
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```

**7. Memformat teks**

```html
<p align="justify">
  Kami sedang belajar <mark>HTML dasar</mark> , pada matakuliah
  <b>Pemrograman Web</b> di Prodi Teknik Informasi
  <u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat adalah
  membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.
</p>
```

**8. Menyisipkan gambar**

```html
<img src="Logo_UPB.png" width="200" height="160">
```

gunakan juga atribut widht dan height untuk mengatur ukuran gambar yang akan di tampilkan nanti.

<h3><b>9. Menambahkan hyperlink</b></h3>

Hyperlink ini berguna untuk berpindah halaman website atau berkunjung kehalaman website

```html
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com" target="_self" >Halaman Web Eksternal Google</a>
</nav>
```

Disini saya menggunakan atribut **target** yang berguna untuk membuka website/halaman di buka pada jendela yang sama.

## **Jawab Pertanyaan Berikut**

1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
   error ketika terjadi kesalahan penulisan tag?      
   **Jawaban:**        
   <mark style="background-color:lightblue">Tidak terjadi error, tetapi tag/kode yang tidak sesuai tidak akan ditampilkan pada halaman website.</mark>

2. Apa perbedaan dari tag p dengan tag br, berikan penjelasannya!        
   **Jawaban:**         
   <mark style="background-color:lightblue">Tag p digunakan untuk membuat paragraf, sedangkan tag br digunakan untuk memberikan enter pada paragraf.</mark>

3. Apa perbedaan atribut title dan alt pada tag img, berikan penjelasannya!  
   **Jawaban:**        
   <mark style="background-color:lightblue">Atribut title akan muncul jika kursor diarahkan keobjek/gambar, sedangkan atribut alt(alternatif) akan muncul jika user tidak bisa menampilkan gambar atau jaringan internet tidak bisa menginput gambar.</mark>

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!        
   **Jawaban:**        
   <mark style=background-color:lightblue>sebaiknya hanya mengisi atribut widht saja karna dengan mengisi atribut widht saja itu sudah termasuk height, contoh : jika saya mengisi widht="100" maka otomatis height = "100" jadi height tersebut mengikuti widhtnya</mark>

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( \_blank, \_self, \_top,
\_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?  
**Jawaban:**         
  <ul >
  <li><mark style=background-color:lightblue>_blank: Ketika Anda menggunakan target="_blank", tautan akan dibuka dalam jendela atau tab browser yang baru, terpisah dari halaman saat ini. Ini akan memungkinkan pengguna tetap berada di halaman asal sambil mengakses tautan yang dibuka dalam jendela baru.</mark></li>

  <li><mark style=background-color:lightblue>_self: Nilai ini adalah nilai default. Ketika Anda menggunakan target="_self", tautan akan dibuka dalam jendela atau tab yang sama dengan halaman saat ini. Ini adalah perilaku standar jika Anda tidak menentukan nilai target.</mark></li>

  <li><mark style=background-color:lightblue>_top: Ketika Anda menggunakan target="_top", tautan akan membuka halaman baru dalam jendela atau tab yang sama seperti _self, namun jika halaman tersebut merupakan frame dalam struktur frame HTML, maka halaman baru tersebut akan menggantikan seluruh frame tersebut. Ini akan mengarahkan tautan ke halaman yang paling atas dalam hierarki frame.</mark></li>

  <li><mark style=background-color:lightblue>_parent: Jika Anda menggunakan target="_parent", tautan akan membuka halaman baru dalam jendela atau tab yang sama seperti _self, tetapi jika halaman tersebut merupakan bagian dari struktur frame HTML, maka halaman baru tersebut akan menggantikan frame yang berisi halaman saat ini (frame yang berada satu tingkat di atas dalam hierarki)</mark>.</li>

  </ul>