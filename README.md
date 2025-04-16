<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Viña Outlet Park</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff;
    }

    .header {
      background-color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 1rem 2rem;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    .nav {
      margin-top: 0.5rem;
    }

    .nav a {
      text-decoration: none;
      margin: 0 15px;
      color: #1e1e1e;
      font-weight: bold;
      font-size: 1.7rem;
    }

    .main-banner {
      width: 100%;
      height: 600px;
      background-image: url('https://img.freepik.com/vector-gratis/banner-horizontal-geometrico-diseno-plano_23-2149968375.jpg?t=st=1744828537~exp=1744832137~hmac=76c018c51478f98265c5ac76d6c3153462fed452bbf5e2bc61048250d0796003&w=1060');
      background-size: cover;
      background-position: center;
    }

    .section-title {
      font-size: 2rem;
      font-weight: bold;
      margin: 30px 50px 10px;
      text-align: left;
    }

    .categories-wrapper {
      background-color: #f3e6f9;
      padding: 30px 0;
    }

    .categories {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 30px;
      padding: 0 50px;
      justify-items: center;
    }

    .extra-section {
      padding: 30px 50px 50px;
    }

    .extra-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 30px;
      justify-items: center;
      margin-bottom: 30px;
    }

    .extra-grid-2 {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 30px;
      justify-items: center;
    }

    .category {
      background-color: #fff;
      border-radius: 10px;
      overflow: hidden;
      position: relative;
      width: 100%;
      max-width: 300px;
      aspect-ratio: 1 / 1;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .category img {
      position: absolute;
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
      z-index: 0;
    }

    .category span {
      position: relative;
      z-index: 1;
      background: rgba(0, 0, 0, 0.5);
      color: white;
      text-align: center;
      padding: 10px 20px;
      font-size: 1.6rem;
      font-weight: bold;
      border-radius: 5px;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header class="header">
    <nav class="nav">
      <a href="#">🛍️ Tiendas</a>
      <a href="#">🔆 Panoramas</a>
      <a href="#">📍 Ubicación</a>
    </nav>
  </header>

  <!-- Imagen principal (banner) -->
  <section class="main-banner"></section>

  <!-- Título de sección -->
  <div class="section-title">Productos</div>

  <!-- Categorías principales con fondo lila -->
  <div class="categories-wrapper">
    <section class="categories">
      <div class="category">
        <img src="https://img.freepik.com/foto-gratis/retrato-modelo-elegante-joven-muchacha-ropa-casual-verano-sombrero-marron-maquillaje-natural-vidrios-aislados_158538-8562.jpg?t=st=1744828234~exp=1744831834~hmac=9656c6e33b9c352b105784137522f54a7b1c24ccaa6c4bf69383993c91da6288&w=740" alt="Mujer">
        <span>Mujer</span>
      </div>
      <div class="category">
        <img src="https://img.freepik.com/foto-gratis/hombre-moda-ropa-punto-invierno_158595-4105.jpg?t=st=1744828265~exp=1744831865~hmac=968af3a1d3a6d9bbf33e319d1687029c5bd008c3035c325f011ab90f760bf0d7&w=740" alt="Hombre">
        <span>Hombre</span>
      </div>
      <div class="category">
        <img src="https://img.freepik.com/foto-gratis/retrato-nino-pequeno-lindo-feliz_171337-7112.jpg?t=st=1744828388~exp=1744831988~hmac=0684cfe9b2f302b9387920c31d404f16bb5b038d07c7bb674c9c24f892e9bf1e&w=996" alt="Infantil">
        <span>Infantil</span>
      </div>
      <div class="category">
        <img src="https://img.freepik.com/foto-gratis/diseno-habitacion-relajante-plantas-verdes_23-2149155790.jpg?t=st=1744828355~exp=1744831955~hmac=a48e20060ab71a6d58720d036e11b5507e7d29ab2e5146b16bf8e4f4c5791446&w=900" alt="Deco hogar">
        <span>Deco hogar</span>
      </div>
    </section>
  </div>

  <!-- Título Panoramas -->
  <div class="section-title">Panoramas</div>

  <!-- Más productos -->
  <section class="extra-section">
    <div class="extra-grid">
      <div class="category"><img src="Imagenes/Captura de pantalla 2025-04-16 145522.png" alt="Extra 1"></div>
      <div class="category"><img src="Imagenes/Captura de pantalla 2025-04-16 145920.png" alt="Extra 2"></div>
      <div class="category"><img src="Imagenes/Captura de pantalla 2025-04-16 150012.png" alt="Extra 3"></div>
      <div class="category"><img src="Imagenes/Captura de pantalla 2025-04-16 150054.png" alt="Extra 4"></div>
    </div>
    <div class="extra-grid-2">
      <div class="category"><img src="Imagenes/Captura de pantalla 2025-04-16 150130.png" alt="Extra 5"></div>
      <div class="category"><img src="Imagenes/Captura de pantalla 2025-04-16 150203.png" alt="Extra 6"></div>
    </div>
  </section>

</body>
</html>
