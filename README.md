<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ecomoda | Moda con Estilo</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Montserrat', sans-serif;
      background-color: #121212;
      color: #e0e0e0;
      line-height: 1.6;
    }
    header {
      background-color: #1f1f1f;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #333;
    }
    .logo {
      font-size: 1.8em;
      font-weight: 700;
      color: #fff;
    }
    nav a {
      color: #ccc;
      text-decoration: none;
      margin-left: 20px;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #fff;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1600180758890-b43d0f107d5a?auto=format&fit=crop&w=1400&q=80') no-repeat center center/cover;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
    }
    .hero h1 {
      font-size: 3em;
      background-color: rgba(0,0,0,0.6);
      padding: 20px;
      border-radius: 10px;
    }
    section {
      padding: 60px 40px;
    }
    .about, .products, .testimonials, .contact {
      max-width: 1000px;
      margin: auto;
    }
    .about h2, .products h2, .testimonials h2, .contact h2 {
      font-size: 2em;
      margin-bottom: 20px;
      color: #fff;
    }
    .about p {
      font-size: 1.1em;
      color: #ccc;
    }
    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .product {
      background-color: #1e1e1e;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      border-radius: 10px;
    }
    .product h3 {
      margin-top: 10px;
      color: #fff;
    }
    .testimonials blockquote {
      font-style: italic;
      color: #bbb;
      border-left: 4px solid #444;
      margin: 20px 0;
      padding-left: 20px;
    }
    .contact form {
      display: flex;
      flex-direction: column;
    }
    .contact input, .contact textarea {
      padding: 10px;
      margin-bottom: 15px;
      background-color: #2a2a2a;
      border: 1px solid #444;
      color: #fff;
      border-radius: 5px;
    }
    .contact button {
      background-color: #444;
      color: #fff;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    .contact button:hover {
      background-color: #666;
    }
    footer {
      background-color: #1a1a1a;
      color: #777;
      text-align: center;
      padding: 20px 10px;
      border-top: 1px solid #333;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Ecomoda</div>
    <nav>
      <a href="#about">Sobre Nosotros</a>
      <a href="#products">Colección</a>
      <a href="#testimonials">Testimonios</a>
      <a href="#contact">Contacto</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Diseño, elegancia y poder en cada prenda</h1>
  </section>

  <section class="about" id="about">
    <h2>Sobre Ecomoda</h2>
    <p>Ecomoda es una marca icónica nacida en el corazón de Bogotá, Colombia. Fusionamos elegancia clásica con tendencias contemporáneas, creando colecciones que empoderan y transforman. Con raíces en la tradición familiar y una visión moderna, vestimos a quienes quieren destacar con autenticidad.</p>
  </section>

  <section class="products" id="products">
    <h2>Colección Destacada</h2>
    <div class="products-grid">
      <div class="product">
        <img src="https://source.unsplash.com/300x400/?fashion" alt="Producto 1">
        <h3>Blazer Ejecutivo</h3>
      </div>
      <div class="product">
        <img src="https://source.unsplash.com/300x400/?clothing" alt="Producto 2">
        <h3>Vestido de Noche</h3>
      </div>
      <div class="product">
        <img src="https://source.unsplash.com/300x400/?apparel" alt="Producto 3">
        <h3>Camisa Casual</h3>
      </div>
    </div>
  </section>

  <section class="testimonials" id="testimonials">
    <h2>Testimonios</h2>
    <blockquote>"Ecomoda me hizo sentir poderosa. Sus diseños son únicos y de calidad inigualable." – Catalina A.</blockquote>
    <blockquote>"Una experiencia de lujo. Atención al detalle en cada prenda." – Jorge E.</blockquote>
  </section>

  <section class="contact" id="contact">
    <h2>Contáctanos</h2>
    <form>
      <input type="text" placeholder="Nombre" required />
      <input type="email" placeholder="Correo electrónico" required />
      <textarea rows="5" placeholder="Tu mensaje" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Ecomoda. Todos los derechos reservados.</p>
    <p>Síguenos en redes sociales: Instagram | Facebook | Twitter</p>
  </footer>
</body>
</html>
