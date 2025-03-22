# Perfil de GitHub - CarlosAMDev

Este es un perfil de GitHub interactivo que incluye un botón para alternar entre temas oscuro y claro, animaciones sutiles y un diseño moderno. La estructura está dividida en tres secciones: HTML, CSS y JavaScript.

---

## HTML (index.html)

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Perfil de GitHub - CarlosAMDev</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>CarlosAMDev</h1>
    <button id="theme-toggle"><i class="fas fa-adjust"></i> Cambiar Tema</button>
  </header>
  <div class="container">
    <p class="bio">Desarrollador apasionado, creando soluciones innovadoras y experiencias digitales impactantes.</p>
    
    <!-- Sección de habilidades / lenguajes -->
    <section class="skills">
      <h2>Lenguajes de Programación</h2> <br>
      <span><i class="fab fa-python"></i> Python</span>
      <span><i class="fab fa-html5"></i> HTML</span>
      <span><i class="fab fa-css3-alt"></i> CSS</span>
      <span><i class="fab fa-js"></i> JavaScript</span>
      <span><i class="fab fa-php"></i> PHP</span>
      <span><i class="fab fa-docker"></i> Docker</span>
    </section>
    
    <!-- Sección Sobre Mí en formato de lista -->
    <section class="about">
      <h2>Sobre Mí</h2>
      <ul>
        <li>Soy principiante y estoy en constante aprendizaje.</li>
        <li>Próximamente agregaré una foto personal.</li>
        <li>Apasionado por el desarrollo web y las nuevas tecnologías.</li>
        <li>Me encanta compartir conocimientos y crecer junto a la comunidad.</li>
      </ul>
    </section>
    
    <!-- Sección Información Extra para estilizar la página -->
    <section class="extra">
      <h2>Información Extra</h2>
      <p>Aquí irán futuras actualizaciones y contenido relevante. ¡Mantente atento para novedades y mejoras en el perfil!</p>
    </section>
    
    <!-- Redes sociales -->
    <section class="social-icons">
      <a href="#" title="GitHub"><i class="fab fa-github"></i></a>
      <a href="#" title="X (antes Twitter)"><i class="fa-brands fa-x-twitter"></i></a>
      <a href="#" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
      <a href="#" title="Instagram"><i class="fab fa-instagram"></i></a>
    </section>
  </div>
  <footer>
    &copy; 2025 CarlosAMDev. Todos los derechos reservados.
  </footer>
  
  <script src="script.js"></script>
</body>
</html>
