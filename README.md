<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>THEWOODYSOUNDS</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: url('https://www.transparenttextures.com/patterns/cubes.png'), linear-gradient(to bottom, #a8dadc, #f1faee);
      margin: 0;
      padding: 0;
      color: #1d3557;
    }
    header {
      background-color: #f4a261;
      padding: 40px;
      text-align: center;
      color: #fff;
      font-size: 3rem;
      font-family: 'Comic Sans MS', cursive;
      background-image: url('https://static.wikia.nocookie.net/disney/images/3/3e/Woody_Render.png');
      background-size: 120px;
      background-repeat: no-repeat;
      background-position: left center;
      padding-left: 140px;
    }
    .hero {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 40px;
      background: url('https://i.pinimg.com/originals/7e/f0/8a/7ef08ac979998e4dfb15eb9939b6f73b.jpg') center/cover no-repeat;
      color: white;
      text-shadow: 2px 2px 5px #000;
      font-size: 2rem;
      font-family: 'Comic Sans MS', cursive;
    }
    .products {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 60px 20px;
      gap: 40px;
    }
    .product {
      background-color: #fefae0;
      border: 4px solid #e76f51;
      border-radius: 20px;
      width: 280px;
      text-align: center;
      box-shadow: 8px 8px 20px rgba(0,0,0,0.25);
      transition: transform 0.3s ease;
    }
    .product:hover {
      transform: scale(1.05);
    }
    .product img {
      width: 100%;
      border-top-left-radius: 20px;
      border-top-right-radius: 20px;
    }
    .product h3 {
      margin: 15px 0 10px;
      font-family: 'Comic Sans MS', cursive;
      font-size: 1.4rem;
    }
    .product p {
      padding: 0 15px 20px;
      font-size: 1rem;
    }
    footer {
      background-color: #264653;
      color: #fff;
      text-align: center;
      padding: 25px 0;
      font-size: 1.2rem;
    }
  </style>
</head>
<body>
  <header>
    THEWOODYSOUNDS
  </header>

  <section class="hero">
    ¡Bienvenido al mundo de Woody y la mejor calidad de sonido con AirPods!
  </section>

  <section class="products">
    <div class="product">
      <img src="https://store.storeimages.cdn-apple.com/4982/as-images.apple.com/is/MWP22?wid=532&hei=582&fmt=png-alpha&.v=1591634795000" alt="AirPods Pro" />
      <h3>AirPods Pro</h3>
      <p>Cancelación de ruido, modo ambiente y estuche de carga inalámbrica.</p>
    </div>
    <div class="product">
      <img src="https://store.storeimages.cdn-apple.com/4982/as-images.apple.com/is/MME73?wid=532&hei=582&fmt=png-alpha&.v=1632861342000" alt="AirPods 3ª Gen" />
      <h3>AirPods 3ª Gen</h3>
      <p>Diseño renovado, sonido espacial y mejor duración de batería.</p>
    </div>
    <div class="product">
      <img src="https://store.storeimages.cdn-apple.com/4982/as-images.apple.com/is/MV7N2?wid=532&hei=582&fmt=png-alpha&.v=1551489688005" alt="AirPods 2ª Gen" />
      <h3>AirPods 2ª Gen</h3>
      <p>Conexión instantánea y control por voz con "Oye Siri".</p>
    </div>
  </section>

  <footer>
    &copy; 2025 THEWOODYSOUNDS. Inspirado en Toy Story y Woody.
  </footer>
</body>
</html>
