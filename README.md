<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CHANDAN KUMAR SHOPPING</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
  
</head>
<style>
  <!--css use-->
  .product-card {
  transition: 0.3s ease;
}

.product-card:hover {
  transform: scale(1.03);
  box-shadow: 0 5px 15px rgba(231, 7, 7, 0.3);
}

.carousel-item img {
  height: 500px;
  object-fit: cover;
}

footer {
  margin-top: 40px;
}

</style>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container-fluid">
      <a class="navbar-brand fw-bold" href="#">WELCOME TO THE CHANDAN WEBSITE</a>
      <form class="d-flex mx-auto w-50">
        <input class="form-control me-2" type="search" placeholder="Search for  chandan  brands and more" aria-label="Search">
        <button class="btn btn-light" type="submit">Search</button>
      </form>
      <div>
        <a href="#" class="btn btn-outline-light me-2">Login</a>
        <a href="#" class="btn btn-outline-light">Cart</a>
      </div>
    </div>
  </nav>



  <!-- Banner -->
  <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="software.png" class="d-block w-100" alt="Banner">
      </div>
      <div class="carousel-item">
        <img src="software1.png" class="d-block w-100" alt="Banner">
      </div>
    </div>
  </div>
 


  <!-- Categories -->
  <div class="container my-4">
    <div class="row text-center">
      <div class="col">
        <img src="https://rukminim2.flixcart.com/image/312/312/xif0q/computer/l/0/r/-original-imahbzhbnvgjpm7n.jpeg?q=70" class="rounded-circle mb-2">
        <p>Laptop</p>
      </div>
      <div class="col">
        <img src="https://rukminim2.flixcart.com/image/312/312/xif0q/washing-machine-new/z/l/l/-original-imags7tpwaxawghz.jpeg?q=70" class="rounded-circle mb-2">
        <p>Electronics</p>
      </div>
      <div class="col">
        <img src="data:image/jpeg;base64,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" class="rounded-circle mb-2">
        <p>SHIRTS</p>
      </div>
      <div class="col">
        <img src="https://rukminim2.flixcart.com/image/612/612/xif0q/shirt/0/s/u/xl-st2-vebnor-original-imahdt27ykzceue5.jpeg?q=70" class="rounded-circle mb-2">
        <p>Fashion</p>
      </div>
      <div class="col">
        <img src="https://rukminim2.flixcart.com/fk-p-flap/100/100/image/cb8cea37b03f03d3.jpg?q=50" class="rounded-circle mb-2">
        <p>Home</p>
      </div>
      <div class="col">
        <img src="https://rukminim2.flixcart.com/image/312/312/xif0q/television/m/c/f/-original-imahdzrccjqqfhqc.jpeg?q=70" class="rounded-circle mb-2">
        <p>Appliances</p>
      </div>
    </div>
  </div>




  <!-- Products -->
  <div class="container">
    <h3 class="mb-4">Best Deals</h3>
    <div class="row">
      <div class="col-md-3">
        <div class="card product-card">
          <img src="https://rukminim2.flixcart.com/image/312/312/xif0q/computer/2/h/m/-original-imahdwgyjhs2g8kp.jpeg?q=70" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Laptop</h5>
            <p class="card-text">From ₹29,999</p>
            <a href="#" class="btn btn-primary btn-sm">Buy</a>
          </div>
        </div>
      </div>


      <div class="col-md-3">
        <div class="card product-card">
          <img src="https://rukminim2.flixcart.com/image/312/312/xif0q/mobile/g/n/3/-original-imahdv7fg5x2zyyz.jpeg?q=70" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Smartphone</h5>
            <p class="card-text">From ₹9,999</p>
            <a href="#" class="btn btn-primary btn-sm">Buy</a>
          </div>
        </div>
      </div>


      <div class="col-md-3">
        <div class="card product-card">
          <img src="https://rukminim2.flixcart.com/image/612/612/xif0q/headphone/t/t/j/-original-imahd2syvmhjsxhm.jpeg?q=70" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Headphones</h5>
            <p class="card-text">From ₹799</p>
            <a href="#" class="btn btn-primary btn-sm">Buy</a>
          </div>
        </div>
      </div>


      <div class="col-md-3">
        <div class="card product-card">
          <img src="https://rukminim2.flixcart.com/image/612/612/xif0q/smartwatch/n/z/f/-original-imah8762zqn7v9gt.jpeg?q=70" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Smart Watch</h5>
            <p class="card-text">From ₹1,499</p>
            <a href="#" class="btn btn-primary btn-sm">Buy</a>
          </div>
        </div>
      </div>
    </div>
  </div>


   <div class="col-md-3">
        <div class="card product-card">
          <img src="https://rukminim2.flixcart.com/image/312/312/xif0q/mobile/q/n/s/-original-imah4jyfrgsbebg9.jpeg?q=70" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">i PHONE</h5>
            <p class="card-text">From ₹1,4999</p>
            <a href="#" class="btn btn-primary btn-sm">Buy</a>
          </div>
        </div>
      </div>
    </div>
  </div>



  
  <!-- Footer -->
  <footer class="bg-primary text-white text-center p-3 mt-4">
    &copy; Welcome to Chandan Kumar Shopping Website!
Your one-stop destination for quality products, great deals, and an exceptional shopping experience.
Shop smart. Shop with us!


  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
# chandan-kuamr-shopping-website
