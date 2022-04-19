# Lab6web
```
              Alfiansyah Rambe
              312010338
              TI 20 B2
```

# Praktikum 6
### membuat layout web dengan menggunakan Twitter Bootsrap.

## langkah 1
Buka web Bootstrap https://getbootstrap.com/ lalu download file bootstrap.
![image](https://user-images.githubusercontent.com/101393632/163903032-752f36ba-555d-489b-b9a4-d1e8358976ac.png)

## langkah 2
Jika sudah di download, masukkan file tersebut kedalam file lab6_css_framework

![image](https://user-images.githubusercontent.com/101393632/163903166-1adcfc3e-6941-4a13-b3e2-9d86c6355066.png)

Disini kita akan mendapatkan 3 file, yaitu : css, img dan js.

## langkah 3
Buat File html didalam dile lab6_css_framework dan masukan kode bootstrapnya, kode tersebut bisa kita ambil dari web bootstrap.

Berikut Kodenya :

```
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
  </body>
</html>
```

## langkah 4
setelah itu buatlah layout sederhana seperti yang pernah kita buat di praktikum sebelumnya.

dan dibawah ini adalah kode nya :

### HTML
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
      crossorigin="anonymous"
    />
    <link rel="stylesheet" href="stylelayout.css" />

    <title>Layout dengan Bootstrap</title>
  </head>
  <body>
    <div id="container">
      <header>
        <h1>Layout Sederhana</h1>
      </header>

      <!-- Menambah Navigasi -->
      <nav>
        <a href="home.html" class="active">Home</a>
        <a href="artikel.html">Artikel</a>
        <a href="about.html">About</a>
        <a href="kontak.html">Kontak</a>
      </nav>

      <!-- Menambah panel HERO -->
      <section id="hero">
        <h1>
          <b>Hello World!</b>
        </h1>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum
          lorem elit, iaculis innisl volutpat, malesuada tincidunt arcu. Proin
          in leo fringilla, vestibulum mi porta, faucibus felis. Integer
          pharetra est nunc, nec pretium nunc pretium ac.
        </p>
        <a href="home.html" class="btn btn-primary" role="button"
          >Learn more &raquo;</a
        >
      </section>

      <!-- Menambah Wrapper, Main, row dan box -->
      <div id="wrapper">
        <section id="main">
          <div class="row">
            <div class="box">
              <img
                src="https://dummyimage.com/120/db7d25/fff.png"
                alt=""
                class="image-circle"
              />
              <h3>satu</h3>
              <p>
                Donec sed odio dui. Etiam porta sem malesuada magna mollis
                euismod.
              </p>
              <button type="button" class="btn btn-secondary">
                View detail
              </button>
            </div>
            <div class="box">
              <img
                src="https://dummyimage.com/120/3e73e6/fff.png"
                alt=""
                class="image-circle"
              />
              <h3>dua</h3>
              <p>
                Donec sed odio dui. Etiam porta sem malesuada magna mollis
                euismod.
              </p>
              <button type="button" class="btn btn-secondary">
                View detail
              </button>
            </div>
            <div class="box">
              <img
                src="https://dummyimage.com/120/71e6d4/fff.png"
                alt=""
                class="image-circle"
              />
              <h3>tiga</h3>
              <p>
                Donec sed odio dui. Etiam porta sem malesuada magna mollis
                euismod.
              </p>
              <button type="button" class="btn btn-secondary">
                View detail
              </button>
            </div>
          </div>

          <hr class="divider" />
          <article class="entry">
            <h2>First featurette heading.</h2>
            <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" />
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
              tincidunt arcu. Proin in leo fringilla, vestibulum mi porta,
              faucibus felis. Integer pharetra est nunc, nec pretium nunc
              pretium ac.
            </p>
          </article>
          <hr class="divider" />
          <article class="entry">
            <h2>First featurette heading.</h2>
            <img
              src="https://dummyimage.com/150/7b8a70/fff.png"
              alt=""
              class="right-img"
            />
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit.
              Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
              tincidunt arcu. Proin in leo fringilla, vestibulum mi porta,
              faucibus felis. Integer pharetra est nunc, nec pretium nunc
              pretium ac.
            </p>
          </article>
        </section>
        <aside id="sidebar">
          <div class="widget-box">
            <h3 class="title">Widget Header</h3>
            <ul>
              <li><a href="#">Widget Link</a></li>
              <li><a href="#">Widget Link</a></li>
              <li><a href="#">Widget Link</a></li>
              <li><a href="#">Widget Link</a></li>
              <li><a href="#">Widget Link</a></li>
            </ul>
          </div>
          <div class="widget-box">
            <h3 class="title">Widget Text</h3>
            <p>
              Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
              tincidunt arcu. Proin in leo fringilla, vestibulum mi porta,
              faucibus felis. Integer pharetra est nunc, nec pretium nunc
              pretium ac.
            </p>
          </div>
        </aside>
      </div>
      <footer>
        <p>
          &copy; 2022 - Universitas Pelita Bangsa - Alfiansyah Rambe - 312010338
        </p>
      </footer>
    </div>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
      crossorigin="anonymous"
    ></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
  </body>
</html>
```

### CSS
```
/* Reset CSS */
* {
  margin: 0;
  padding: 0;
 }
 body {
  line-height:1;
  font-size:100%;
  font-family:'Open Sans', sans-serif;
  color:#5a5a5a;
 }
 #container {
  width: 980px;
  margin: 0 auto;
  box-shadow: 0 0 1em #cccccc;
 }
 /* header */
 header {
  padding: 20px;
 }
 header h1 {
  margin: 20px 10px;
  color: #b5b5b5;
 }
 
 /* Navigasi */
  nav {
   display: block;
   background-color: #1f5faa;
  }
  nav a {
   padding: 15px 30px;
   display: inline-block;
   color: #ffffff;
   font-size: 14px;
   text-decoration: none;
   font-weight: bold;
  }
 
  nav a.active,
  nav a:hover {
   background-color: #2b83ea;
  }
 
 /* Hero Panel */
 #hero {
   background-color: #e4e4e5;
   padding: 50px 20px;
   margin-bottom: 20px;
  }
  #hero h1 {
   margin-bottom: 20px;
   font-size: 35px;
  }
  #hero p {
   margin-bottom: 20px;
   font-size: 18px;
   line-height: 25px;
  }
 
 /* Main content */
  #wrapper {
    margin: 0;
  }
  #main {
   float: left;
   width: 640px;
   padding: 20px;
  }
  /* sidebar area */
  #sidebar {
   float: left;
   width: 260px;
   padding: 20px;
  }
 
 /* widget */
 .widget-box {
   border:1px solid #eee;
   margin-bottom:20px;
  }
  .widget-box .title {
   padding:10px 16px;
   background-color:#428bca;
   color:#fff;
   font-size: 20px;
  }
  .widget-box ul {
   list-style-type:none;
  }
  .widget-box li {
   border-bottom:1px solid #eee;
 }
 .widget-box li a {
  padding:10px 16px;
  color:#333;
  display:block;
  text-decoration:none;
 }
 .widget-box li:hover a {
  background-color:#eee;
 }
 .widget-box p {
  padding:15px;
  line-height:25px;
 } 
 
 /* footer */
 footer {
   clear: both;
   background-color:#1d1d1d;
   padding:20px;
   color:#eee;
  }
  
 /* box */
 .box {
   display:block;
   float:left;
   width:33.333333%;
   box-sizing:border-box;
   -moz-box-sizing:border-box;
   -webkit-box-sizing:border-box;
   padding:0 10px;
   text-align:center;
  }
  .box h3 {
   margin: 15px 0;
  }
  .box p {
   line-height: 20px;
   font-size: 14px;
   margin-bottom: 15px;
  }
  .box img {
   border: 0;
   vertical-align: middle;
  }
 
 /* img circle */
  .image-circle {
   border-radius: 50%;
  }
 
 /* row */
  .row {
   margin: 0 -10px;
   box-sizing: border-box;
   -moz-box-sizing: border-box;
   -webkit-box-sizing: border-box;
  }
  .row:after, .row:before,
  .entry:after, .entry:before {
   content:'';
   display:table;
  }
  .row:after,
  .entry:after {
   clear:both;
  } 
 
 /* divider */
  .divider {
   border:0;
   border-top:1px solid #eeeeee;
   margin:40px 0;
  }
 
 /* entry */
  .entry {
   margin: 15px 0;
  }
  .entry h2 {
   margin-bottom: 20px;
  }
  .entry p {
   line-height: 25px;
  }
  .entry img {
   float: left;
   border-radius: 5px;
   margin-right: 15px;
  }
  .entry .right-img {
   float: right;
  } 

```
### Dan dibawah ini adalah hasil dari Kode Bootstrap di atas :

![HASIL](https://user-images.githubusercontent.com/101393632/163915698-a2419a66-d3e6-40a7-8bb1-eecd4f3f98ba.jpg)

============ S E L E S A I ==========
