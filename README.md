<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Décor - About Us</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero {
      background: url('image1.png') no-repeat center center;
      background-size: cover;
      color: white;
      text-align: center;
      padding: 50px 0;
    }
    .overview, .details, .combination {
      padding: 50px 0;
    }
    .footer {
      background: #333;
      color: white;
      padding: 30px 0;
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">DÉCOR</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
        <li class="nav-item border border-subtle badge ps-3 pe-3 border-1 text-center m-2 ">
            <a class="nav-link  text-dark" aria-current="page" href="index.html">Home</a>
          </li>
          <li class="nav-item border border-subtle badge ps-3 pe-3 border-1 text-center m-2 ">
            <a class="nav-link  text-dark" aria-current="page" href="aboutus.html">About us</a>
          </li>
          <li class="nav-item border border-subtle badge ps-3 pe-3 border-1 text-center m-2 ">
            <a class="nav-link  text-dark" aria-current="page" href="service.html">Services</a>
          </li>
          <li class="nav-item border border-subtle badge ps-3 pe-3 border-1 text-center m-2 ">
            <a class="nav-link  text-dark" aria-current="page" href="contactus.html">Contact us</a>
          </li>
    </ul>
  </div>
</nav>

<!-- Hero Section -->
<section class="hero">
  <div class="container">
    <h1>About Our Brand</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Placera mattis.</p>
  </div>
</section>

<!-- Overview Section -->
<section class="overview">
  <div class="container">
    <h2>Overview</h2>
    <p> Interior designers work closely with clients to understand their needs and preferences, translating them into cohesive
         designs that reflect personal style while adhering to practical considerations. Key aspects include spatial planning,
          architectural detailing, and the integration of technology and sustainability. The goal is to create spaces that are 
          both beautiful and livable, enhancing the overall quality of life for the occupants</p>
  </div>
</section>

<!-- Details Section -->
<section class="details bg-light">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <img src="image4.jpg" height="300" width="400" alt="Carefully Considered Details">
      </div>
      <div class="col-md-6">
        <h3>Carefully Considered Details & Perfections</h3>
        <p>Carefully considered details in interior design can transform a space, harmonizing functionality with aesthetics.
         Thoughtful selections of textures, colors, and materials create a cohesive atmosphere, while strategically placed 
         lighting enhances ambiance and highlights architectural features. Every element, from bespoke furniture to curated decor,
          is meticulously chosen to reflect personal style and elevate the overall experience of the room.</p>
        <a href="#" class="btn btn-warning">Learn More</a>
      </div>
    </div>
  </div>
</section>

<!-- Combination Section -->
<section class="combination">
  <div class="container">
    <div class="row">
      <div class="col-md-6 order-md-2">
        <img src="image3.jpeg" class="img-fluid" alt="Crafted in Combination of beauty & Perfection">
      </div>
      <div class="col-md-6 order-md-1">
        <h3>Crafted in Combination of beauty & Perfection</h3>
        <p>Crafted in a combination of beauty and perfection, exceptional interior design merges elegance with meticulous attention
             to detail. Each element, from bespoke furniture to intricate lighting fixtures, is chosen to harmonize with the overall
              aesthetic. The result is a space that not only captivates the eye but also embodies a seamless blend of functionality 
              and artistry.</p>
        <a href="#" class="btn btn-warning">Shop now</a>
      </div>
    </div>
  </div>
</section>

<!-- Footer -->
<footer class="footer">
  <div class="container">
    <div class="row">
      <div class="col-md-4">
        <h5>COMPANY</h5>
        <ul class="list-unstyled">
          <li><a href="#">Profile</a></li>
          <li><a href="#">Contact</a></li>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Locations</a></li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5>RETURNS</h5>
        <ul class="list-unstyled">
          <li><a href="#">FAQ's</a></li>
          <li><a href="#">Size Guides</a></li>
          <li><a href="#">Address</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5>FOLLOW US</h5>
        <a href="#" class="mr-2"><img src="path_to_icon.png" alt="LinkedIn"></a>
        <a href="#" class="mr-2"><img src="path_to_icon.png" alt="Instagram"></a>
        <a href="#"><img src="path_to_icon.png" alt="Facebook"></a>
      </div>
    </div>
  </div>
</footer>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
