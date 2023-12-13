<html>
  <head>
    <style>
body {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  margin: 0;
}
.navbar {
  overflow: hidden;
  background-color: #333;
}
.navbar a {
  font-size:16px ;
  float: left;
  padding: 14px 16px;
  color: rgb(10, 183, 214);
  text-align:center ;
  text-decoration: none;
}
.subnav {
  overflow: hidden;
  float: left;
}
.subnav .subnavbtn {
  font-size:16px ;
  outline: none;
  border:none ;
  color: green;
  background-color:inherit ;
  font-family:inherit ;
  padding:14px 16px ;
  margin: 0;
}
.navbar a:hover, .subnav:hover .subnavbtn {
  background-color: khaki;
}
.subnav-content {
  display: none;
  position: absolute;
  left: 0;
  background-color: khaki;
  z-index: 1;
  width: 100%;
}
.subnav-content a {
  float: left;
  color: red;
  text-decoration: none;
}
.subnav-content a:hover {
  background-color:greenyellow ;
  color: blue;
}
.subnav:hover .subnav-content {
  display: block;
}
    </style>
  </head>
  <body style="background-image: url(https://awsimages.detik.net.id/community/media/visual/2021/06/14/salah-satu-kapal-perang-iran-berlayar-di-perairan-samudra-atlantik_169.jpeg?w=1200);">\
    <h1>semat datang di biro kami</h1>
    <div class="navbar">
      <a href="menu utama">menu utama</a>
      <div class="subnav">
        <button class="subnavbtn">layanan informasi<i class="fa fa-caret-down"></i></button>
        <div class="subnav-content">
          <a href="#liburan">liburan</a>
          <a href="#transportasi">transportasi</a>
          <a href="#hotel">hotel</a>
        </div>
      </div>
      <div class="subnav">
        <button class="subnavbtn">pemesanan layanan<i class="fa fa-caret down"></i></button>
        <div class="subnav-content">
          <a href="#destinasi liburan"> destinasi liburan</a>
          <a href="#transportasi">transportasi</a>
          <a href="#hotel">hotel</a>
          <a href="#vila">vila</a>
          <a href="#homestay">homestay</a>
        </div>
      </div>
    </div>
  </body>
</html>
