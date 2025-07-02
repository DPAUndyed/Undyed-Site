<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>UNDYED | Moda en gris</title>
  <style>
    :root {
      --gris-oscuro: #1c1c1c;
      --gris-medio: #444;
      --gris-claro: #ccc;
      --blanco: #f4f4f4;
    }

    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background: var(--blanco);
      color: var(--gris-oscuro);
    }

    header {
      background: var(--gris-oscuro);
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    nav {
      background: var(--gris-medio);
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 15px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 8px 15px;
      border-radius: 5px;
      transition: background 0.3s;
    }

    nav a:hover {
      background: var(--gris-claro);
      color: var(--gris-oscuro);
    }

    section {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 30px;
    }

    .categorias {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
      gap: 20px;
    }

    .categoria {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
      cursor: pointer;
      transition: transform 0.2s;
    }

    .categoria:hover {
      transform: scale(1.05);
    }

    .simulacion-img {
      width: 100%;
      height: 140px;
      background: linear-gradient(135deg, #bbb, #eaeaea);
      border-radius: 8px;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

  <header>
    <h1>UNDYED</h1>
    <p>Moda sin teñir. Minimalismo puro.</p>
  </header>

  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#tienda">Tienda</a>
    <a href="#favoritos">Favoritos</a>
    <a href="#carrito">Carrito</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="inicio">
    <h2>Categorías destacadas</h2>
    <div class="categorias">
      <div class="categoria">
        <div class="simulacion-img"></div>
        Hombre
      </div>
      <div class="categoria">
        <div class="simulacion-img"></div>
        Mujer
      </div>
      <div class="categoria">
        <div class="simulacion-img"></div>
        Niños
      </div>
      <div class="categoria">
        <div class="simulacion-img"></div>
        Oversized
      </div>
      <div class="categoria">
        <div class="simulacion-img"></div>
        Long Sleeve
      </div>
      <div class="categoria">
        <div class="simulacion-img"></div>
        Caps
      </div>
    </div>
  </section>

</body>
</html>
