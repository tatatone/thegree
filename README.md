<html>
<head>
<title>THE GREE</title>
</head>
<link rel="stylesheet" href="style.css">
<body bgcolor="5c7a73">
<div class="header">
	<h1 align="certer"><img src="หัว.jpg" width="100%"height="25%"></h1>
<div class="manu">
	<a href="home.html">หน้าแรก</a>
	<a href="4.html">สินค้าทั้งหมด</a>
	<a href="2.html">บทความ</a>
	<a href="3.html">เกี่ยวกับ</a>
	<a href="ต.html">ติดต่อ</a>
</div><br><br>

<div class="slideshow-container">
  <div class="mySlides fade">
    <div class="numbertext"></div>
    <a href="ไม้ดอก.html"><img src="dok.jpg" style="width:100%"></a>
  </div>
  <div class="mySlides fade">
    <div class="numbertext"></div>
    <a href="ไม้ร่มเงา.html"><img src="mi.jpg" style="width:100%"></a>
   
    <div class="text"></div>
  </div>
  <div class="mySlides fade">
    <div class="numbertext"></div>
    <a href="ไม้แนวรั่ว.html"><img src="nr.jpg" style="width:100%"></a>
  </div>
  <div class="mySlides fade">
    <div class="numbertext"></div>
    <a href="ไม้เลื่อย.html"><img src="ไม้เลื่อย.jpg" style="width:100%"></a>
  </div>
  <div class="mySlides fade">
    <div class="numbertext"></div>
    <a href="ไม้ในบ้าน.html"><img src="tmnb.jpg" style="width:100%"></a>
  </div>
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
  <br>
  <div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span> 
    <span class="dot" onclick="currentSlide(2)"></span> 
    <span class="dot" onclick="currentSlide(3)"></span>
    <span class="dot" onclick="currentSlide(4)"></span> 
    <span class="dot" onclick="currentSlide(5)"></span>  
  </div>
  <script>
  var slideIndex = 1;
  showSlides(slideIndex);
  function plusSlides(n) {
    showSlides(slideIndex += n);
  }
  function currentSlide(n) {
    showSlides(slideIndex = n);
  }
  function showSlides(n) {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    if (n > slides.length) {slideIndex = 1}    
    if (n < 1) {slideIndex = slides.length}
    for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";  
    }
    for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active";
  }
  </script><br><br><br>
<footer>
  <div class="container">
 <marquee style="color:white">© Copyright 2020 chanitnan, All Rights Reserved</marqueen>
 </div>
</footer>
</body>
</html>
