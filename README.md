<!DOCTYPE html><html lang="es"><head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Tienda Online</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
    }
    .navbar {
      margin-bottom: 20px;
    }
    .card {
      margin: 10px;
    }
  </style>
</head><body>
  <!-- HEADER -->
  <header>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Mi Tienda</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item"><a class="nav-link active" href="#">Inicio</a></li>
            <li class="nav-item"><a class="nav-link" href="#destacados">Destacados</a></li>
            <li class="nav-item"><a class="nav-link" href="#ofertas">Ofertas</a></li>
          </ul>
        </div>
      </div>
    </nav>
  </header>  <!-- SLIDER -->  <section class="container mb-4">
    <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="https://via.placeholder.com/800x300" class="d-block w-100" alt="slide1">
        </div>
        <div class="carousel-item">
          <img src="https://via.placeholder.com/800x300" class="d-block w-100" alt="slide2">
        </div>
        <div class="carousel-item">
          <img src="https://via.placeholder.com/800x300" class="d-block w-100" alt="slide3">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
        <span class="carousel-control-prev-icon"></span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
        <span class="carousel-control-next-icon"></span>
      </button>
    </div>
  </section>  <!-- MAIN -->  <main class="container">
    <h2 id="destacados">Productos Destacados</h2>
    <div class="row d-flex flex-wrap">
      <div class="card col-md-3">
        <img src="https://via.placeholder.com/150" class="card-img-top" alt="producto1">
        <div class="card-body">
          <h5 class="card-title">Producto 1</h5>
          <p class="card-text">Breve descripción del producto.</p>
          <p class="text-primary">$1000</p>
        </div>
      </div>
      <div class="card col-md-3">
        <img src="https://via.placeholder.com/150" class="card-img-top" alt="producto2">
        <div class="card-body">
          <h5 class="card-title">Producto 2</h5>
          <p class="card-text">Breve descripción del producto.</p>
          <p class="text-primary">$2000</p>
        </div>
      </div>
    </div><h2 id="ofertas" class="mt-4">Ofertas</h2>
<div class="row d-flex flex-wrap">
  <div class="card col-md-3">
    <img src="https://via.placeholder.com/150" class="card-img-top" alt="oferta1">
    <div class="card-body">
      <h5 class="card-title">Oferta 1</h5>
      <p class="card-text">Breve descripción del producto en oferta.</p>
      <p class="text-danger">$800</p>
    </div>
  </div>
</div>

  </main>  <!-- FOOTER -->  <footer class="bg-dark text-white text-center p-3 mt-4">
    <p>© 2025 Mi Tienda Online</p>
    <a href="#" class="text-white me-2"><i class="bi bi-facebook"></i></a>
    <a href="#" class="text-white"><i class="bi bi-instagram"></i></a>
  </footer>  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script></body></html>