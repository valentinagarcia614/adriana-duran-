<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Artesanías Wulaju</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2e9e4; /* fondo beige claro */
      display: flex;
    }

    .container {
      display: flex;
      margin: 20px;
      width: 100%;
      gap: 20px;
    }

    .profile {
      width: 25%;
      background-color: #fff9f5;
      border-radius: 12px;
      box-shadow: 0 2px 12px rgba(0,0,0,0.1);
      padding: 20px;
    }

    .profile img {
      width: 100%;
      border-radius: 12px;
      border: 3px solid #d4a373;
    }

    .profile h2 {
      text-align: center;
      margin: 15px 0 5px;
      color: #6b4f3b;
    }

    .contact-info {
      text-align: center;
      font-size: 0.95em;
      margin-bottom: 15px;
      color: #5a4e42;
    }

    .contact-info a {
      display: block;
      color: #7a5c4b;
      text-decoration: none;
      margin-top: 6px;
    }

    .contact-info a:hover {
      text-decoration: underline;
    }

    .history {
      background-color: #fcefe3;
      padding: 12px;
      border-left: 5px solid #d4a373;
      border-radius: 8px;
    }

    .history strong {
      display: block;
      margin-bottom: 5px;
      color: #a06134;
    }

    .products {
      width: 75%;
    }

    .products h2 {
      margin-bottom: 20px;
      color: #7c4c2c;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
    }

    .product-card {
      background-color: #fffdf9;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.08);
      overflow: hidden;
      display: flex;
      flex-direction: column;
      transition: transform 0.2s;
    }

    .product-card:hover {
      transform: translateY(-5px);
    }

    .product-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }

    .product-card h3 {
      margin: 10px;
      font-size: 1.1em;
      color: #5a3e2b;
    }

    .product-card p {
      margin: 0 10px 10px;
      font-size: 0.9em;
      color: #5f4b3b;
    }

    .product-card button {
      margin: 10px;
      padding: 8px;
      background-color: #a06134;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .product-card button:hover {
      background-color: #874f28;
    }
  </style>
</head>
<body>
<div class="container">
  <!-- Perfil -->
  <div class="profile">
    <img src="../pagina/imagenes/Adriana.png" alt="Foto Adriana Cristina Durán Agudelo">
    <h2>Adriana Cristina Durán Agudelo</h2>
    <div class="contact-info">
      <a href="adrianaduran575@ gmail.com">adrianaduran575@ gmail.com</a>
      <a href="tel:+321 2875536">Tel: +321 2875536</a> 
    </div>
    <div class="history">
      <strong>Historia:</strong>
      <p>Este emprendimiento nació del amor y la enseñanza de una madre que le inculcó el arte de tejer desde niña. Lo que comenzó como una tradición familiar se transformó en una pasión y en un negocio lleno de historia y dedicación. Hoy, el local ofrece creaciones únicas como llaveros, pulseras y detalles decorativos, todos hechos a mano con cariño. Más que vender productos, busca honrar un legado, transmitir emociones y mantener viva la tradición del trabajo artesanal.</p>
    </div>
  </div>
  <!-- Productos -->
  <div class="products">
    <h2>Productos de Artesanías Wulaju</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="../pagina/imagenes/collarsemillacedro.png" alt="Collar en semilla de cedro" />
        <h3>Collar en semilla de cedro</h3>
        <p>Esta hecho en Semilla de cedro, hilo o cuerda encerada, cierres metálicos, aguja.</p>
        <button>Ver más</button>
      </div>
      <div class="product-card">
        <img src="../pagina/imagenes/manillaensemilla.png" alt="Manillas en semilla de café" />
        <h3>Manillas en semilla de café</h3>
        <p>Esta diseñado en Semilla de café, hilo, resina, cierres, aguja.</p>
        <button>Ver más</button>
      </div>
      <div class="product-card">
        <img src="../pagina/imagenes/llaverocafe.png" alt="Llavero en semillas de café" />
        <h3>Llavero en semillas de café</h3>
        <p>Elaborada con  Semilla de café, resina, herraje metálico, argolla, hilo decorativo (opcional).</p>
        <button>Ver más</button>
      </div>
      <div class="product-card">
        <img src="../pagina/imagenes/llaverodetorombolo.png" alt="Llavero en semillas de torombolo " />
        <h3>Llavero en semillas de torombolo </h3>
        <p>Hecho con  Semillas naturales toronbolo, , hilo decorativo, herraje metálico, argolla.</p>
        <button>Ver más</button>
      </div>
      <div class="product-card">
        <img src="../pagina/imagenes/topitosdemadera.png" alt="topitos de madera " />
        <h3>topitos de madera </h3>
        <p> Esta a base Madera, pintura acrílica, base de silicona, pegamento.</p>
        <button>Ver más</button>
      </div>
      <div class="product-card">
        <img src="../pagina/imagenes/portalapiceros.png" alt="porta lapiceros en semilla de cedro " />
        <h3>porta lapiceros en semilla de cedro </h3>
        <p>Diseñado en Semilla de cedro, guadua, pegamento, barniz natural, elementos decorativos (opcional).</p>
        <button>Ver más</button>
      </div>
      <div class="product-card">
        <img src="../pagina/imagenes/imanesdenevera.png" alt="imanes de nevera " />
        <h3>imanes de nevera </h3>
        <p>Madera, pintura acrílica, imán adhesivo, frases impresas o pintadas, pegamento.</p>
        <button>Ver más</button>
      </div>
      <div class="product-card">
        <img src="../pagina/imagenes/portallave.png" alt="Porta llaves " />
        <h3>Porta llaves </h3>
        <p>Hecho en tagua, acrílicos, cola de rata, erraje y resina.</p>
        <button>Ver más</button>
      </div>
      <div class="product-card">
        <img src="../pagina/imagenes/manillaenmacrame.png" alt="Manillas de café en macramé" />
        <h3>Manillas de café en macramé</h3>
        <p>Esta elaborado en semilla de cafe, cuerda macrame, adornos, broche.</p>
        <button>Ver más</button>
      </div>
    </div>
  </div>
</div>
</body>
</html>

      
     

