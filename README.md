<!DOCTYPE html><html lang="es"><head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Diseño Responsive</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }body {
  font-family: 'Roboto', sans-serif;
  padding: 20px;
}

header {
  background-color: #333;
  color: white;
  padding: 10px;
  text-align: center;
}

nav {
  display: flex;
  justify-content: space-around;
  background-color: #555;
  padding: 10px;
}

nav a {
  color: white;
  text-decoration: none;
}

.container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.item {
  background-color: #ddd;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
  margin-top: 20px;
}

@media (max-width: 600px) {
  nav {
    flex-direction: column;
    align-items: center;
  }
}

  </style>
</head><body>
  <header>
    <h1>Mi Sitio Responsive</h1>
  </header>  <nav>
    <a href="#">Inicio</a>
    <a href="#">Servicios</a>
    <a href="#">Contacto</a>
  </nav>  <main class="container">
    <div class="item">Elemento 1</div>
    <div class="item">Elemento 2</div>
    <div class="item">Elemento 3</div>
    <div class="item">Elemento 4</div>
  </main>  <footer>
    <p>© 2025 Mi Sitio Responsive</p>
  </footer>
</body></html>