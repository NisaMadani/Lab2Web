# Lab2Web
	Jawaban no. 2
Pendeklarasian CSS elemen h1{…} = mengatur posisi dan memberikan gaya pada judul halaman utama yang bersifat default
Pendeklarasian CSS elemen #intro h1{…} = mengatur posisi dan gaya pada judul halaman utama dengan tema yang kita sukai.
	Jawaban no 3.
Semuanya akan tampil.

Internal CSS adalah kode CSS yang ditulis di dalam tag <style> dan kode HTML dituliskan di bagian atas (header) file HTML. Internal CSS dapat digunakan untuk membuat tampilan pada satu halaman website dan tidak digunakan pada halaman website yang lain.
Cara ini akan sangat cocok dipakai untuk menciptakan halaman web dengan tampilan yang berbeda. Dengan kata lain, Internal CSS ini bisa dipakai untuk menciptakan tampilan yang unik, pada setiap halaman website.
Berikut ini adalah contoh penempatan Internal CSS pada file HTML.
<!DOCTYPE html>
<html>
<head>
  <title>Contoh Internal CSS</title>
  <!-- contoh internal css dalam tag head -->
  <style type="text/css">
    p{
      font-family: arial;
      line-height: 2.75em;
      font-size: 16px;
    }
    i { 
      font-family: arial;
      color: blue;
    }
  </style>
</head>

<body>
  <!-- contoh internal css dalam tag body -->
  <style type="text/css">
    h2 { 
      font-family: arial;
      color: #1B9CFC;
    }
  </style>
  <h2>Niagahoster</h2>
</body>
</html>


Eksternal CSS adalah kode CSS yang ditulis terpisah dengan kode HTML Eksternal CSS ditulis di sebuah file khusus yang berekstensi .css. File eksternal CSS biasanya diletakkan setelah bagian <head> pada halaman.
Cara ini lebih sederhana dan simpel daripada menambahkan kode CSS di setiap elemen HTML yang ingin Anda atur tampilannya. 
Berikut ini adalah contoh penempatan External CSS pada file HTML. Sebagai contoh saya membuat file CSS dengan nama style.css berikut isi kode style.css.
p {
    font-family: arial;
    line-height: 2.75em;
}

i {
    font-family: arial;
    color: orange;
}

h2 {
    font-family: arial;
    color: #1B9CFC;
}
Untuk menggunakan file style.css dalam HTML, Anda perlu menambahkannya ke dalam file HTML. Dengan menggunakan tag <link> berikut contohnya.
<link rel="stylesheet" type="text/css" href="style.css">
Berikut ini penempatan kode dalam satu file HTML.
<!DOCTYPE html>
<html>
<head>
    <title>Contoh Eksternal CSS</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <h2>Niagahoster</h2>
</body>
</html>

Inline CSS adalah kode CSS yang ditulis langsung pada atribut elemen HTML. Setiap elemen HTML memiliki atribut style, di situ lah inline CSS ditulis.
Cara ini kurang efisien karena setiap tag HTML yang diberikan harus memiliki style masing-masing. Anda akan lebih sulit dalam mengatur website jika hanya menggunakan inline CSS. Sebab, Inline CSS digunakan hanya untuk mengubah satu elemen saja.
Berikut ini adalah contoh penempatan kode dari Inline CSS:
<h2 style="color:blue; font-family: arial;">Niagahoster</h2>



	Jawaban no 4.

Semuanya akan tampil di browser. Kode CSS internal diletakkan di dalam bagian <head> pada halaman. Class dan ID bisa digunakan untuk merujuk pada kode CSS, namun hanya akan aktif pada halaman tersebut.
 <div id="intro">
        <h1>Hello World</h1>
        <p style="text-align: center;color: #ccd8e4;">Kami sedang belajar HTML dan CSS dasar , pada mata kuliah<b>Pemrograman
            Web</b> 
            di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat
            adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML
            dan CSS.</p>
                    <!--CSS Class Selector-->
                    <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
                </div>
            </body>
            </html>


















