# Mi-tienda-online-
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi Tienda Online</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
    }
    header {
      background-color: #222;
      color: white;
      padding: 10px 0;
    }
    .nav-link {
      color: #ccc !important;
    }
    .nav-link:hover {
      color: white !important;
    }
    .ofertas {
      background-color: #ffeaa7;
      padding: 20px;
    }
    footer {
      background-color: #222;
      color: #aaa;
      padding: 20px 0;
      text-align: center;
    }
    .icono {
      margin: 0 10px;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="container d-flex justify-content-between align-items-center">
      <h1 class="h3">🛍️ Mi Tienda</h1>
      <nav>
        <ul class="nav">
          <li class="nav-item"><a class="nav-link" href="#">Inicio</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Productos</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contacto</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Slider -->
  <div id="carouselEjemplo" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="https://via.placeholder.com/1200x400?text=Bienvenido+a+Mi+Tienda" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="https://via.placeholder.com/1200x400?text=¡Descuentos+Especiales!" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="https://via.placeholder.com/1200x400?text=Nuevos+Productos" class="d-block w-100" alt="...">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselEjemplo" data-bs-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselEjemplo" data-bs-slide="next">
      <span class="carousel-control-next-icon"></span>
    </button>
  </div>

  <!-- Productos destacados -->
  <section class="container mt-5">
    <h2 class="mb-4">Productos Destacados</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card">
          <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="Producto 1">
          <div class="card-body">
            <h5 class="card-title">Producto 1</h5>
            <p class="card-text">$1.999</p>
            <a href="#" class="btn btn-primary">Comprar</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="Producto 2">
          <div class="card-body">
            <h5 class="card-title">Producto 2</h5>
            <p class="card-text">$2.499</p>
            <a href="#" class="btn btn-primary">Comprar</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="Producto 3">
          <div class="card-body">
            <h5 class="card-title">Producto 3</h5>
            <p class="card-text">$999</p>
            <a href="#" class="btn btn-primary">Comprar</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Sección de ofertas -->
  <section class="ofertas mt-5 text-center">
    <h3>🔥 Ofertas Especiales</h3>
    <p>Aprovechá nuestros descuentos por tiempo limitado.</p>
  </section>

  <!-- Footer -->
  <footer class="mt-5">
    <div class="container">
      <p>© 2025 Mi Tienda - Todos los derechos reservados.</p>
      <div>
        <a href="#" class="icono"><i class="bi bi-facebook"></i></a>
        <a href="#" class="icono"><i class="bi bi-instagram"></i></a>
        <a href="#" class="icono"><i class="bi bi-whatsapp"></i></a>
      </div>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
