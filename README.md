# One-million-barber-shop
tienda de productos de barberia
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>One Miller Barber Shop Supply</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #1c1c1c;
      color: #fff;
    }

    header {
      background: #000;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: #e0b000;
    }

    nav {
      background: #333;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background: url('https://scontent.fgua1-3.fna.fbcdn.net/v/t39.30808-6/489940554_657006767257156_3237271357075334672_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=833d8c&_nc_ohc=64cBe3ycGQUQ7kNvwEddvjG&_nc_oc=AdnI3rmzoOnDQX6uIIaN33AakhaW_0xUDqUQ4a2u9KyAU2rJrxW5LwHgTsNovHWr-m-lWYCr15mhtuuFOtPZcYo8&_nc_zt=23&_nc_ht=scontent.fgua1-3.fna&_nc_gid=UxRFS0rX3UX73cGp7lmlZg&oh=00_AfHVV1TzFqoXClY8awQ1KdZYi2rpS7ylM1l6e5nAoUF4TQ&oe=67FB6FE1') no-repeat center center;
      background-size: contain;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .hero h2 {
      font-size: 2em;
      background-color: rgba(0, 0, 0, 0.6);
      display: inline-block;
      padding: 10px 20px;
      border-radius: 10px;
    }

    .section {
      padding: 40px 20px;
      text-align: center;
    }

    .section h3 {
      font-size: 1.8em;
      color: #e0b000;
      margin-bottom: 20px;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .product {
      background: #2a2a2a;
      padding: 20px;
      width: 250px;
      border-radius: 10px;
    }

    .product img {
      width: 100%;
      border-radius: 5px;
    }

    .product h4 {
      margin: 10px 0 5px;
    }

    .contact {
      background: #111;
      padding: 30px 20px;
      text-align: center;
    }

    .contact p {
      margin: 10px 0;
    }

    footer {
      background: #000;
      text-align: center;
      padding: 10px;
      font-size: 0.9em;
      color: #aaa;
    }

    a.whatsapp-btn {
      display: inline-block;
      background: #25d366;
      color: #fff;
      padding: 10px 20px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>ONE MILLER BARBER SHOP SUPPLY</h1>
  </header>

  <nav>
    <a href="#productos">Productos</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <div class="hero">
    <h2>¡Todo para el barbero moderno en un solo lugar!</h2>
  </div>

  <section id="productos" class="section">
    <h3>Productos Destacados</h3>
    <div class="products">
      <!-- Producto 1 -->
      <div class="product">
        <img src="https://www.laesquinadelpeinador.com/mods/html/fil/Model/Product/2205/thumb_03_12567_0ec_1_copy.jpg.webp" alt="Máquina de Corte">
        <h4>Máquina de Corte Pro</h4>
        <p>Q850.00</p>
      </div>
      
      <!-- Producto 2 -->
      <div class="product">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTNZrGAfcnAuGQ-h4foxTY7-V09GpnFrkMJew&s" alt="Cera para Cabello">
        <h4>Cera Mate Fuerte</h4>
        <p>Q45.00</p>
      </div>
      
      <!-- Producto 3 -->
      <div class="product">
        <img src="https://m.media-amazon.com/images/I/61-W7u3LO4L._SL1500_._SX600_.jpg" alt="Navaja Clásica">
        <h4>Navaja Clásica</h4>
        <p>Q120.00</p>
      </div>
      
      <!-- Producto 4 (a rellenar) -->
      <div class="product">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR6VRb10dtyzWXUxDFppc9CyKuGntHzf45teA&s" alt="tijeras">
        <h4>Nombre del producto 1</h4>
        <p>Q00.00</p>
      </div>
      
      <!-- Producto 5 (a rellenar) -->
      <div class="product">
        <img src="data:image/jpeg;base64,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" alt="cremas">
        <h4>Nombre del producto 2</h4>
        <p>Q00.00</p>
      </div>
      
      <!-- Producto 6 (a rellenar) -->
      <div class="product">
        <img src="https://www.eurostil.com/wp-content/uploads/2019/05/pulverizadores.png" alt="accesorios">
        <h4>Nombre del producto 3</h4>
        <p>Q00.00</p>
      </div>
    </div>
  </section>

  <section id="contacto" class="contact">
    <h3>Contáctanos</h3>
    <p>📍 Zona 1, Ciudad de Guatemala</p>
    <p>📞 WhatsApp: +502 5123-4567</p>
    <a class="whatsapp-btn" href="https://wa.me/50251234567" target="_blank">Escríbenos por WhatsApp</a>
  </section>

  <footer>
    © 2025 One Miller Barber Shop Supply - Todos los derechos reservados
  </footer>

</body>
</html>

