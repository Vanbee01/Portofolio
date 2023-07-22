# Portofolioo
This my portofolio 
created by Wahyudin

BASE CODE

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="style.css" type="text/css" media="all" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css">
  <script src="https://code.jquery.com/jquery-3.6.3.min.js" integrity="sha256-pvPw+upLPUjgMXY0G+8O0xUf+/Im1MZjXxxgOcBQBXU=" crossorigin="anonymous"></script>
  <title>Wahyudin</title>
</head>
<body>
  <!---loader--->
  <div class="bg-loader">
    <div class="loader"></div>
  </div>
  <!--- Header --->
  <div class="medsos">
    <div class="container">
      <ul>
        <li><a href="#"><i class="fa-brands fa-facebook"></i></a></li>
        <li><a href="#"><i class="fa-brands fa-youtube"></i></a></li>
        <li><a href="#"><i class="fa-brands fa-instagram"></i></a></li>
      </ul>
    </div>
  </div>
  
  <header>
    <div class="container">
    <h1><a href="index.html">WAHYUDIN</a></h1>
      <ul>
        <li class="active"><a href="index.html">HOME</a></li>
        <li><a href="about.html">ABOUT</a></li>
        <li><a href="service.html">SERVICE</a></li>
        <li><a href="contact.html">CONTACT</a></li>
      </ul>
    </div>
  </header>
  <!--- Banner --->
  <section class="banner">
    <h2><a href="webdev.html" >KLIK UNTUK MELIHAT LEBIH</a></h2>
  </section>
  <!--- About --->
  <section class="about">
    <div class="container">
      <h3>About</h3>
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. <strong>Lorem Ipsum has been the industry's</strong> standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book</p>
    </div>
  </section>
  <!--- Service --->
  <section class="service">
    <div class="container">
      <h3>SERVICE</h3>
      <div class="box">
        <div class="col-4">
          <div class="icon"><i class="fa-solid fa-mobile"></i></div>
          <h4>MOBILE APP</h4>
        </div>
        <div class="col-4">
          <div class="icon"><a href="webdev.html"><i class="fa-solid fa-globe"></i></a></div>
          <h4>WEB DEVELOPMENT</h4>
        </div>
        <div class="col-4">
          <div class="icon"><i class="fa-solid fa-edit"></i></div>
          <h4>DESIGN</h4>
        </div>
        <div class="col-4">
          <div class="icon"><i class="fa-solid fa-chart-bar"></i></div>
          <h4>DIGITAL MARKETING</h4>
        </div>
      </div>
    </div>
  </section>
  <!---Footer--->
  <footer>
    <div class="container">
      <small>Copyright &copy; 2023 - Wahyudin All Rights Reserve.</small>
    </div>
  </footer>
  <script type="text/javascript">
    $(document).ready(function(){
      $(".bg-loader").hide();
    })
  </script>
</body>
</html>
