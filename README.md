# Queen-essences-
Tienda de perfumes para dama 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Perfumes de Ensueño</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Perfumes de Ensueño</h1>
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#productos">Productos</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="inicio" class="hero">
    <h2>Descubre tu aroma perfecto</h2>
    <p>Fragancias exclusivas para cada ocasión</p>
  </section>

  <section id="productos">
    <h2>Nuestros Perfumes</h2>
    <div class="producto">
      <img src="https://via.placeholder.com/150" alt="Perfume 1">
      <h3>Rosa Mística</h3>
      <p>Una fragancia floral con notas de jazmín y rosa.</p>
    </div>
    <div class="producto">
      <img src="https://via.placeholder.com/150" alt="Perfume 2">
      <h3>Oro Oriental</h3>
      <p>Aroma cálido con toques de vainilla y ámbar.</p>
    </div>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <form onsubmit="enviarFormulario(event)">
      <input type="text" placeholder="Tu nombre" required />
      <input type="email" placeholder="Tu correo" required />
      <textarea placeholder="Tu mensaje" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Perfumes de Ensueño</p>
  </footer>

  <script>
    function enviarFormulario(e) {
      e.preventDefault();
      alert("Gracias por contactarnos. Te responderemos pronto.");
    }
  </script>
</body>
</html>
