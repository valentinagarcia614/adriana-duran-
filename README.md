<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Adriana Cristina Durán</title>
  <link rel="stylesheet" href="estilos.css">
</head>
<body>
  <header>
    <h1>Adriana Cristina Durán Agudelo</h1>
  </header>

  <section class="biografia">
    <img src="img/artesana.jpg" alt="Foto de la artesana">
    <div>
      <h2>Historia</h2>
      <p>
        Elaboración de imágenes, llaveros, lapiceros, pulseras tejidas en macramé, etc.
        El local fue fundado hace mucho tiempo inspirado por su madre, quien le enseñó a tejer.
        Desde entonces, lleva años honrando ese legado.
      </p>
    </div>
  </section>

  <section class="productos">
    <h2>Productos artesanales</h2>
    <div class="galeria">
      <div class="producto">
        <img src="img/collar-cedro.jpg" alt="Collar en semilla de cedro">
        <p>Collar en semilla de cedro - $15,000</p>
      </div>
      <div class="producto">
        <img src="img/manillas-cafe.jpg" alt="Manillas recinadas en café">
        <p>Manillas recinadas en café - $12,000</p>
      </div>
      <div class="producto">
        <img src="img/llavero-cafe-libano.jpg" alt="Llavero en café - Líbano Tolima">
        <p>Llavero semillas de café temática Líbano Tolima - $12,000</p>
      </div>
      <div class="producto">
        <img src="img/llavero-toronbolo.jpg" alt="Llavero toronbolo Colombia">
        <p>Llavero toronbolo temática Colombia - $10,000</p>
      </div>
      <div class="producto">
        <img src="img/topitos-frailejon.jpg" alt="Topitos frailejón">
        <p>Topitos de madera temática frailejón - $10,000</p>
      </div>
      <div class="producto">
        <img src="img/portalapiceros.jpg" alt="Portalapiceros">
        <p>Portalapiceros semilla de cedro y guadua - $25,000</p>
      </div>
      <div class="producto">
        <img src="img/imanes-nevera.jpg" alt="Imanes de nevera">
        <p>Imanes de nevera frases y temática Líbano Tolima - $12,000</p>
      </div>
      <div class="producto">
        <img src="img/portallaves-balcon.jpg" alt="Portallaves balcón">
        <p>Porta llaves forma de balcón en madera - $25,000</p>
      </div>
      <div class="producto">
        <img src="img/manillas-macrame.jpg" alt="Manillas tejidas café">
        <p>Manillas de café tejidas en macramé - $10,000</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Adriana Cristina Durán. Artesanía con amor.</p>
  </footer>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #f5f5f5;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #6b4c3b;
  color: #fff;
  text-align: center;
  padding: 1rem;
}

.biografia {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  padding: 2rem;
  align-items: center;
  background-color: #fff;
}

.biografia img {
  max-width: 300px;
  border-radius: 8px;
}

.biografia div {
  flex: 1;
}

.productos {
  padding: 2rem;
}

.productos h2 {
  text-align: center;
  margin-bottom: 1.5rem;
}

.galeria {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.5rem;
}

.producto {
  background: #fff;
  padding: 1rem;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  text-align: center;
}

.producto img {
  width: 100%;
  max-height: 200px;
  object-fit: cover;
  border-radius: 6px;
}

footer {
  background-color: #6b4c3b;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}
