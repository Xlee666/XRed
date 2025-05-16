# XRed
666
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>XRed - Moda Urbana</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>XRed</h1>
    <nav>
      <a href="#productos">Productos</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Moda urbana para todos</h2>
    <p>Descubre lo mejor del estilo urbano en XRed.</p>
    <button onclick="scrollToProducts()">Ver productos</button>
  </section>

  <section id="productos">
    <h3>Nuestros productos</h3>
    <div class="productos-container" id="product-list">
      <!-- Aquí se cargarán los productos dinámicamente -->
    </div>
  </section>

  <section id="contacto">
    <h3>Contáctanos</h3>
    <form id="contact-form">
      <input type="text" placeholder="Tu nombre" required />
      <input type="email" placeholder="Tu correo" required />
      <textarea placeholder="Tu mensaje" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 XRed. Todos los derechos reservados.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
