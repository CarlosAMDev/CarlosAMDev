<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Perfil de GitHub - CarlosAMDev</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
  <style>
    /* Animaciones */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes bounce {
      0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
      40% { transform: translateY(-10px); }
      60% { transform: translateY(-5px); }
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #0d1117;
      color: #c9d1d9;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    header {
      background: #161b22;
      padding: 20px 0;
      text-align: center;
      border-bottom: 1px solid #30363d;
    }
    header h1 {
      margin: 0;
      font-size: 32px;
    }
    .container {
      width: 90%;
      max-width: 1000px;
      margin: 30px auto;
      animation: fadeIn 1s ease-in-out;
    }
    .bio {
      text-align: center;
      margin-bottom: 30px;
      font-size: 18px;
      color: #8b949e;
    }
    /* Sección de habilidades */
    .skills {
      text-align: center;
      margin: 30px 0;
    }
    .skills h2 {
      font-size: 26px;
      margin-bottom: 15px;
      border-bottom: 1px solid #30363d;
      display: inline-block;
      padding-bottom: 5px;
    }
    .skills span {
      display: inline-block;
      background: #21262d;
      padding: 8px 15px;
      margin: 5px;
      border-radius: 5px;
      font-size: 16px;
      transition: transform 0.3s ease;
    }
    .skills span:hover {
      animation: bounce 0.6s;
    }
    .skills i {
      margin-right: 8px;
    }
    /* Sección Sobre Mí */
    .about {
      background: #161b22;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 30px;
      box-shadow: 0 0 10px rgba(255, 255, 255, 0.05);
    }
    .about h2 {
      font-size: 26px;
      margin-bottom: 10px;
      border-bottom: 1px solid #30363d;
      padding-bottom: 10px;
    }
    .about ul {
      list-style-type: disc;
      padding-left: 20px;
      text-align: left;
      max-width: 600px;
      margin: 0 auto;
      color: #c9d1d9;
    }
    /* Sección Información Extra para estilizar la página */
    .extra {
      background: linear-gradient(135deg, #161b22, #0d1117);
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 30px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
    }
    .extra h2 {
      font-size: 26px;
      margin-bottom: 15px;
      text-align: center;
      border-bottom: 1px solid #30363d;
      padding-bottom: 10px;
    }
    .extra p {
      text-align: center;
      font-size: 18px;
      color: #8b949e;
    }
    /* Redes sociales */
    .social-icons {
      text-align: center;
      margin: 30px 0;
    }
    .social-icons a {
      color: #58a6ff;
      font-size: 28px;
      margin: 0 15px;
      transition: color 0.3s ease, transform 0.3s ease;
    }
    .social-icons a:hover {
      color: #1f6feb;
      transform: scale(1.1);
    }
    footer {
      text-align: center;
      margin: 20px 0;
      font-size: 14px;
      color: #8b949e;
    }
  </style>
</head>
<body>
  <header>
    <h1>CarlosAMDev</h1>
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
</body>
</html>
