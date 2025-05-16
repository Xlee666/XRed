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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #111;
  color: #fff;
}
header {
  background: #222;
  padding: 20px;
  text-align: center;
}
header h1 {
  font-size: 2.5rem;
  color: #f00;
}
nav a {
  margin: 0 15px;
  color: #ccc;
  text-decoration: none;
}
.hero {
  background: linear-gradient(to bottom, #111, #222);
  height: 70vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.hero h2 {
  font-size: 3rem;
  margin-bottom: 10px;
}
.hero button {
  margin-top: 20px;
  padding: 10px 20px;
  background: #f00;
  border: none;
  color: white;
  font-weight: bold;
  cursor: pointer;
}
.productos-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  padding: 20px;
}
.producto {
  background: #222;
  padding: 15px;
  border-radius: 8px;
  text-align: center;
}
.producto img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}
footer {
  background: #111;
  text-align: center;
  padding: 20px;
  color: #666;
}
form {
  display: flex;
  flex-direction: column;
  padding: 20px;
  max-width: 500px;
  margin: auto;
}
form input, form textarea {
  margin-bottom: 10px;
  padding: 10px;
  border: none;
  border-radius: 4px;
}
form button {
  background: #f00;
  color: white;
  border: none;
  padding: 10px;
  cursor: pointer;
}
