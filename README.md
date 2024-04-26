## Praktikum WEB 1
## HTML

## 1.html interduction


Apa itu HTML?
- HTML adalah singkatan dari Hyper Text Markup Language
- HTML adalah bahasa markup standar untuk membuat halaman Web
- HTML menjelaskan struktur halaman Web
- HTML terdiri dari serangkaian elemen
- Elemen HTML memberi tahu browser cara menampilkan konten
- Elemen HTML memberi label pada bagian konten seperti "ini adalah judul", "ini adalah paragraf", "ini adalah tautan", dll.

```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

![interduction 1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/e2dde9ee-1937-4659-ba2c-070b482188c6)



Example Explained
The <!DOCTYPE html> declaration defines that this document is an HTML5 document
The <html> element is the root element of an HTML page
The <head> element contains meta information about the HTML page
The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.


## 2.Html elemnts

Elemen HTML ditentukan oleh tag awal, beberapa konten, dan tag akhir.



```
<!DOCTYPE html>
<html>
<body>

<h1>Makan nasi</h1>
<p>Makan batagor.</p>

</body>
</html>

```

![element1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/52df3ef7-4086-40fa-978c-3877d8adc410)

Jangan Pernah Lewati Tag Akhir
Beberapa elemen HTML akan ditampilkan dengan benar, meskipun Anda lupa tag penutupnya:

```
<!DOCTYPE html>
<html>
<body> 

<p>This is a paragraph.
<p>This is a paragraph.

</body>
</html>

```

Elemen HTML Kosong
Elemen HTML yang tidak memiliki konten disebut elemen kosong.
Tag <br>mendefinisikan jeda baris, dan merupakan elemen kosong tanpa tag penutup:


```
<!DOCTYPE html>
<html>
<body> 

<p>This is a <br> paragraph with a line break.</p>

</body>
</html>
```

## 3. HTML Atributs

HTML Attributes


- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"


```
<!DOCTYPE html>
<html>
<body>

<h2>The href Attribute</h2>

<p>HTML links are defined with the a tag. The link address is specified in the href attribute:</p>

<a href="https://www.w3schools.com">Visit W3Schools</a>

</body>
</html>
```





The src Attribute
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:


```
<!DOCTYPE html>
<html>
<body>

<h2>cola cola</h2>
<p>HTML images are defined with the img tag, and the filename of the image source is specified in the src attribute:</p>

<img src="https://eskipaper.com/images/coca-cola-can-1.jpg" width="500" height="600">

</body>
</html>
```

![atribut 2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/0305c89f-4732-47f1-9204-cf50854fe29f)

- Ada dua cara untuk menentukan URL dalam src atribut:

1. URL Absolut - Tautan ke gambar eksternal yang dihosting di situs web lain. Contoh: src="https://www.w3schools.com/images/img_girl.jpg" .
Catatan: Gambar eksternal mungkin dilindungi hak cipta. Jika Anda tidak mendapatkan izin untuk menggunakannya, Anda mungkin melanggar undang-undang hak cipta. Selain itu, Anda tidak dapat mengontrol gambar eksternal; itu bisa tiba-tiba dihapus atau diubah.
2. URL Relatif - Tautan ke gambar yang dihosting di dalam situs web. Di sini, URL tidak menyertakan nama domain. Jika URL diawali tanpa garis miring, URL tersebut akan relatif terhadap halaman saat ini. Contoh: src="img_girl.jpg". Jika URL dimulai dengan garis miring, itu akan berhubungan dengan domain. Contoh: src="/images/img_girl.jpg".
Tip: Hampir selalu yang terbaik adalah menggunakan URL relatif. Mereka tidak akan rusak jika Anda mengubah domain.


Atribut lebar dan tinggi
Tag <img>juga harus berisi atribut widthand height, yang menentukan lebar dan tinggi gambar (dalam piksel):

```
<!DOCTYPE html>
<html>
<body>

<h2>Width and Height Attributes</h2>

<p>The width and height attributes of the img tag, defines the width and height of the image:</p>

<img src="https://th.bing.com/th/id/OIP.WC3WUdOUUUSG6pvrQtK3agAAAA?rs=1&pid=ImgDetMain" width="500" height="500">

</body>
</html>

```



![atribut3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/d7d639b9-46e8-4568-a640-dad31fb554f9)



Atribut alt

Atribut yang diperlukan altuntuk <img> tag menentukan teks alternatif untuk suatu gambar, jika gambar karena alasan tertentu tidak dapat ditampilkan. Hal ini dapat disebabkan oleh koneksi yang lambat, atau kesalahan pada srcatribut, atau jika pengguna menggunakan pembaca layar.

```
<!DOCTYPE html>
<html>
<body>

<h2>The alt Attribute</h2>
<p>The alt attribute should reflect the image content, so users who cannot see the image get an understanding of what the image contains:</p>

<img src="https://th.bing.com/th/id/OIP.DbiighMUSdxhvzEu47J_PwHaEO?w=285&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7" alt="Girl with a jacket" width="500" height="400">

</body>
</html>
```

![atribut4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/dec008a1-ebe2-43ef-9074-4bd4bb898f2c)

Atribut gaya

Atribut styledigunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya.

```
<!DOCTYPE html>
<html>
<body>

<h2>The style Attribute</h2>
<p>The style attribute is used to add styles to an element, such as color:</p>

<p style="color:blue;">This is a red paragraph.</p>

</body>
</html>
```

![atribut5](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/eda025df-11e4-43e7-aedf-3af5e4b1f55e)



Judul Atribut

Atribut titlemendefinisikan beberapa informasi tambahan tentang suatu elemen.
Nilai atribut title akan ditampilkan sebagai tooltip ketika Anda mengarahkan mouse ke elemen:

```
<!DOCTYPE html>
<html>
<body>

<h2 title="I'm a header">The title Attribute</h2>

<p title="I'm a tooltip">Mouse over this paragraph, to display the title attribute as a tooltip.</p>

</body>
</html>


```

Ringkasan Bab

- Semua elemen HTML dapat memiliki atribut
- Atribut hrefmenentukan <a>URL halaman yang dituju link tersebut
- Atribut srcmenentukan <img>jalur ke gambar yang akan ditampilkan
- Atribut widthdan heightmemberikan <img>informasi ukuran untuk gambar
- Atribut altmenyediakan <img>teks alternatif untuk suatu gambar
- Atribut styledigunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya
- Atribut langtag <html>menyatakan bahasa halaman Web
- Atribut titlemendefinisikan beberapa informasi tambahan tentang suatu elemen

## 4. HTML Paragraph

Paragraf HTML

Elemen HTML <p>mendefinisikan paragraf.
Sebuah paragraf selalu dimulai pada baris baru, dan browser secara otomatis menambahkan spasi (margin) sebelum dan sesudah paragraf.

Tampilan HTML
Anda tidak dapat memastikan bagaimana HTML akan ditampilkan.
Layar besar atau kecil, dan jendela yang diubah ukurannya akan memberikan hasil yang berbeda.
Dengan HTML, Anda tidak dapat mengubah tampilan dengan menambahkan spasi atau baris tambahan pada kode HTML Anda.
Browser akan secara otomatis menghapus spasi dan baris tambahan saat halaman ditampilkan:

```
<!DOCTYPE html>
<html>
<body>

<p>
This paragraph
contains a lot of lines
in the source code,
but the browser 
ignores it.
</p>

<p>
This paragraph
contains      a lot of spaces
in the source     code,
but the    browser 
ignores it.
</p>

<p>
The number of lines in a paragraph depends on the size of the browser window. If you resize the browser window, the number of lines in this paragraph will change.
</p>

</body>
</html>


```

![paragrp1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/31ab12ad-643a-404c-b8b2-39c5a930b2ba)

Aturan Horisontal HTML


Tag <hr>mendefinisikan jeda tematik di halaman HTML, dan paling sering ditampilkan sebagai aturan horizontal.
Elemen ini <hr>digunakan untuk memisahkan konten (atau menentukan perubahan) di halaman HTML:


```
<!DOCTYPE html>
<html>
<body>

<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>

<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>

<h2>This is heading 2</h2>
<p>This is some other text.</p>

</body>
</html>

```

![p2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/7f68f73b-f4c4-42f5-b701-3629ccf062cd)

Jeda Baris HTML


Elemen HTML <br>mendefinisikan jeda baris.
Gunakan <br>jika Anda menginginkan jeda baris (baris baru) tanpa memulai paragraf baru:

```
<!DOCTYPE html>
<html>
<body>

<p>This is<br>a paragraph<br>with line breaks.</p>

</body>
</html>


```


![p3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/d53e9509-74f1-44c2-a334-a43fe68da06d)


Solusi - Elemen HTML <pre>


Elemen HTML <pre>mendefinisikan teks yang telah diformat sebelumnya.
Teks di dalam <pre>elemen ditampilkan dalam font dengan lebar tetap (biasanya Courier), dan mempertahankan spasi dan jeda baris:

```
<!DOCTYPE html>
<html>
<body>

<p>The pre tag preserves both spaces and line breaks:</p>

<pre>
   My Bonnie lies over the ocean.

   My Bonnie lies over the sea.

   My Bonnie lies over the ocean.
   
   Oh, bring back my Bonnie to me.
</pre>

</body>
</html>


```

![p7](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/db6701a7-26c6-4652-ac8a-3c1a1801e310)

## 5. HTML Styles

Atribut HTML styledigunakan untuk menambahkan gaya ke suatu elemen, seperti warna, font, ukuran, dan lainnya.

Warna latar belakang
Properti CSS background-colormendefinisikan warna latar belakang untuk elemen HTML.


```
<!DOCTYPE html>
<html>
<body style="background-color:red;">

<h1>superman</h1>
<p>batman</p>

</body>
</html>
```

![s11](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/edd575e1-7027-4319-bbf8-4d3d3517fc9b)


Warna teks
Properti CSS colormendefinisikan warna teks untuk elemen HTML:

```
<!DOCTYPE html>
<html>
<body>

<h1 style="color:black;">ganteng dulu baru bisa dihargai ;)</h1>
<p style="color:red;">pinter dulu baru bisa di hargai ;)</p>

</body>
</html>
```


![s2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/8651ddc9-15f1-4f32-bbff-0050be600e14)

font
Properti CSS font-familymendefinisikan font yang akan digunakan untuk elemen HTML:

```
<!DOCTYPE html>
<html>
<body>

<h1 style="font-family:verdana;">harus ganteng</h1>
<p style="font-family:courier;">harus pinter</p>

</body>
</html>


```

![s3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/22b373e9-0120-4d1d-ac10-ced24c6c8321)

Ukuran teks
Properti CSS font-sizemendefinisikan ukuran teks untuk elemen HTML:

```
<!DOCTYPE html>
<html>
<body>

<h1 style="font-size:400%;">cilacap</h1>
<p style="font-size:260%;">bercahaya</p>

</body>
</html>


```

![s4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/14ee5f7d-a7a2-4d49-a9ec-c4420771f607)

Ringkasan Bab


- Gunakan styleatribut untuk menata elemen HTML
- Gunakan background-coloruntuk warna latar belakang
- Gunakan coloruntuk warna teks
- Gunakan font-familyuntuk font teks
- Gunakan font-sizeuntuk ukuran teks
- Gunakan text-alignuntuk perataan teks


## 6. HTML Color

Warna HTML ditentukan dengan nama warna yang telah ditentukan sebelumnya, atau dengan nilai RGB, HEX, HSL, RGBA, atau HSLA.

```
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:Tomato;">Tomato</h1>
<h1 style="background-color:Orange;">Orange</h1>
<h1 style="background-color:DodgerBlue;">DodgerBlue</h1>
<h1 style="background-color:MediumSeaGreen;">MediumSeaGreen</h1>
<h1 style="background-color:Gray;">Gray</h1>
<h1 style="background-color:SlateBlue;">SlateBlue</h1>
<h1 style="background-color:Violet;">Violet</h1>
<h1 style="background-color:LightGray;">LightGray</h1>

</body>
</html>

```


![c1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/1d629639-4a49-4ad0-b8ff-27db4d1c6700)

Warna latar belakang
Anda dapat mengatur warna latar belakang untuk elemen HTML:

```
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:DodgerBlue;">Hello World</h1>

<p style="background-color:Tomato;">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
</p>

</body>
</html>
```


![c2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/a64dff24-1ebc-496e-958c-49cf3fc038c1)

Warna teks
Anda dapat mengatur warna teks:

```
<!DOCTYPE html>
<html>
<body>

<h3 style="color:Tomato;">Hello World</h3>

<p style="color:DodgerBlue;">Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>

<p style="color:MediumSeaGreen;">Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.</p>

</body>
</html>

```

![c3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/dbbc8318-b13a-495d-a55e-9f57a966196c)

Warna Perbatasan
Anda dapat mengatur warna batas:

```
<!DOCTYPE html>
<html>
<body>

<h1 style="border: 2px solid Tomato;">Hello World</h1>

<h1 style="border: 2px solid DodgerBlue;">Hello World</h1>

<h1 style="border: 2px solid Violet;">Hello World</h1>

</body>
</html>


```


![c4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/56455026-3089-49a6-bd42-4f4c1ef8f2c6)

Nilai Warna


Dalam HTML, warna juga dapat ditentukan menggunakan nilai RGB, nilai HEX, nilai HSL, nilai RGBA, dan nilai HSLA.
Tiga elemen <div> berikut memiliki warna latar belakang yang diatur dengan nilai RGB, HEX, dan HSL:

```
<!DOCTYPE html>
<html>
<body>

<p>Same as color name "Tomato":</p>

<h1 style="background-color:rgb(255, 99, 71);">rgb(255, 99, 71)</h1>
<h1 style="background-color:#ff6347;">#ff6347</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">hsl(9, 100%, 64%)</h1>

<p>Same as color name "Tomato", but 50% transparent:</p>
<h1 style="background-color:rgba(255, 99, 71, 0.5);">rgba(255, 99, 71, 0.5)</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">hsla(9, 100%, 64%, 0.5)</h1>

<p>In addition to the predefined color names, colors can be specified using RGB, HEX, HSL, or even transparent colors using RGBA or HSLA color values.</p>

</body>
</html>

```


![c5](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/f1355ba0-8df9-4f3a-8e29-86458a2404a3)

## Warna RGB


Dalam HTML, suatu warna dapat ditentukan sebagai nilai RGB, menggunakan rumus ini:
rgb ( merah, hijau , biru )
Setiap parameter (merah, hijau, dan biru) menentukan intensitas warna dengan nilai antara 0 dan 255.
Artinya ada 256 x 256 x 256 = 16777216 kemungkinan warna!
Misalnya, rgb(255, 0, 0) ditampilkan dengan warna merah, karena merah disetel ke nilai tertingginya (255), dan dua lainnya (hijau dan biru) disetel ke 0.
Contoh lainnya, rgb(0, 255, 0) ditampilkan dengan warna hijau, karena hijau disetel ke nilai tertingginya (255), dan dua lainnya (merah dan biru) disetel ke 0.
Untuk menampilkan warna hitam, atur semua parameter warna ke 0, seperti ini: rgb(0, 0, 0).
Untuk menampilkan warna putih, atur semua parameter warna ke 255, seperti ini: rgb(255, 255, 255).
Bereksperimenlah dengan mencampurkan nilai RGB di bawah ini:


```
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:rgb(255, 0, 0);">rgb(255, 0, 0)</h1>
<h1 style="background-color:rgb(0, 0, 255);">rgb(0, 0, 255)</h1>
<h1 style="background-color:rgb(60, 179, 113);">rgb(60, 179, 113)</h1>
<h1 style="background-color:rgb(238, 130, 238);">rgb(238, 130, 238)</h1>
<h1 style="background-color:rgb(255, 165, 0);">rgb(255, 165, 0)</h1>
<h1 style="background-color:rgb(106, 90, 205);">rgb(106, 90, 205)</h1>

</body>
</html>

```


![rgb](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/c1c83276-2775-417c-aafd-92c6b846a864)

## Warna HEX


Dalam HTML, suatu warna dapat ditentukan menggunakan nilai heksadesimal dalam bentuk:
#rrggbb​
Dimana rr (merah), gg (hijau) dan bb (biru) merupakan nilai heksadesimal antara 00 dan ff (sama dengan desimal 0-255).
Misalnya, #ff0000 ditampilkan dengan warna merah, karena merah disetel ke nilai tertingginya (ff), dan dua lainnya (hijau dan biru) disetel ke 00.
Contoh lainnya, #00ff00 ditampilkan dengan warna hijau, karena hijau disetel ke nilai tertingginya (ff), dan dua lainnya (merah dan biru) disetel ke 00.
Untuk menampilkan warna hitam, atur semua parameter warna ke 00, seperti ini: #000000.
Untuk menampilkan warna putih, atur semua parameter warna ke ff, seperti ini: #ffffff.
Bereksperimenlah dengan mencampurkan nilai HEX di bawah ini:

```
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:#ff0000;">#ff0000</h1>
<h1 style="background-color:#0000ff;">#0000ff</h1>
<h1 style="background-color:#3cb371;">#3cb371</h1>
<h1 style="background-color:#ee82ee;">#ee82ee</h1>
<h1 style="background-color:#ffa500;">#ffa500</h1>
<h1 style="background-color:#6a5acd;">#6a5acd</h1>

</body>
</html>

```


![hex](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/cc9b3b0a-9f91-4952-9846-aa3fdeddb22b)



## Warna HSL


Dalam HTML, suatu warna dapat ditentukan menggunakan hue, saturation, dan lightness (HSL) dalam bentuk:
hsl( rona , saturasi , kecerahan )
Hue adalah derajat pada roda warna dari 0 hingga 360. 0 berwarna merah, 120 berwarna hijau, dan 240 berwarna biru.
Saturasi adalah nilai persentase. 0% berarti warna abu-abu, dan 100% berarti warna penuh.
Ringan juga merupakan nilai persentase. 0% berwarna hitam, dan 100% berwarna putih.
Bereksperimenlah dengan mencampurkan nilai HSL di bawah ini:


```
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%)</h1>
<h1 style="background-color:hsl(240, 100%, 50%);">hsl(240, 100%, 50%)</h1>
<h1 style="background-color:hsl(147, 50%, 47%);">hsl(147, 50%, 47%)</h1>
<h1 style="background-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%)</h1>
<h1 style="background-color:hsl(39, 100%, 50%);">hsl(39, 100%, 50%)</h1>
<h1 style="background-color:hsl(248, 53%, 58%);">hsl(248, 53%, 58%)</h1>

</body>
</html>
```

![hsl](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/7bf1f064-7b12-4a4c-b62f-56e09aa50457)



## 7. HTML CSS


Apa itu CSS?
Cascading Style Sheets (CSS) digunakan untuk memformat tata letak halaman web.
Dengan CSS, Anda dapat mengontrol warna, font, ukuran teks, jarak antar elemen, bagaimana elemen diposisikan dan ditata, gambar latar belakang atau warna latar belakang apa yang akan digunakan, tampilan berbeda untuk perangkat dan ukuran layar berbeda, dan lebih banyak!


Menggunakan CSS
CSS dapat ditambahkan ke dokumen HTML dengan 3 cara:


- Inline - dengan menggunakan styleatribut di dalam elemen HTML
- Internal - dengan menggunakan <style>elemen di <head>bagian tersebut
- Eksternal - dengan menggunakan <link> elemen untuk menautkan ke file CSS eksternal
- Cara paling umum untuk menambahkan CSS adalah dengan menyimpan gaya di file CSS eksternal. Namun, dalam tutorial ini kita akan menggunakan gaya inline dan internal, karena ini lebih mudah untuk didemonstrasikan, dan lebih mudah bagi Anda untuk mencobanya sendiri.


CSS sebaris


CSS sebaris digunakan untuk menerapkan gaya unik ke satu elemen HTML.
CSS sebaris menggunakan styleatribut elemen HTML.
Contoh berikut mengatur warna teks elemen <h1>menjadi biru, dan warna teks elemen <p>menjadi merah:


```
<!DOCTYPE html>
<html>
<body>

<h1 style="color:green;">Makan</h1>

<p style="color:brown;">Biar ga sakit</p>

</body>
</html>
```


![c1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/f60393a1-e455-4c96-ac6e-81adbf8359c9)


CSS dalaman


CSS internal digunakan untuk menentukan gaya untuk satu halaman HTML.
CSS internal didefinisikan di <head>bagian halaman HTML, di dalam sebuah <style>elemen.
Contoh berikut mengatur warna teks SEMUA <h1>elemen (di halaman itu) menjadi biru, dan warna teks SEMUA <p>elemen menjadi merah. Selain itu, halaman akan ditampilkan dengan warna latar belakang "biru bubuk": 

```
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: red;}
p    {color: black;}
</style>
</head>
<body>

<h1>Gini amat</h1>
<p>Hidup</p>

</body>
</html>

```


![c2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/ee6067e1-6719-4707-94e3-4459da92c32d)



CSS eksternal


Lembar gaya eksternal digunakan untuk menentukan gaya pada banyak halaman HTML.
Untuk menggunakan style sheet eksternal, tambahkan link ke dalamnya di <head>bagian setiap halaman HTML:

```
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```


![c6](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/c1998ba5-8add-4f4e-9953-89220e9e1695)


Perbatasan CSS


Properti CSS bordermendefinisikan batas di sekitar elemen HTML.
Tip: Anda dapat menentukan batas untuk hampir semua elemen HTML.


```

<!DOCTYPE html>
<html>
<head>
<style>
p {
  border: 2px solid brown;
}
</style>
</head>
<body>

<h1>This is a heading</h1>

<p>ikan</p>
<p>harimau</p>
<p>buaya</p>

</body>
</html>

```


![c8](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/55d18de7-b04e-4d26-916e-32a45313db0c)


Bantalan CSS


Properti CSS paddingmendefinisikan padding (spasi) antara teks dan batas.


```
<!DOCTYPE html>
<html>
<head>
<style>
p {
  border: 2px solid powderblue;
  padding: 30px;
}
</style>
</head>
<body>

<h1>This is a heading</h1>

<p>nanas</p>
<p>alpukat</p>
<p>pisang</p>

</body>
</html>
```


![c9](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/13c6023e-87a0-4022-b3b8-2af10bd4fbcd)


Margin CSS


Properti CSS marginmendefinisikan margin (spasi) di luar batas.


```
<!DOCTYPE html>
<html>
<head>
<style>
p {
  border: 2px solid powderblue;
  margin: 50px;
}
</style>
</head>
<body>

<h1>Sepatu super</h1>

<p>This is a paragraph.</p>
<p>This is a paragraph.</p>
<p>This is a paragraph.</p>

</body>
</html>


```



![cc](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/332e341b-1d8d-4595-8bdf-fc2708235139)



Tautan ke CSS Eksternal


Style sheet eksternal dapat direferensikan dengan URL lengkap atau dengan jalur yang berhubungan dengan halaman web saat ini.



```
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>robot</h1>
<p>mobil kereta</p>

</body>
</html>


```


![ccc](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/e92cb511-3228-436c-bb4c-f1b4566db359)



Ringkasan Bab



- Gunakan atribut HTML styleuntuk penataan gaya sebaris
- Gunakan elemen HTML <style>untuk mendefinisikan CSS internal
- Gunakan elemen HTML <link>untuk merujuk ke file CSS eksternal
- Gunakan elemen HTML <head>untuk menyimpan elemen <style> dan <link>
- Gunakan properti CSS coloruntuk warna teks
- Gunakan properti CSS font-familyuntuk font teks
- Gunakan properti CSS font-sizeuntuk ukuran teks
- Gunakan properti CSS borderuntuk batas
- Gunakan properti CSS paddinguntuk ruang di dalam perbatasan
- Gunakan properti CSS marginuntuk ruang di luar batas


## 8. HTML Link


Tautan HTML - Hyperlink


Tautan HTML adalah hyperlink.
Anda dapat mengeklik tautan dan melompat ke dokumen lain.
Saat Anda menggerakkan mouse ke atas link, panah mouse akan berubah menjadi tangan kecil.



Tautan HTML - Atribut target


Secara default, halaman tertaut akan ditampilkan di jendela browser saat ini. Untuk mengubahnya, Anda harus menentukan target lain untuk tautan tersebut.
Atribut targetmenentukan tempat untuk membuka dokumen tertaut.
Atribut targetdapat memiliki salah satu dari nilai berikut:
-self- Bawaan. Membuka dokumen di jendela/tab yang sama dengan yang diklik
-blank- Membuka dokumen di jendela atau tab baru
-parent- Membuka dokumen di bingkai induk
-top- Membuka dokumen di seluruh isi jendela


```
<!DOCTYPE html>
<html>
<body>

<h2>The target Attribute</h2>

<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a> 

<p>If target="_blank", the link will open in a new browser window or tab.</p>

</body>
</html>


```




![l1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/d7114bb5-739f-44a3-a595-c7053fcf0b17)



URL Absolut vs. URL Relatif


Kedua contoh di atas menggunakan URL absolut (alamat web lengkap) pada hrefatributnya.
Tautan lokal (tautan ke halaman dalam situs web yang sama) ditentukan dengan URL relatif (tanpa bagian "https://www"):

```
<!DOCTYPE html>
<html>
<body>

<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>

</body>
</html>



```


![l2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/d409b1b6-6d5b-4eb2-9b26-6f2ff958c3d6)


Tautan HTML - Gunakan Gambar sebagai Tautan
Untuk menggunakan gambar sebagai link, cukup masukkan <img> tag ke dalam <a>tag:



```
<!DOCTYPE html>
<html>
<body>

<h2>Image as a Link</h2>

<p>The image below is a link. Try to click on it.</p>

<a href="default.asp"><img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;"></a>

</body>
</html>

```

![l3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/497a193a-6807-43d8-bc6e-69927285893e)



Tautan ke Alamat Email


Gunakan mailto:di dalam hrefatribut untuk membuat tautan yang membuka program email pengguna (agar mereka dapat mengirim email baru):


```
<!DOCTYPE html>
<html>
<body>

<h2>Link to an Email Address</h2>

<p>To create a link that opens in the user's email program (to let them send a new email), use mailto: inside the href attribute:</p>

<p><a href="mailto:someone@example.com">Send email</a></p>

</body>
</html>

```


![l4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/62653ce5-be81-482d-9982-1a0f10796723)


Tombol sebagai Tautan


Untuk menggunakan tombol HTML sebagai tautan, Anda harus menambahkan beberapa kode JavaScript.
JavaScript memungkinkan Anda menentukan apa yang terjadi pada peristiwa tertentu, seperti mengklik tombol:



```
<!DOCTYPE html>
<html>
<body>

<h2>Button as a Links</h2>

<p>Click the button to go to the HTML tutorial.</p>

<button onclick="document.location='default.asp'">HTML Tutorial</button>

</body>
</html>

```


![l5](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/f86da40b-814c-4596-b44b-56dded484b5d)



Judul Tautan


Atribut titlemenentukan informasi tambahan tentang suatu elemen. Informasi ini paling sering ditampilkan sebagai teks keterangan alat saat mouse bergerak di atas elemen.


```
<!DOCTYPE html>
<html lang="en-US">
<body>

<h2>Link Titles</h2>
<p>The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.</p>
<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>

</body>
</html>


```


![l6](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/3d37f116-f41f-4351-92dc-1a12c44d80b8)


Ringkasan Bab


- Gunakan <a>elemen untuk menentukan tautan
- Gunakan hrefatribut untuk menentukan alamat tautan
- Gunakan targetatribut untuk menentukan tempat membuka dokumen tertaut
- Gunakan <img>elemen (di dalam <a>) untuk menggunakan gambar sebagai tautan
- unakan mailto:skema di dalam hrefatribut untuk membuat tautan yang membuka program email pengguna


## Warna Tautan


Warna Tautan HTML



Secara default, tautan akan muncul seperti ini (di semua browser):
- Tautan yang belum dikunjungi digarisbawahi dan berwarna biru
- Tautan yang dikunjungi digarisbawahi dan berwarna ungu
- Tautan aktif digarisbawahi dan berwarna merah
Anda dapat mengubah warna status tautan dengan menggunakan CSS:


```
<!DOCTYPE html>
<html>
<head>
<style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}
a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}
a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}
a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>
</head>
<body>

<h2>Link Colors</h2>

<p>You can change the default colors of links</p>

<a href="html_images.asp" target="_blank">HTML Images</a> 

</body>
</html>

```


![lc1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/04ad2b14-ec6a-475e-ac34-389ebee1c3b7)



## Buat bookmark

Buat Bookmark dalam HTML


Bookmark dapat berguna jika halaman web sangat panjang.
Untuk membuat bookmark - pertama buat bookmark, lalu tambahkan link ke dalamnya.
Ketika tautan diklik, halaman akan bergulir ke bawah atau ke atas ke lokasi yang diberi bookmark.


```

<!DOCTYPE html>
<html>
<body>

<p><a href="#C4">Jump to Chapter 4</a></p>
<p><a href="#C10">Jump to Chapter 10</a></p>

<h2>Chapter 1</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 2</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 3</h2>
<p>This chapter explains ba bla bla</p>

<h2 id="C4">Chapter 4</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 5</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 6</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 7</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 8</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 9</h2>
<p>This chapter explains ba bla bla</p>

<h2 id="C10">Chapter 10</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 11</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 12</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 13</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 14</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 15</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 16</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 17</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 18</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 19</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 20</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 21</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 22</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 23</h2>
<p>This chapter explains ba bla bla</p>

</body>
</html>


```



![bm](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/c0d9ce75-13c3-4861-a3c3-46271d54d529)



## 9. HTML Imegs


Gambar dapat meningkatkan desain dan tampilan halaman web.



```
<!DOCTYPE html>
<html>
<body>

<h2>HTML Image</h2>
<img src="https://th.bing.com/th/id/OIP.oPBGac-MSBgqFlfDW7SBtAHaFP?w=241&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7" alt="Flowers in Chania" width="460" height="345">

</body>
</html>


```


![i1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/b2a5fb79-c64c-4472-a424-e6f27ce17f67)



Sintaks Gambar HTML



Tag HTML <img>digunakan untuk menyematkan gambar di halaman web.
Gambar secara teknis tidak dimasukkan ke dalam halaman web; gambar ditautkan ke halaman web. Tag <img>menciptakan ruang penahan untuk gambar yang direferensikan.
Tag <img>kosong, hanya berisi atribut, dan tidak memiliki tag penutup.
Tag <img>memiliki dua atribut wajib:
src - Menentukan jalur ke gambar
alt - Menentukan teks alternatif untuk gambar


Atribut src


Atribut yang diperlukan srcmenentukan jalur (URL) ke gambar.
Catatan: Saat halaman web dimuat, pada saat itulah browserlah yang mengambil gambar dari server web dan menyisipkannya ke halaman. Oleh karena itu, pastikan gambar tersebut benar-benar tetap berada di tempat yang sama dengan halaman web, jika tidak pengunjung Anda akan mendapatkan ikon tautan rusak. Ikon tautan rusak dan altteks ditampilkan jika browser tidak dapat menemukan gambar.


```
<!DOCTYPE html>
<html>
<body>

<h2>Alternative text</h2>

<p>The alt attribute should reflect the image content, so users who cannot see the image get an understanding of what the image contains:</p>

<img src="img_chania.jpg" alt="Flowers in Chania" width="460" height="345">

</body>
</html>


```

![i3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/3796f4e9-093f-43fc-a743-468b64251119)



Atribut alt


Atribut wajib altmenyediakan teks alternatif untuk gambar, jika pengguna karena alasan tertentu tidak dapat melihatnya (karena koneksi lambat, kesalahan pada atribut src, atau jika pengguna menggunakan pembaca layar).
Nilai atribut altharus mendeskripsikan gambar:


```
<!DOCTYPE html>
<html>
<body>

<p>If a browser cannot find the image, it will display the alternate text:</p>

<img src="wrongname.gif" alt="Flowers in Chania">

</body>
</html>


```



Ukuran Gambar - Lebar dan Tinggi


Anda dapat menggunakan styleatribut untuk menentukan lebar dan tinggi suatu gambar.



```
<!DOCTYPE html>
<html>
<body>

<h2>Image Size</h2>

<p>Here we specify the width and height of an image with the width and height attributes:</p>

<img src="https://th.bing.com/th/id/OIP.YH9LLg92G09J3KsgTU0pQwHaLH?w=115&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7" alt="Girl in a jacket" width="500" height="400">

</body>
</html>

```



![i4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/32d4f3a6-28ef-4953-b1e3-68771babb550)




Gambar sebagai Tautan


Untuk menggunakan gambar sebagai tautan, letakkan <img>tag di dalam <a> tag:


```

<!DOCTYPE html>
<html>
<body>

<h2>Image as a Link</h2>

<p>The image is a link. You can click on it.</p>

<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

</body>
</html>


```



![i5](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/06be24e4-515c-4190-9a36-1a6eb8dcb330)


## image Map




Peta Gambar



Tag HTML <map>mendefinisikan peta gambar. Peta gambar adalah gambar dengan area yang dapat diklik. Area ditentukan dengan satu atau lebih <area>tag.
Coba klik pada komputer, ponsel, atau secangkir kopi pada gambar di bawah ini:


```
<!DOCTYPE html>
<html>
<body>

<h2>Image Maps</h2>
<p>Click on the computer, the phone, or the cup of coffee to go to a new page and read more about the topic:</p>

<img src="workplace.jpg" alt="Workplace" usemap="#workmap" width="400" height="379">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
</map>

</body>
</html>
```


![pg1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/779cef80-8e41-4846-937c-e137481c9f1f)


Bagaimana cara kerjanya?


Ide dibalik peta gambar adalah Anda dapat melakukan tindakan yang berbeda-beda tergantung pada bagian gambar yang Anda klik.
Untuk membuat peta gambar, Anda memerlukan gambar, dan beberapa kode HTML yang menjelaskan area yang dapat diklik.



Foto


Gambar disisipkan menggunakan <img>tag. Satu-satunya perbedaan dari gambar lain adalah Anda harus menambahkan usemapatribut:


Buat Peta Gambar


Lalu, tambahkan <map>elemen.
Elemen ini <map>digunakan untuk membuat peta gambar, dan ditautkan ke gambar menggunakan name atribut yang diperlukan:


Area


Kemudian, tambahkan area yang dapat diklik.
Area yang dapat diklik ditentukan menggunakan <area>elemen.
Membentuk
Anda harus menentukan bentuk area yang dapat diklik, dan Anda dapat memilih salah satu dari nilai berikut:
rect- mendefinisikan wilayah persegi panjang
circle- mendefinisikan wilayah melingkar
poly- mendefinisikan wilayah poligonal
default- mendefinisikan seluruh wilayah
Anda juga harus menentukan beberapa koordinat untuk dapat menempatkan area yang dapat diklik pada gambar.


Bentuk = "lurus"


Koordinatnya shape="rect"berpasangan, satu untuk sumbu x dan satu lagi untuk sumbu y.
Jadi koordinatnya 34,44terletak 34 piksel dari margin kiri dan 44 piksel dari atas:


```
<!DOCTYPE html>
<html>
<body>

<h2>Image Maps</h2>
<p>Click on the computer to go to a new page and read more about the topic:</p>

<img src="https://th.bing.com/th/id/OIP.pDYQs58XUffTuIfJ562dxQHaEL?w=381&h=181&c=7&r=0&o=5&dpr=1.3&pid=1.7" alt="Workplace" usemap="#workmap" width="400" height="379">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
</map>

</body>
</html>


```

![pg2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/6809a296-93d9-40da-b01b-e31fdffbda25)




Bentuk = "lingkaran"


Untuk menambah luas lingkaran, cari dulu koordinat pusat lingkarannya:


```
<!DOCTYPE html>
<html>
<body>

<h2>Image Maps</h2>
<p>Click on the cup of coffee to go to a new page and read more about the topic:</p>

<img src="https://th.bing.com/th/id/OIP.DNmNmQ3pfktiJlqLFBvdQAHaE7?w=262&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7" alt="Workplace" usemap="#workmap" width="400" height="379">

<map name="workmap">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
</map>

</body>
</html>

```



![pg3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/80e33445-2b7a-48e5-8adc-f65487d4f011)


Bentuk = "poli"



Berisi shape="poly"beberapa titik koordinat, yang menghasilkan bentuk yang dibentuk dengan garis lurus (poligon).
Ini dapat digunakan untuk membuat bentuk apa pun.
Mungkin seperti bentuk croissant!
Bagaimana kita membuat croissant pada gambar di bawah ini menjadi link yang dapat diklik?


```
<!DOCTYPE html>
<html>
<body>

<h2>Image Maps</h2>
<p>Click on the croissant to go to a new page and read more about the topic:</p>

<img src="https://th.bing.com/th/id/OIP.NA_gDxM_in8-N2hOhfc_UwHaG6?w=175&h=186&c=7&r=0&o=5&dpr=1.3&pid=1.7" alt="French Food" usemap="#foodmap" width="450" height="405">

<map name="foodmap">
  <area shape="poly" coords="140,121,181,116,204,160,204,222,191,270,140,329,85,355,58,352,37,322,40,259,103,161,128,147" alt="Croissant" href="croissant.htm">
</map>

</body>
</html>

```


![pg4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/718d5f5e-90cb-42a4-a4aa-618ebf7511d5)




Ringkasan Bab


- Gunakan elemen HTML <map>untuk mendefinisikan peta gambar
- Gunakan elemen HTML <area>untuk menentukan area yang dapat diklik di peta gambar
- Gunakan atribut HTML usemapelemen <img>untuk menunjuk ke peta gambar




## Bacground Images


Gambar Latar Belakang pada elemen HTML


Untuk menambahkan gambar latar belakang pada elemen HTML, gunakan styleatribut HTML dan properti CSS background-image:


```
<!DOCTYPE html>
<html>
<head>
<style>
p {
  background-image: url('img_girl.jpg');
}
</style>
</head>
<body>

<h2>Background Image</h2>

<p>You can specify background images<br>
for any visible HTML element.<br>
In this example, the background image<br>
is specified for a div element.<br>
By default, the background-image<br>
will repeat itself in the direction(s)<br>
where it is smaller than the element<br>
where it is specified. (Try resizing the<br>
browser window to see how the<br>
background image behaves.</p>

</body>
</html>

```



![BI](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/640f4a37-bde0-4b25-b48d-0d359591a7c9)



Gambar Latar Belakang pada Halaman



Jika Anda ingin seluruh halaman memiliki gambar latar belakang, Anda harus menentukan gambar latar belakang pada <body>elemen:


```
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-image: url('https://th.bing.com/th?id=OIF.PQQh%2b0P6ML8ci%2f4DmvHjvg&w=280&h=186&c=7&r=0&o=5&dpr=1.3&pid=1.7');
}
</style>
</head>
<body>

<h2>Background Image</h2>

<p>By default, the background image will repeat itself if it is smaller than the element where it is specified, in this case the body element.</p>

</body>
</html>
```


![B2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/83c1db39-973a-4e38-b92d-bcfe2c533196)


Sampul Latar Belakang


Jika Anda ingin gambar latar belakang menutupi seluruh elemen, Anda dapat mengatur propertinya background-sizemenjadi cover.
Selain itu, untuk memastikan seluruh elemen selalu tertutup, atur propertinya background-attachmentmenjadifixed:
Dengan cara ini, gambar latar belakang akan menutupi seluruh elemen, tanpa peregangan (gambar akan mempertahankan proporsi aslinya):


```
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-image: url('https://th.bing.com/th/id/OIP.lu8CcUAS_UiIOr5v_TeePwHaEo?w=289&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7');
  background-repeat: no-repeat;
  background-attachment: fixed;  
  background-size: cover;
  
}
body {
	font-color: white;
    }
</style>
</head>
<body>

<h2>Background Cover</h2>

<p>Set the background-size property to "cover" and the background image will cover the entire element, in this case the body element.</p>

</body>
</html>

```




![B2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/8732a266-a380-4080-87a1-2a8829663b27)




Peregangan Latar Belakang


Jika Anda ingin gambar latar belakang diregangkan agar sesuai dengan seluruh elemen, Anda dapat mengatur propertinya background-sizemenjadi 100% 100%:



```
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-image: url('https://th.bing.com/th/id/OIP.XvZsnumh7kDRdObxJJWuwgHaDm?w=345&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7');
  background-repeat: no-repeat;
  background-attachment: fixed; 
  background-size: 100% 100%;
}
</style>
</head>
<body>

<h2>Background Stretch</h2>

<p>Set the background-size property to "100% 100%" and the background image will be stretched to cover the entire element, in this case the body element.</p>

</body>
</html>


```


![B4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/9c2f3f53-0ba2-42d4-8c20-1061e5b53738)


## 10. HTML Table


Tentukan Tabel HTML


Tabel dalam HTML terdiri dari sel-sel tabel di dalam baris dan kolom.


```
<!DOCTYPE html>
<html>
<style>
table, th, td {
  border:1px solid black;
}
</style>
<body>

<h2>A basic HTML table</h2>

<table style="width:100%">
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>

<p>To understand the example better, we have added borders to the table.</p>

</body>
</html>
```


![t1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/0a7d458f-b6ef-463e-8040-a629243290ab)



Sel Tabel


Setiap sel tabel ditentukan oleh a <td>dan </td>tag.
td singkatan dari data tabel.
Segala sesuatu di antara <td>dan </td>merupakan konten sel tabel.


```
<!DOCTYPE html>
<html>
<style>
table, th, td {
  border:1px solid black;
}
</style>
<body>

<h2>TD elements define table cells</h2>

<table style="width:100%">
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
</table>

<p>To understand the example better, we have added borders to the table.</p>

</body>
</html>

```


![t2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/8dd584aa-5dcf-43e8-a730-ac3db62cb266)


Baris Tabel



Setiap baris tabel dimulai dengan a <tr>dan diakhiri dengan </tr>tag.
tr singkatan dari baris tabel.


```
<!DOCTYPE html>
<html>
<style>
table, th, td {
  border:1px solid black;
}
</style>
<body>

<h2>tabel kematian</h2>

<table style="width:100%">
  <tr>
    <td>naga</td>
    <td>dinosaurus</td>
    <td>amoeba</td>
  </tr>
  <tr>
    <td>54</td>
    <td>154</td>
    <td>1065</td>
  </tr>
</table>

<p>To understand the example better, we have added borders to the table.</p>

</body>
</html>


```



![t3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/37a5ff7a-4ba1-4d02-ba6a-61fddde78c0d)



Header Tabel


Terkadang Anda ingin sel Anda menjadi sel header tabel. Dalam kasus tersebut, gunakan <th>tag alih-alih <td>tag:
th singkatan dari header tabel.


```
<!DOCTYPE html>
<html>
<style>
table, th, td {
  border:1px solid black;
}
</style>
<body>

<h2>TH elements define table headers</h2>

<table style="width:80%">
  <tr>
    <th>anis</th>
    <th>prabowo</th>
    <th>ganjar</th>
  </tr>
  <tr>
    <td>imin</td>
    <td>gibran</td>
    <td>mahfud</td>
  </tr>
  <tr>
    <td>43</td>
    <td>72</td>
    <td>45</td>
  </tr>
</table>

<p>To understand the example better, we have added borders to the table.</p>

</body>
</html>


```


![t4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/ce5cc3f1-fb05-4722-99f7-4798bc71c89c)




## Batas Table


Cara Menambahkan Perbatasan


Untuk menambahkan batas, gunakan borderproperti CSS pada table, th, dan tdelemen:


```
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<h2>Table With Border</h2>

<p>Use the CSS border property to add a border to the table.</p>

<table style="width:100%">
  <tr>
    <th>nama</th>
    <th>panggilan</th> 
    <th>umur</th>
  </tr>
  <tr>
    <td>juli</td>
    <td>agustus</td>
    <td>79</td>
  </tr>
  <tr>
    <td>maret</td>
    <td>april</td>
    <td>90</td>
  </tr>
  <tr>
    <td>octo</td>
    <td>doel</td>
    <td>887</td>
  </tr>
</table>

</body>
</html>
```


![t5](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/e0b720f4-0127-4f34-8755-b5f0aeba78f3)



Batas Tabel Runtuh


Untuk menghindari batas ganda seperti pada contoh di atas, atur border-collapse properti CSS menjadi collapse.
Hal ini akan membuat perbatasan tersebut runtuh menjadi satu perbatasan:

```
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
</style>
</head>
<body>

<h2>Collapsed Borders</h2>
<p>If you want the borders to collapse into one border, add the CSS border-collapse property.</p>

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

</body>
</html>


```



![t6](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/d768382f-3ef7-4bf2-bc3d-b407ec6bdca4)


Perbatasan Meja Bundar


Dengan border-radiusproperti, perbatasannya mendapat sudut membulat:


```
<!DOCTYPE html>
<html>
<head>
<style>
th, td {
  border: 1px solid black;
  border-radius: 10px;
}
</style>
</head>
<body>

<h2>Table With Rounded Borders</h2>

<p>Use the CSS border-radius property to add rounded corners to the table cells.</p>

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

</body>
</html>
```


![t7](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/43741644-6d5c-499b-a56c-fb6833850f66)


Batas Tabel Bertitik


Dengan border-styleproperti tersebut, Anda dapat mengatur tampilan border.


```
<!DOCTYPE html>
<html>
<head>
<style>
th, td {
  border-style: dotted;
}
</style>
</head>
<body>

<h2>Table With Dotted Borders</h2>

<p>Use the CSS border-style property to set the style of the borders.</p>

<table style="width:100%">
  <tr>
    <th>nama</th>
    <th>panggilan</th> 
    <th>usia</th>
  </tr>
  <tr>
    <td>alfa</td>
    <td>alpin</td>
    <td>34</td>
  </tr>
  <tr>
    <td>dimas</td>
    <td>hendra</td>
    <td>35</td>
  </tr>
  <tr>
    <td>kenan</td>
    <td>apin</td>
    <td>23</td>
  </tr>
</table>

</body>
</html>
```

![t8](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/9a8b27f1-1207-4d22-9a99-95b684645efa)



## Table Zize

HTML Table Width


To set the width of a table, add the style attribute to the <table> element:


```
<!DOCTYPE html>
<html>
<style>
table, th, td {
  border:5px solid black;
  border-collapse: collapse;
}
</style>

<body>

<h2>100% wide HTML Table</h2>

<table style="width: 60%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

</body>
</html>


```


![tz1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/e8874695-4d8f-426e-be1e-0bace093bca0)



HTML Table Column Width


To set the size of a specific column, add the style attribute on a <th> or <td> element:



```
<!DOCTYPE html>
<html>
<style>
table, th, td {
  border:2px solid black;
  border-collapse: collapse;
}
</style>
<body>

<h2>Set the first column to 70% of the table width</h2>

<table style="width:10%">
  <tr>
    <th style="width:90%">Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

</body>
</html>

```


![tz2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/2979c71c-82a7-4e31-9f87-ef272f11a987)


HTML Table Row Height


To set the height of a specific row, add the style attribute on a table row element:


```
<!DOCTYPE html>
<html>
<style>
table, th, td {
  border:2px dotted black;
  border-collapse: collapse;
}
</style>
<body>

<h2>Set the height of the second row to 200 pixels</h2>

<table style="width:80%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr style="height:140px">
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

</body>
</html>


```

![tz3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/b46c3b4a-b2fb-4f18-8c2c-8386b7911d9b)



## table pedding&spasi

Tabel HTML - Bantalan Sel


Cell padding adalah jarak antara tepi sel dan isi sel.
Secara default padding diatur ke 0.
Untuk menambahkan padding pada sel tabel, gunakan properti CSS padding:


```
<h2>Cellpadding - top - bottom - left - right </h2>
<p>We can specify different padding for all fours sides of the cell content.</p>

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>ahmad</td>
    <td>kurcai</td>
    <td>50</td>
  </tr>
  <tr>
    <td>nurulll</td>
    <td>adi</td>
    <td>94</td>
  </tr>
  <tr>
    <td>riko</td>
    <td>rido</td>
    <td>80</td>
  </tr>
</table>

</body>
</html>

```



![tp1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/0104692c-5ff8-45e3-86dc-0312aae92556)


Tabel HTML - Spasi Sel


Jarak sel adalah jarak antar sel.
Secara default, spasi diatur ke 2 piksel.
Untuk mengubah spasi antar sel tabel, gunakan border-spacingproperti CSS pada table elemen:


```
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
}
table {
  border-spacing: 30px;
}
</style>
</head>
<body>

<h2>Cellspacing</h2>
<p>Change the space between the cells with the border-spacing property.</p>

<table style="width:90%">
  <tr>
    <th>nama</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>arya</td>
    <td>dimas</td>
    <td>50</td>
  </tr>
  <tr>
    <td>revano</td>
    <td>arfilal</td>
    <td>94</td>
  </tr>
  <tr>
    <td>jamal</td>
    <td>nyong</td>
    <td>80</td>
  </tr>
</table>

</body>
</html>


```


![tp2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/04767808-29fc-4848-911c-d94343b6fe84)


## table colwspen rowspend


Tabel HTML - Colspan
Untuk membuat sel menjangkau beberapa kolom, gunakan colspanatribut:


```
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 2px solid black;
  border-collapse: collapse;
}
</style>
</head>
<body>

<h2>Cell that spans two columns</h2>
<p>To make a cell span more than one column, use the colspan attribute.</p>

<table style="width:60%">
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>43</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>57</td>
  </tr>
</table>
</body>
</html>


```



![tr1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/b2c9b97f-9ae0-4a95-8853-2a71c0d56b2d)


Tabel HTML - Rentang Baris


Untuk membuat sel menjangkau beberapa baris, gunakan rowspanatribut:


```
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
</style>
</head>
<body>

<h2>Cell that spans two rows</h2>
<p>To make a cell span more than one row, use the rowspan attribute.</p>

<table style="width:80%">
  <tr>
    <th>Name</th>
    <td>Jill</td>
  </tr>
  <tr>
    <th rowspan="2">Phone</th>
    <td>555-1234</td>
  </tr>
  <tr>
    <td>555-8745</td>
  </tr>
</table>
</body>
</html>

```


![tr2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/e762454a-482e-42a8-9611-7f9aac92fd21)


## Table Styeling


Tabel HTML - Garis Zebra



Jika Anda menambahkan warna latar belakang pada setiap baris tabel lainnya, Anda akan mendapatkan efek garis zebra yang bagus.


```
<!DOCTYPE html>
<html>
<head>
<style>
table {
  border-collapse: collapse;
  width: 80%;
}

th, td {
  text-align: left;
  padding: 11px;
}

tr:nth-child(even) {
  background-color: #D6EEEE;
}
</style>
</head>
<body>

<h2>Zebra Striped Table</h2>
<p>For zebra-striped tables, use the nth-child() selector and add a background-color to all even (or odd) table rows:</p>

<table>
  <tr>
  <th>First Name</th>
  <th>Last Name</th>
  <th>Points</th>
  </tr>
  <tr>
  <td>Peter</td>
  <td>Griffin</td>
  <td>$100</td>
  </tr>
  <tr>
  <td>Lois</td>
  <td>Griffin</td>
  <td>$150</td>
  </tr>
  <tr>
  <td>Joe</td>
  <td>Swanson</td>
  <td>$300</td>
  </tr>
  <tr>
  <td>Cleveland</td>
  <td>Brown</td>
  <td>$250</td>
  </tr>
</table>

</body>
</html>
```



![ts1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/255e1b15-555b-4738-8f19-121383fd7684)



Tabel HTML - Garis Zebra Vertikal



Untuk membuat garis zebra vertikal, beri gaya pada setiap kolom lainnya , bukan setiap baris lainnya .


``<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 3px solid black;
  border-collapse: collapse;
}

th:nth-child(even),td:nth-child(even) {
  background-color: #D6EEEE;
}
</style>
</head>
<body>

<h2>Striped Table</h2>


<p>For zebra-striped tables, use the nth-child() selector and add a background-color to all even (or odd) table rows:</p>



```
<table style="width:100%">
  <tr>
    <th>MON</th>
    <th>TUE</th>
    <th>WED</th>
    <th>THU</th>
    <th>FRI</th>
    <th>SAT</th>
    <th>SUN</th>
  </tr>
  <tr>
    <td>ce </td>
    <td>fe </td>
    <td>gr </td>
    <td>yj </td>
    <td>ry </td>
    <td>sf </td>
    <td>af </td>
  </tr>
  <tr>
    <td>ef </td>
    <td>aa </td>
    <td>cs </td>
    <td>ge </td>
    <td>ku </td>
    <td>rt </td>
    <td>jr </td>
  </tr>
  <tr>
    <td>er </td>
    <td>fw </td>
    <td>ve </td>
    <td>he </td>
    <td>jt </td>
    <td>li </td>
    <td>yn </td>
  </tr>
  <tr>
    <td>eh </td>
    <td>09 </td>
    <td>jt </td>
    <td>ah </td>
    <td>5h </td>
    <td>hr </td>
    <td>jt </td>
  </tr>
</table>

</body>
</html>





```


![ts2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/e8bbb84e-656a-4089-87f3-f467b537a1f4)



Gabungkan Garis Zebra Vertikal dan Horisontal



Anda dapat menggabungkan gaya dari dua contoh di atas dan Anda akan memiliki garis-garis di setiap baris dan kolom lainnya.
Jika Anda menggunakan warna transparan, Anda akan mendapatkan efek yang tumpang tindih.
Gunakan rgba()warna untuk menentukan transparansi warna:


```
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}

tr:nth-child(even) {
  background-color: rgba(150, 212, 212, 0.4);
}

th:nth-child(even),td:nth-child(even) {
  background-color: rgba(150, 212, 212, 0.4);
}
</style>
</head>
<body>

<h2>Striped Table</h2>
<p>For zebra-striped tables, use the nth-child() selector and add a background-color to all even (or odd) table rows:</p>

<table style="width:100%">
  <tr>
    <th>MON</th>
    <th>TUE</th>
    <th>WED</th>
    <th>THU</th>
    <th>FRI</th>
    <th>SAT</th>
    <th>SUN</th>
  </tr>
  <tr>
    <td>erg </td>
    <td>wf </td>
    <td>heh </td>
    <td>hte </td>
    <td>wfwe </td>
    <td> wg</td>
    <td>hwrh </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td>
    <td> </td>
    <td> </td>
    <td> </td>
    <td> </td>
    <td> </td>
  </tr>
  <tr>
    <td>wrg53 </td>
    <td>wgvd </td>
    <td>wg </td>
    <td>gwegwg </td>
    <td> fwfv</td>
    <td>geg </td>
    <td>gweg </td>
  </tr>
  <tr>
    <td>gweg </td>
    <td> gw</td>
    <td>wg </td>
    <td> vwe</td>
    <td>fwef </td>
    <td>fwe </td>
    <td>ew </td>
  </tr>
</table>

</body>
</html>
```


![ts3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/bc623a73-a923-41dd-b868-5f611d20db55)



Tabel Melayang




Gunakan :hoverpemilih truntuk menyorot baris tabel dengan mengarahkan mouse:



```
<!DOCTYPE html>
<html>
<head>
<style>
table {
  border-collapse: collapse;
  width: 70%;
}

th, td {
  padding: 10px;
  text-align: left;
  border-bottom: 3px solid #DDD;
}

tr:hover {background-color: #D6EEEE;}
</style>
</head>
<body>

<h2>Hoverable Table</h2>
<p>Move the mouse over the table rows to see the effect.</p>

<table>
  <tr>
    <th>First Name</th>
    <th>Last Name</th>
    <th>Points</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
    <td>$150</td>
  </tr>
  <tr>
    <td>Joe</td>
    <td>Swanson</td>
    <td>$300</td>
  </tr>
  <tr>
    <td>Cleveland</td>
    <td>Brown</td>
    <td>$250</td>
  </tr>
</table>

</body>
</html>
```


![ts5](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/1d6d2ba2-c8ed-4cde-8980-364522280ff6)




## 11. HTML List

Daftar HTML memungkinkan pengembang web mengelompokkan sekumpulan item terkait dalam daftar.


```
<!DOCTYPE html>
<html>
<body>

<h2>An Unordered HTML List</h2>

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>  

<h2>An Ordered HTML List</h2>

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol> 

</body>
</html>

```


![l1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/2ed68ab1-2d05-4999-910a-5f6178555fa3)


Daftar HTML Tidak Berurutan


Daftar tidak berurutan dimulai dengan <ul>tag. Setiap item daftar dimulai dengan <li>tag.
Item daftar akan ditandai dengan poin (lingkaran hitam kecil) secara default:


```
<!DOCTYPE html>
<html>
<body>

<h2>An unordered HTML list</h2>

<ul>
  <li>cengkeh</li>
  <li>rambutan</li>
  <li>ikan</li>
</ul>  

</body>
</html>


```


![l2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/29ef7cbc-2fe3-440a-ad68-ac83dbb02759)


Daftar HTML yang dipesan



Daftar yang diurutkan dimulai dengan <ol>tag. Setiap item daftar dimulai dengan <li>tag.
Item daftar akan ditandai dengan angka secara default:


```
<!DOCTYPE html>
<html>
<body>

<h2>An ordered HTML list</h2>

<ol>
  <li>barca</li>
  <li>madrid</li>
  <li>liverpool</li>
</ol>  

</body>
</html>


```


![l3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/b4522906-434a-4645-b4de-a34c41640650)



Daftar Deskripsi HTML


HTML juga mendukung daftar deskripsi.
Daftar deskripsi adalah daftar istilah, dengan deskripsi setiap istilah.
Tag <dl>mendefinisikan daftar deskripsi, <dt>tag mendefinisikan istilah (nama), dan <dd> tag menjelaskan setiap istilah:


```
<!DOCTYPE html>
<html>
<body>

<h2>A Description List</h2>

<dl>
  <dt>makanan</dt>
  <dd>roti cana</dd>
  <dt>minuman</dt>
  <dd>florida</dd>
</dl>

</body>
</html>
```


![l4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/803cab83-49b9-4247-a174-1ce4e6e163dc)


## List Tidak Berurutan

Daftar HTML Tidak Berurutan


Daftar tidak berurutan dimulai dengan <ul>tag. Setiap item daftar dimulai dengan <li>tag.
Item daftar akan ditandai dengan poin (lingkaran hitam kecil) secara default:

```
<!DOCTYPE html>
<html>
<body>

<h2>An unordered HTML list</h2>

<ul>
  <li>ehe</li>
  <li>gpoergj</li>
  <li>ojngoreg</li>
</ul>  

</body>
</html>
```


![lu1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/ee9b1dec-0b38-4b19-94f6-6de12d8a9546)


Daftar HTML Tidak Berurutan - Pilih Penanda Item Daftar
Properti CSS list-style-typedigunakan untuk menentukan gaya penanda item daftar. Itu dapat memiliki salah satu dari nilai berikut:

```
<!DOCTYPE html>
<html>
<body>

<h2>Unordered List without Bullets</h2>

<ul style="list-style-type:none;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>  

</body>
</html>


```


![lu2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/9f0aa3f5-2b52-4d95-a97e-b49771923653)



Daftar HTML Bersarang


Daftar dapat disarangkan (daftar di dalam daftar):

```
<!DOCTYPE html>
<html>
<body>

<h2>A Nested List</h2>
<p>Lists can be nested (list inside list):</p>

<ul>
  <li>Coffee</li>
  <li>Tea
    <ol>
      <li>Black tea</li>
      <li>Green tea</li>
    </ol>
  </li>
  <li>Milk</li>
</ul>

</body>
</html>


```


![lu3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/730c7574-c5ae-4327-92b8-68a33ecfb770)



Daftar Horisontal dengan CSS


Daftar HTML dapat ditata dengan berbagai cara dengan CSS.
Salah satu cara yang populer adalah menata daftar secara horizontal, untuk membuat menu navigasi:


```
<!DOCTYPE html>
<html>
<head>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111111;
}
</style>
</head>
<body>

<h2>Navigation Menu</h2>
<p>In this example, we use CSS to style the list horizontally, to create a navigation menu:</p>

<ul>
  <li><a href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>

</body>
</html>
```


![lu4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/fcca07ac-fad1-4c73-af67-352f83744100)


## List Order

Ordered HTML List


An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.
The list items will be marked with numbers by default:


```
<!DOCTYPE html>
<html>
<body>

<h2>An ordered HTML list</h2>

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>  

</body>
</html>


```


![lo1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/29efe534-0632-4b04-addd-0c86824d05ae)


Ordered HTML List - The Type Attribute



The type attribute of the <ol> tag, defines the type of the list item marker:


```
<!DOCTYPE html>
<html>
<body>

<h2>Ordered List with Lowercase Roman Numbers</h2>

<ol type="i">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>  

</body>
</html>

```

![lo2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/fedfb3e2-2951-4754-8ea6-c4b594029338)


Control List Counting


By default, an ordered list will start counting from 1. If you want to start counting from a specified number, you can use the start attribute:


```
<!DOCTYPE html>
<html>
<body>

<h2>The start attribute</h2>
<p>By default, an ordered list will start counting from 1. Use the start attribute to start counting from a specified number:</p>

<ol start="50">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<ol type="I" start="50">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

</body>
</html>

```


![lo3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/cbe75074-b4ce-4377-a938-d782e617f745)



Nested HTML Lists


Lists can be nested (list inside list):


```
<!DOCTYPE html>
<html>
<body>

<h2>A Nested List</h2>
<p>Lists can be nested (list inside list):</p>

<ol>
  <li>Coffee</li>
  <li>Tea
    <ol>
      <li>Black tea</li>
      <li>Green tea</li>
    </ol>
  </li>
  <li>Milk</li>
</ol>

</body>
</html>

```


![lo4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/f8cf284f-0b3a-486d-9971-79d100a7454e)


Ringkasan Bab


- Gunakan elemen HTML <ol>untuk menentukan daftar yang diurutkan
- Gunakan atribut HTML typeuntuk menentukan tipe penomoran
- Gunakan elemen HTML <li>untuk mendefinisikan item daftar
- Daftar dapat disarangkan
- Item daftar dapat berisi elemen HTML lainnya


## List Lainya


Daftar Deskripsi HTML


Daftar deskripsi adalah daftar istilah, dengan deskripsi setiap istilah.
Tag <dl>mendefinisikan daftar deskripsi, tag mendefinisikan istilah (nama), dan tag menjelaskan setiap istilah: <dt> <dd>


```
<!DOCTYPE html>
<html>
<body>

<h2>njajal</h2>

<dl>
  <dt>Copy</dt>
  <dd>- mumet</dd>
  <dt>susu</dt>
  <dd>- jos</dd>
</dl>

</body>
</html>


```

![oll1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/3203ee00-23ca-4852-b1d7-20d05dbec47a)


Ringkasan Bab
Gunakan elemen HTML <dl>untuk menentukan daftar deskripsi
Gunakan elemen HTML <dt>untuk menentukan istilah deskripsi
Gunakan elemen HTML <dd>untuk mendeskripsikan istilah dalam daftar deskripsi



## 12. HTML Div



Elemen <div>


Elemen ini <div>secara default adalah elemen blok, artinya elemen ini mengambil semua lebar yang tersedia, dan dilengkapi dengan jeda baris sebelum dan sesudahnya.


<div> sebagai wadah

 
Elemen ini <div>sering digunakan untuk mengelompokkan bagian-bagian halaman web menjadi satu.

```
<!DOCTYPE html>
<html>
<style>
div {
  background-color: #FFF4A3;
}
</style>
<body>

<h1>HTML DIV Example</h1>

<div>
  <h2>London</h2>
  <p>London is the capital city of England.</p>
  <p>London has over 13 million inhabitants.</p>
</div>

<p>The yellow background is added to demonstrate the footprint of the DIV element.</p>

</body>
</html>
```

![image](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/9861b2ce-f8c1-4959-9616-9b3b5654cde1)



Ratakan tengah elemen <div>


Jika Anda memiliki <div>elemen yang lebarnya tidak 100%, dan Anda ingin meratakannya di tengah, setel marginproperti CSS ke auto

```
<!DOCTYPE html>
<html>
<style>
div {
  width: 300px;
  margin: auto;
  background-color: #FFF4A3;
}
</style>
<body>

<h1>Center align a DIV element</h1>

<div>
  <h2>London</h2>
  <p>London is the capital city of England.</p>
  <p>London has over 13 million inhabitants.</p>
</div>

</body>
</html>
```


![d2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/dad34fbf-fb63-44af-a52d-a5488599c8c5)


Beberapa elemen <div>


Anda dapat memiliki banyak <div>container di halaman yang sama.

```
<!DOCTYPE html>
<html>
<body>

<h1>Multiple DIV Elements</h1>

<div style="background-color:#FFF4A3;">
  <h2>London</h2>
  <p>London is the capital city of England.</p>
  <p>London has over 13 million inhabitants.</p>
</div>

<div style="background-color:#FFC0C7;">
  <h2>Oslo</h2>
  <p>Oslo is the capital city of Norway.</p>
  <p>Oslo has over 600.000 inhabitants.</p>
</div>

<div style="background-color:#D9EEE1;">
  <h2>Rome</h2>
  <p>Rome is the capital city of Italy.</p>
  <p>Rome has almost 3 million inhabitants.</p>
</div>

<p>CSS styles are added to make it easier to separate the divs, and to make them more pretty:)</p>

</body>
</html>

```


![D3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/20a2aef8-38b8-4104-8586-7b8a6f5565f1)


Mengambang


Properti CSS floatawalnya tidak dimaksudkan untuk menyelaraskan <div>elemen secara berdampingan, namun telah digunakan untuk tujuan ini selama bertahun-tahun.
Properti CSS floatdigunakan untuk memposisikan dan memformat konten serta memungkinkan elemen melayang bersebelahan, bukan di atas satu sama lain.

```
<!DOCTYPE html>
<html>
<style>
div.mycontainer {
  width:100%;
  overflow:auto;
}
div.mycontainer div {
  width:33%;  
  float:left;
}
</style>
<body>

<div class="mycontainer">

  <div style="background-color:#FFF4A3;">
    <h2>London</h2>
    <p>London is the capital city of England.</p>
    <p>London has over 13 million inhabitants.</p>
  </div>
  
  <div style="background-color:#FFC0C7;">
    <h2>Oslo</h2>
    <p>Oslo is the capital city of Norway.</p>
    <p>Oslo has over 600.000 inhabitants.</p>
  </div>
  
  <div style="background-color:#D9EEE1;">
    <h2>Rome</h2>
    <p>Rome is the capital city of Italy.</p>
    <p>Rome has almost 3 million inhabitants.</p>
  </div>

</div>

</body>
</html>

```



![d4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/11185f01-a087-4675-a265-19e9e6328c66)


Blok sebaris


Jika Anda mengubah properti <div>elemen displaydari blockmenjadi inline-block, <div>elemen tidak akan lagi menambahkan jeda baris sebelum dan sesudahnya, dan akan ditampilkan berdampingan, bukan di atas satu sama lain.



```
<!DOCTYPE html>
<html>
<style>
div {
  width:30%;  
  display:inline-block;
}
</style>
<body>

<div style="background-color:#FFF4A3;">
  <h2>London</h2>
  <p>London is the capital city of England.</p>
  <p>London has over 13 million inhabitants.</p>
</div>

<div style="background-color:#FFC0C7;">
  <h2>Oslo</h2>
  <p>Oslo is the capital city of Norway.</p>
  <p>Oslo has over 600.000 inhabitants.</p>
</div>

<div style="background-color:#D9EEE1;">
  <h2>Rome</h2>
  <p>Rome is the capital city of Italy.</p>
  <p>Rome has almost 3 million inhabitants.</p>
</div>

</body>
</html>


```


![d5](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/a095382b-6ff8-451d-badb-d3ea8b05c4f3)


Melenturkan


Modul Tata Letak CSS Flexbox diperkenalkan untuk memudahkan merancang struktur tata letak responsif yang fleksibel tanpa menggunakan float atau positioning.
Agar metode fleksibel CSS berfungsi, kelilingi <div>elemen dengan <div>elemen lain dan berikan status sebagai wadah fleksibel.



```
<!DOCTYPE html>
<html>
<head>
<style>
.mycontainer {
  display: flex;
}
.mycontainer > div {
  width:33%;
}
</style>
</head>
<body>

<h1>Flexbox Example</h1>

<p>Align three DIV elements side by side.</p>

<div class="mycontainer">

  <div style="background-color:#FFF4A3;">
    <h2>London</h2>
    <p>London is the capital city of England.</p>
    <p>London has over 13 million inhabitants.</p>
  </div>
  
  <div style="background-color:#FFC0C7;">
    <h2>Oslo</h2>
    <p>Oslo is the capital city of Norway.</p>
    <p>Oslo has over 600.000 inhabitants.</p>
  </div>
  
  <div style="background-color:#D9EEE1;">
    <h2>Rome</h2>
    <p>Rome is the capital city of Italy.</p>
    <p>Rome has almost 3 million.</p>
  </div>

</div>

</body>
</html>

```


![d6](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/8816b57c-3497-473c-ace9-bedc1ca1ef82)


jaringan


Modul Tata Letak Grid CSS menawarkan sistem tata letak berbasis grid, dengan baris dan kolom, sehingga memudahkan mendesain halaman web tanpa harus menggunakan float dan positioning.
Kedengarannya hampir sama dengan flex, namun memiliki kemampuan untuk menentukan lebih dari satu baris dan memposisikan setiap baris secara individual.
Metode grid CSS mengharuskan Anda mengelilingi <div>elemen dengan <div>elemen lain dan memberikan status sebagai wadah grid, dan Anda harus menentukan lebar setiap kolom.



```
<!DOCTYPE html>
<html>
<head>
<style>
.grid-container {
  display: grid;
  grid-template-columns: 33% 33% 33%;
}
</style>
</head>
<body>

<h1>Grid Example</h1>

<p>Align three DIV elements side by side.</p>

<div class="grid-container">

<div style="background-color:#FFF4A3;">
  <h2>London</h2>
  <p>London is the capital city of England.</p>
  <p>London has over 13 million inhabitants.</p>
</div>

<div style="background-color:#FFC0C7;">
  <h2>Oslo</h2>
  <p>Oslo is the capital city of Norway.</p>
  <p>Oslo has over 600.000 inhabitants.</p>
</div>

<div style="background-color:#D9EEE1;">
  <h2>Rome</h2>
  <p>Rome is the capital city of Italy.</p>
  <p>Rome has almost 3 million inhabitants.</p>
</div>

</div>

</body>
</html>



```


![d7](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/daf5c79b-afc0-405b-99bb-038daf2c14cc)


## 13. Classes

Menggunakan Atribut kelas


Atribut ini classsering digunakan untuk menunjuk ke nama kelas dalam style sheet. Itu juga dapat digunakan oleh JavaScript untuk mengakses dan memanipulasi elemen dengan nama kelas tertentu.
Pada contoh berikut kita memiliki tiga <div>elemen dengan classatribut bernilai "kota". Ketiga <div> elemen tersebut akan diberi gaya yang sama sesuai dengan .city definisi gaya di bagian kepala:


```
<!DOCTYPE html>
<html>
<head>
<style>
.city {
  background-color: pink;
  color: white;
  border: 2px solid black;
  margin: 20px;
  padding: 20px;
}
</style>
</head>
<body>

<div class="city">
<h2>London</h2>
<p>London is the capital of England.</p>
</div> 

<div class="city">
<h2>Paris</h2>
<p>Paris is the capital of France.</p>
</div>

<div class="city">
<h2>Tokyo</h2>
<p>Tokyo is the capital of Japan.</p>
</div>

</body>
</html>


```


![c1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/211e5844-15c0-4b9b-a8d8-ab299d762010)


Sintaks Untuk Kelas


Untuk membuat kelas; tulis karakter titik (.), diikuti dengan nama kelas. Lalu, definisikan properti CSS di dalam kurung kurawal {}:


```
<!DOCTYPE html>
<html>
<head>
<style>
.city {
  background-color: green;
  color: white;
  padding: 10px;
}
</style>
</head>
<body>

<h2>The class Attribute</h2>
<p>Use CSS to style elements with the class name "city":</p>

<h2 class="city">Cilacap</h2>
<p>Cilacap is the capital of Jawa tengah.</p>

<h2 class="city">motean</h2>
<p>motean is the capital of Jawa jawa.</p>

<h2 class="city">Purwokerto</h2>
<p>purwokerto is the capital of Jawa suriname.</p>

</body>
</html>


```


![c2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/5867ac35-fa44-4351-b88f-0c5cc6e15579)

Beberapa Kelas


Elemen HTML dapat dimiliki lebih dari satu kelas.
Untuk mendefinisikan beberapa kelas, pisahkan nama kelas dengan spasi, misalnya <div class="city main">. Elemen akan ditata sesuai dengan semua kelas yang ditentukan.
Dalam contoh berikut, <h2>elemen pertama adalah milik kelas citydan juga milik mainkelas tersebut, dan akan mendapatkan gaya CSS dari kedua kelas: 


```
<!DOCTYPE html>
<html>
<head>
<style>
.city {
  background-color: tomato;
  color: white;
  padding: 10px;
} 

.main {
  text-align: center;
}
</style>
</head>
<body>

<h2>Multiple Classes</h2>
<p>Here, all three h2 elements belongs to the "city" class. In addition, London also belongs to the "main" class, which center-aligns the text.</p>

<h2 class="city main">London</h2>
<h2 class="city">Paris</h2>
<h2 class="city">Tokyo</h2>

</body>
</html>

```

![c3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/ec626ff4-c2a0-4a1b-807c-c88f39cb65c4)


Elemen Berbeda Dapat Berbagi Kelas yang Sama


Elemen HTML yang berbeda dapat menunjuk ke nama kelas yang sama.
Dalam contoh berikut, keduanya <h2>menunjuk <p> ke kelas "kota" dan akan berbagi gaya yang sama:


```
<!DOCTYPE html>
<html>
<head>
<style>
.city {
  background-color: tomato;
  color: white;
  padding: 10px;
} 
</style>
</head>
<body>

<h2>Different Elements Can Share Same Class</h2>

<p>Even if the two elements do not have the same tag name, they can both point to the same class, and get the same CSS styling:</p>

<h2 class="city">Paris</h2>
<p class="city">Paris is the capital of France.</p>

</body>
</html>

```


![c4](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/ae93bd8c-90ad-4be1-b5a7-d504c335b150)



Ringkasan Bab


- Atribut HTML classmenentukan satu atau lebih nama kelas untuk suatu elemen
- Kelas digunakan oleh CSS dan JavaScript untuk memilih dan mengakses elemen tertentu
- Atribut ini classdapat digunakan pada elemen HTML apa pun
- Nama kelas peka huruf besar-kecil
- Elemen HTML yang berbeda dapat menunjuk ke nama kelas yang sama
- JavaScript dapat mengakses elemen dengan nama kelas tertentu dengan getElementsByClassName() metode tersebut


## 14. Id


Menggunakan Atribut id


Atribut idmenentukan id unik untuk elemen HTML. Nilai atribut id harus unik dalam dokumen HTML.
Atribut iddigunakan untuk menunjuk ke deklarasi gaya tertentu dalam style sheet. Itu juga digunakan oleh JavaScript untuk mengakses dan memanipulasi elemen dengan id tertentu.
Sintaks untuk id adalah: tulis karakter hash (#), diikuti dengan nama id. Lalu, definisikan properti CSS di dalam kurung kurawal {}.
Dalam contoh berikut kita memiliki <h1>elemen yang menunjuk ke nama id "myHeader". Elemen ini <h1> akan ditata sesuai dengan #myHeader definisi gaya di bagian kepala:



```
<!DOCTYPE html>
<html>
<head>
<style>
#myHeader {
  background-color: red;
  color: black;
  padding: 40px;
  text-align: center;
} 
</style>
</head>
<body>

<h2>The id Attribute</h2>
<p>Use CSS to style an element with the id "mykepala":</p>

<h1 id="myHeader">My kepala</h1>

</body>
</html>


```



![id1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/23d69ff6-06f8-48ff-81f3-b5611c34962c)




Perbedaan Antara Kelas dan ID


Nama kelas dapat digunakan oleh beberapa elemen HTML, sedangkan nama id hanya boleh digunakan oleh satu elemen HTML dalam halaman:


```
<!DOCTYPE html>
<html>
<head>
<style>
/* Style the element with the id "myHeader" */
#myHeader {
  background-color: green;
  color: black;
  padding: 40px;
  text-align: center;
}

/* Style all elements with the class name "city" */
.city {
  background-color: brown;
  color: white;
  padding: 10px;
} 
</style>
</head>
<body>

<h2>Difference Between Class and ID</h2>
<p>A class name can be used by multiple HTML elements, while an id name must only be used by one HTML element within the page:</p>

<!-- An element with a unique id -->
<h1 id="myHeader">kucing</h1>

<!-- Multiple elements with same class -->
<h2 class="city">belanda</h2>
<p>London is the capital of England.</p>

<h2 class="city">Paris</h2>
<p>Paris is the capital of France.</p>

<h2 class="city">Tokyo</h2>
<p>Tokyo is the capital of Japan.</p>

</body>
</html>
```

![i1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/5d00018f-a65f-4e01-95d3-345f2f7dfc1e)



Bookmark HTML dengan ID dan Tautan


Bookmark HTML digunakan untuk memungkinkan pembaca melompat ke bagian tertentu dari halaman web.
Bookmark dapat berguna jika halaman Anda sangat panjang.
Untuk menggunakan bookmark, Anda harus membuatnya terlebih dahulu, lalu menambahkan link ke bookmark tersebut.
Kemudian, ketika link tersebut diklik, halaman tersebut akan bergulir ke lokasi yang diberi bookmark.


```
<!DOCTYPE html>
<html>
<body>

<p><a href="#C4">Jump to Chapter 4</a></p>
<p><a href="#C10">Jump to Chapter 10</a></p>

<h2>Chapter 1</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 2</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 3</h2>
<p>This chapter explains ba bla bla</p>

<h2 id="C4">Chapter 4</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 5</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 6</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 7</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 8</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 9</h2>
<p>This chapter explains ba bla bla</p>

<h2 id="C10">Chapter 10</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 11</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 12</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 13</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 14</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 15</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 16</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 17</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 18</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 19</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 20</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 21</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 22</h2>
<p>This chapter explains ba bla bla</p>

<h2>Chapter 23</h2>
<p>This chapter explains ba bla bla</p>

</body>
</html>


```


![i2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/e48c44a3-b5f6-40cf-afb8-f0f11145f9b8)



Menggunakan Atribut id dalam JavaScript


Atribut idjuga dapat digunakan oleh JavaScript untuk melakukan beberapa tugas untuk elemen tertentu.
JavaScript dapat mengakses elemen dengan id tertentu dengan getElementById()metode:


```
<!DOCTYPE html>
<html>
<body>

<h2>Using The id Attribute in JavaScript</h2>
<p>JavaScript can access an element with a specified id by using the getElementById() method:</p>

<h1 id="myHeader">Hello World!</h1>
<button onclick="displayResult()">Change text</button>

<script>
function displayResult() {
  document.getElementById("myHeader").innerHTML = "Have a nice day!";
}
</script>

</body>
</html>


```


![it](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/b1b99fea-cb4f-47fc-8056-78b5d7b38910)



Ringkasan Bab


- Atribut iddigunakan untuk menentukan id unik untuk elemen HTML
- Nilai atribut id harus unik dalam dokumen HTML
- Atribut ini id digunakan oleh CSS dan JavaScript untuk menata/memilih elemen tertentu
- Nilai atribut id peka huruf besar-kecil
- Atribut ini id juga digunakan untuk membuat bookmark HTML
- JavaScript dapat mengakses elemen dengan id tertentu dengan getElementById() metode ini



## 15. HTML JavaScript

The HTML <script> Tag


The HTML <script> tag is used to define a client-side script (JavaScript).
The <script> element either contains script statements, or it points to an external script file through the src attribute.
Common uses for JavaScript are image manipulation, form validation, and dynamic changes of content.
To select an HTML element, JavaScript most often uses the document.getElementById() method.
This JavaScript example writes "Hello JavaScript!" into an HTML element with id="demo":


```
<!DOCTYPE html>
<html>
<body>

<h2>Use JavaScript to Change Text</h2>
<p>This example writes "Hello JavaScript!" into an HTML element with id="demo":</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script> 

</body>
</html>
```


![j1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/bcb92a54-acac-4f37-9685-c0c754ac2499)


A Taste of JavaScript


Here are some examples of what JavaScript can do:


```
<!DOCTYPE html>
<html>
<body>

<h1>My First JavaScript</h1>
<p>Here, a JavaScript changes the value of the src (source) attribute of an image.</p>

<script>
function light(sw) {
  var pic;
  if (sw == 0) {
    pic = "pic_bulboff.gif"
  } else {
    pic = "pic_bulbon.gif"
  }
  document.getElementById('myImage').src = pic;
}
</script>

<img id="myImage" src="pic_bulboff.gif" width="100" height="180">

<p>
<button type="button" onclick="light(1)">Light On</button>
<button type="button" onclick="light(0)">Light Off</button>
</p>

</body>
</html>


```



![j2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/285cbe8a-faf6-4a79-8541-bd2d02dbf330)



The HTML <noscript> Tag


The HTML <noscript> tag defines an alternate content to be displayed to users that have disabled scripts in their browser or have a browser that doesn't support scripts:


```
<!DOCTYPE html>
<html>
<body>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script>

<noscript>Sorry, your browser does not support JavaScript!</noscript>

<p>A browser without support for JavaScript will show the text written inside the noscript element.</p>
 
</body>
</html>
```


![j3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/172340fc-5ee3-401d-bc81-26ec73a38dbe)


## CSS


## 1. CSS Interduction


Apa itu CSS?


- CSS adalah singkatan dari Cascading Style Sheet
- CSS menjelaskan bagaimana elemen HTML ditampilkan di layar, kertas, atau di media lain
- CSS menghemat banyak pekerjaan. Itu dapat mengontrol tata letak beberapa halaman web sekaligus
- Stylesheet eksternal disimpan dalam file CSS



Mengapa Menggunakan CSS?


CSS digunakan untuk menentukan gaya halaman web Anda, termasuk desain, tata letak, dan variasi tampilan untuk berbagai perangkat dan ukuran layar.


```
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: green;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
</style>
</head>
<body>

<h1>Indonesia</h1>
<p>Lolos semi final</p>

</body>
</html>



```


![i11](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/61b64141-f5dd-4b39-815b-e27239537799)




CSS Memecahkan Masalah Besar


HTML TIDAK PERNAH dimaksudkan untuk memuat tag untuk memformat halaman web!
HTML dibuat untuk mendeskripsikan konten halaman web, seperti:
<h1>Ini adalah judul</h1>
<p>Ini adalah sebuah paragraf.</p>
Ketika tag seperti <font>, dan atribut warna ditambahkan ke spesifikasi HTML 3.2, hal ini menimbulkan mimpi buruk bagi pengembang web. Pengembangan situs web besar, di mana font dan informasi warna ditambahkan ke setiap halaman, menjadi proses yang panjang dan mahal.
Untuk mengatasi masalah ini, World Wide Web Consortium (W3C) menciptakan CSS.
CSS menghapus pemformatan gaya dari halaman HTML!


## 2. Syntaks


Sintaks CSS


pemilih css



Pemilih menunjuk ke elemen HTML yang ingin Anda gaya.
Blok deklarasi berisi satu atau lebih deklarasi yang dipisahkan oleh titik koma.
Setiap deklarasi menyertakan nama properti CSS dan nilainya, dipisahkan oleh titik dua.
Beberapa deklarasi CSS dipisahkan dengan titik koma, dan blok deklarasi diapit oleh kurung kurawal.



```
<!DOCTYPE html>
<html>
<head>
<style>
p {
  color: red;
  text-align: center;
} 
</style>
</head>
<body>

<p>Hello World!</p>
<p>These paragraphs are styled with CSS.</p>

</body>
</html>

```


![s1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/ee19d6d2-173c-4d9a-9022-f3b53f94fbc9)


## 3. CSS Selector


Pemilih CSS


Pemilih CSS digunakan untuk "menemukan" (atau memilih) elemen HTML yang ingin Anda gaya.


Kita dapat membagi pemilih CSS menjadi lima kategori:


- Selector sederhana (pilih elemen berdasarkan nama, id, kelas)
- Penyeleksi kombinator (memilih elemen berdasarkan hubungan tertentu di antara elemen tersebut)
- Selector kelas semu (memilih elemen berdasarkan keadaan tertentu)
- Pemilih elemen semu (memilih dan memberi gaya pada bagian elemen)
- Pemilih atribut (memilih elemen berdasarkan atribut atau nilai atribut)


Pemilih elemen CSS
Pemilih elemen memilih elemen HTML berdasarkan nama elemen.

```
<!DOCTYPE html>
<html>
<head>
<style>
p {
  text-align: lift;
  color: brown;
} 
</style>
</head>
<body>

<p>indonesia menang</p>
<p id="para1">Me too!</p>
<p>And me!</p>

</body>
</html>

```

![se1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/132f48df-2c4d-4f88-8390-9f1cc743e71c)


Pemilih ID CSS


Pemilih id menggunakan atribut id dari elemen HTML untuk memilih elemen tertentu.
Id suatu elemen bersifat unik dalam suatu halaman, sehingga pemilih id digunakan untuk memilih satu elemen unik!
Untuk memilih elemen dengan id tertentu, tulis karakter hash (#), diikuti dengan id elemen tersebut.

```
<!DOCTYPE html>
<html>
<head>
<style>
#para1 {
  text-align: center;
  color: black;
}
</style>
</head>
<body>

<p id="para1">indo menang!</p>
<p>This paragraph is not affected by the style.</p>

</body>
</html>



```


Pemilih kelas CSS

Pemilih kelas memilih elemen HTML dengan atribut kelas tertentu.
Untuk memilih elemen dengan kelas tertentu, tuliskan karakter titik (.), diikuti dengan nama kelas.


```
<!DOCTYPE html>
<html>
<head>
<style>
p.center {
  text-align: center;
  color: red;
}

p.large {
  font-size: 300%;
}
</style>
</head>
<body>

<h1 class="center">trhtr</h1>
<p class="center">Thjthr</p>
<p class="center large">This paragraph will be red, center-aligned, and in a large font-size.</p> 

</body>
</html>



```



![se3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/97cbf91d-1cb2-4033-b54e-b3890bddd201)



## 4. CSS Color


CSS Color Names


In CSS, a color can be specified by using a predefined color name:



```
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:Tomato;">Tomato</h1>
<h1 style="background-color:Orange;">Orange</h1>
<h1 style="background-color:DodgerBlue;">DodgerBlue</h1>
<h1 style="background-color:MediumSeaGreen;">MediumSeaGreen</h1>
<h1 style="background-color:Gray;">Gray</h1>
<h1 style="background-color:SlateBlue;">SlateBlue</h1>
<h1 style="background-color:Violet;">Violet</h1>
<h1 style="background-color:LightGray;">LightGray</h1>

</body>
</html>

```


![co1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/8f6ff3c4-36a6-433f-8072-3711a869f3f7)


## Color RGB


```
<!DOCTYPE html>
<html>
<body>

<h1>Specify colors using RGB values</h1>

<h2 style="background-color:rgb(255, 0, 0);">rgb(255, 0, 0)</h2>
<h2 style="background-color:rgb(0, 0, 255);">rgb(0, 0, 255)</h2>
<h2 style="background-color:rgb(60, 179, 113);">rgb(60, 179, 113)</h2>
<h2 style="background-color:rgb(238, 130, 238);">rgb(238, 130, 238)</h2>
<h2 style="background-color:rgb(255, 165, 0);">rgb(255, 165, 0)</h2>
<h2 style="background-color:rgb(106, 90, 205);">rgb(106, 90, 205)</h2>

</body>
</html>

```


![co2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/58929204-26ca-45b9-8d1b-0750516e223a)



## Color HEX

HEX Value


In CSS, a color can be specified using a hexadecimal value in the form:
#rrggbb
Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).
For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).
To display black, set all values to 00, like this: #000000.
splay white, set all values to ff, like this: #ffffff.  
Experiment by mixing the HEX values below:


```
<!DOCTYPE html>
<html>
<body>

<h1>Specify colors using HEX values</h1>

<h2 style="background-color:#ff0000;">#ff0000</h2>
<h2 style="background-color:#0000ff;">#0000ff</h2>
<h2 style="background-color:#3cb371;">#3cb371</h2>
<h2 style="background-color:#ee82ee;">#ee82ee</h2>
<h2 style="background-color:#ffa500;">#ffa500</h2>
<h2 style="background-color:#6a5acd;">#6a5acd</h2>

</body>
</html>



```


![co3](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/da4dd7e9-8a6b-44fc-97cb-3980b6ad7f33)



## 5. CSS Backgraund


## Backgraund Color


Warna latar belakang CSS
Properti background-colormenentukan warna latar belakang suatu elemen.


```
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: lightblue;
}
</style>
</head>
<body>

<h1>M World</h1>

<p>this is aleterego</p>

</body>
</html>



```



![b1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/929e9bb9-c236-40c6-91fc-ab517bd02e43)




## Backggraund gambar

Gambar latar belakang CSS
Properti background-imagemenentukan gambar untuk digunakan sebagai latar belakang suatu elemen.

Secara default, gambar diulang sehingga menutupi keseluruhan elemen.



```
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-image: url("https://th.bing.com/th?id=OLC.ovP5KSr2ckkViQ480x360&w=138&h=110&c=7&rs=1&qlt=80&o=6&cdv=1&dpr=1.3&pid=Local");
}
</style>
</head>
<body>

<h1>Hello World!</h1>

<p>This page has an image as the background!</p>

</body>
</html>



```




![BG1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/768572fb-9bf6-4a5a-b341-19f9ff5d9b55)



## 6. CSS Margin


Margin CSS


Properti CSS margindigunakan untuk menciptakan ruang di sekitar elemen, di luar batas yang ditentukan.
Dengan CSS, Anda memiliki kendali penuh atas margin. Terdapat properti untuk mengatur margin untuk setiap sisi elemen (atas, kanan, bawah, dan kiri).

Margin - Sisi Individu
CSS memiliki properti untuk menentukan margin untuk setiap sisi elemen:

margin-top
margin-right
margin-bottom
margin-left
Semua properti margin dapat memiliki nilai berikut:

otomatis - browser menghitung margin
length - menentukan margin dalam px, pt, cm, dll.
% - menentukan margin dalam % lebar elemen yang memuatnya
mewarisi - menentukan bahwa margin harus diwarisi dari elemen induk


```
<!DOCTYPE html>
<html>
<head>
<style>
div {
  border: 1px solid black;
  margin-top: 80px;
  margin-bottom: 80px;
  margin-right: 90px;
  margin-left: 60px;
  background-color: red;
}
</style>
</head>
<body>

<h2>Using individual margin properties</h2>

<div>This div element has a top margin of 100px, a right margin of 150px, a bottom margin of 100px, and a left margin of 80px.</div>

</body>
</html>


```


![m1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/ad682836-4fe1-48d8-bc55-27e5e1d6dd91)









## Margin collapse


Keruntuhan Margin


Margin atas dan bawah elemen terkadang diciutkan menjadi satu margin yang sama dengan margin terbesar dari kedua margin tersebut.
Hal ini tidak terjadi pada margin kiri dan kanan! Hanya margin atas dan bawah!


```
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  margin: 0 0 70px 0;
}

h2 {
  margin: 40px 0 0 0;
}
</style>
</head>
<body>

<p>In this example the h1 element has a bottom margin of 50px and the h2 element has a top margin of 20px. So, the vertical margin between h1 and h2 should have been 70px (50px + 20px). However, due to margin collapse, the actual margin ends up being 50px.</p>

<h1>Seleko 1</h1>
<h2>Bonsayur2</h2>

</body>
</html>

```


![m2](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/e30c2de2-fb58-4914-8958-02166e6eaccc)


## 6. Box model

Model Kotak CSS


Dalam CSS, istilah "model kotak" digunakan ketika berbicara tentang desain dan tata letak.
Model kotak CSS pada dasarnya adalah sebuah kotak yang membungkus setiap elemen HTML. Terdiri dari: konten, padding, batas dan margin.


```
<!DOCTYPE html>
<html>
<head>
<style>
div {
  background-color: lightgrey;
  width: 300px;
  border: 15px solid brown;
  padding: 50px;
  margin: 20px;
}
</style>
</head>
<body>

<h2>Demonstrating the Box Model</h2>

<p>The CSS box model is essentially a box that wraps around every HTML element. It consists of: borders, padding, margins, and the actual content.</p>

<div>This text is the content of the box. We have added a 50px padding, 20px margin and a 15px green border. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div>

</body>
</html>



```



![b11`](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/f1636ca3-3b63-422b-8d34-6f3e5b5e4b9b)


## 7. CSS text

CSS memiliki banyak properti untuk memformat teks.


```
<!DOCTYPE html>
<html>
<head>
<style>
div {
  border: 1px solid green;
  padding: 8px;
}

h1 {
  text-align: center;
  text-transform: uppercase;
  color: #4CAF50;
}

p {
  text-indent: 50px;
  text-align: justify;
  letter-spacing: 3px;
}

a {
  text-decoration: none;
  color: #008CBA;
}
</style>
</head>
<body>

<div>
  <h1>text formatting</h1>
  <p>This text is styled with some of the text formatting properties. The heading uses the text-align, text-transform, and color properties.
  The paragraph is indented, aligned, and the space between characters is specified. The underline is removed from this colored
  <a target="_blank" href="tryit.asp?filename=trycss_text">"Try it Yourself"</a> link.</p>
</div>

</body>
</html>



```


![tx1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/30497824-af0e-4d05-b622-22239f417b9b)


## 8. CSS Font


## Font Style


Gaya tulisan


Properti ini font-stylesebagian besar digunakan untuk menentukan teks miring.
Properti ini memiliki tiga nilai:
normal - Teks ditampilkan secara normal
miring - Teks ditampilkan dalam huruf miring
miring - Teksnya "condong" (miring sangat mirip dengan miring, tetapi kurang didukung)


```
<!DOCTYPE html>
<html>
<head>
<style>
p.normal {
  font-variant: normal;
}

p.small {
  font-variant: small-caps;
}
</style>
</head>
<body>

<h1>The font-variant property</h1>

<p class="normal">My name is Hege Refsnes.</p>
<p class="small">My name is Hege Refsnes.</p>

</body>
</html>

```


## Font Zize


Ukuran huruf


Properti font-sizemengatur ukuran teks.
Mampu mengatur ukuran teks penting dalam desain web. Namun, Anda sebaiknya tidak menggunakan penyesuaian ukuran font untuk membuat paragraf terlihat seperti judul, atau judul terlihat seperti paragraf.
Selalu gunakan tag HTML yang tepat, seperti <h1> - <h6> untuk judul dan <p> untuk paragraf.
Nilai ukuran font dapat berupa ukuran absolut atau relatif.
Ukuran absolut:
Mengatur teks ke ukuran tertentu
Tidak mengizinkan pengguna mengubah ukuran teks di semua browser (buruk karena alasan aksesibilitas)
Ukuran absolut berguna ketika ukuran fisik keluaran diketahui
Ukuran relatif:
Menetapkan ukuran relatif terhadap elemen di sekitarnya
Memungkinkan pengguna mengubah ukuran teks di browser

```
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  font-size: 40px;
}

h2 {
  font-size: 30px;
}

p {
  font-size: 14px;
}
</style>
</head>
<body>

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

</body>
</html>

```



![fz](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/37962d41-458c-4e6b-bc9e-ecc49fdb57ec)



## 8. CSS Table



## Table Borders



To specify table borders in CSS, use the border property.
The example below specifies a solid border for <table>, <th>, and <td> elements:



```
<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
  border: 1px solid;
}
</style>
</head>
<body>

<h2>Add a border to a table:</h2>

<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
  </tr>
</table>

</body>
</html>

```



![tb](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/2b5172f4-01a3-4c26-9d7a-d4b0135ac784)



## Table Zize



Lebar dan Tinggi Meja



Lebar dan tinggi tabel ditentukan oleh properti widthdan height.
Contoh di bawah menyetel lebar tabel menjadi 100%, dan tinggi elemen <th> menjadi 70 piksel:



```
<!DOCTYPE html>
<html>
<head>
<style>
table, td, th {
  border: 1px solid black;
}

table {
  border-collapse: collapse;
  width: 100%;
}

th {
  height: 70px;
}
</style>
</head>
<body>

<h2>The width and height Properties</h2>

<p>Set the width of the table, and the height of the table header row:</p>

<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>Peter</td>
    <td>Griffin</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>Lois</td>
    <td>Griffin</td>
    <td>$150</td>
  </tr>
  <tr>
    <td>Joe</td>
    <td>Swanson</td>
    <td>$300</td>
  </tr>
  <tr>
    <td>Cleveland</td>
    <td>Brown</td>
    <td>$250</td>
  </tr>
</table>

</body>
</html>

```



![tz](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/57b391fc-554b-4433-ada8-1af4b0fc5cc3)



## JavaScript


## 1. JS Interduction


JavaScript Dapat Mengubah Konten HTML


Salah satu dari banyak metode JavaScript HTML adalah getElementById().
Contoh di bawah ini "menemukan" elemen HTML (dengan id="demo"), dan mengubah konten elemen (innerHTML) menjadi "Halo JavaScript":


```
<!DOCTYPE html>
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can change HTML content.</p>

<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button>

</body>
</html>

```


![ji1](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/d73ae39c-cb48-4e03-8592-40b557c95330)



## 2. JS Syntx


Nilai JavaScript


Sintaks JavaScript mendefinisikan dua jenis nilai:
- Nilai tetap
- Nilai variabel
Nilai tetap disebut Literals .
Nilai variabel disebut Variabel .


```
<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Numbers</h2>

<p>Number can be written with or without decimals.</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = 10.50;
</script>

</body>
</html>

```


![jss](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/334e849b-54f8-4e31-a203-296a733c45be)



## 3. JS Fungction


Sintaks Fungsi JavaScript


Fungsi JavaScript didefinisikan dengan functionkata kunci, diikuti dengan nama , diikuti dengan tanda kurung () .
Nama fungsi dapat berisi huruf, angka, garis bawah, dan tanda dolar (aturannya sama seperti variabel).
Tanda kurung dapat menyertakan nama parameter yang dipisahkan dengan koma:
( parameter1, parameter2, ... )
Kode yang akan dieksekusi, berdasarkan fungsi, ditempatkan di dalam tanda kurung kurawal: {}



Pemanggilan Fungsi]


Kode di dalam fungsi akan dijalankan ketika "sesuatu" memanggil (memanggil) fungsi tersebut:
- Saat suatu peristiwa terjadi (saat pengguna mengklik tombol)
- Ketika dipanggil (dipanggil) dari kode JavaScript
- Secara otomatis (dipanggil sendiri)
Anda akan belajar lebih banyak tentang pemanggilan fungsi nanti di tutorial ini.
IKLAN


Fungsi Kembali



Ketika JavaScript mencapai sebuah returnpernyataan, fungsi tersebut akan berhenti dijalankan.
Jika fungsi dipanggil dari sebuah pernyataan, JavaScript akan "kembali" untuk mengeksekusi kode setelah pernyataan yang dipanggil.
Fungsi sering kali menghitung nilai kembalian . Nilai yang dikembalikan "dikembalikan" ke "penelepon":



```
<!DOCTYPE html>
<html>
<body>

<h1>JavaScript Functions</h1>

<p>Call a function which performs a calculation and returns the result:</p>

<p id="demo"></p>

<script>
let x = myFunction(4, 3);
document.getElementById("demo").innerHTML = x;

function myFunction(a, b) {
  return a * b;
}
</script>

</body>
</html>

```

![jf](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/780874ac-fb1a-4663-9a58-02119c4c070b)



## 4. JS Strings


Menggunakan Kutipan


String JavaScript adalah nol atau lebih karakter yang ditulis di dalam tanda kutip.



```
<!DOCTYPE html>
<html>
<body>

<h1>JavaScript Strings</h1>

<p id="demo"></p>

<script>
let text = "John Doe";  // String written inside quotes
document.getElementById("demo").innerHTML = text;
</script>

</body>
</html>

```


![jsss](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/8a93ce8e-71ef-4c07-81f4-5dbd6c83f1d4)


## 5. JS Array


Mengapa Menggunakan Array?


Jika Anda memiliki daftar item (misalnya daftar nama mobil), menyimpan mobil dalam variabel tunggal akan terlihat seperti ini:
Namun, bagaimana jika Anda ingin menelusuri mobil-mobil tersebut dan menemukan mobil tertentu? Dan bagaimana jika Anda tidak punya 3 mobil, tapi 300?
Solusinya adalah sebuah array!
Sebuah array dapat menampung banyak nilai dalam satu nama, dan Anda dapat mengakses nilai tersebut dengan mengacu pada nomor indeks.


Membuat Array


Menggunakan literal array adalah cara termudah untuk membuat Array JavaScript.


```
<!DOCTYPE html>
<html>
<body>
<h1>JavaScript Arrays</h1>

<p id="demo"></p>

<script>
const cars = ["Saab", "Volvo", "BMW"];
document.getElementById("demo").innerHTML = cars;
</script>

</body>
</html>

```


![ja](https://github.com/JosindoRadit/praktikum-web-1/assets/168063657/b3b7d4f6-46b5-4a26-9023-c9b092686393)















