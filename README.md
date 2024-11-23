<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Biología Básica</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #e8f5e9;
      color: #333;
    }
    header {
      background-color: #2e7d32;
      color: white;
      padding: 10px 20px;
      text-align: center;
    }
    nav {
      background-color: #388e3c;
      padding: 10px;
      display: flex;
      justify-content: center;
      gap: 15px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 20px;
      max-width: 800px;
      margin: auto;
    }
    footer {
      background-color: #2e7d32;
      color: white;
      text-align: center;
      padding: 10px;
      position: fixed;
      width: 100%;
      bottom: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenidos a Biología Básica</h1>
    <p>Aprende de forma fácil y divertida</p>
  </header>
  <nav>
    <a href="#celulas">Células</a>
    <a href="#genetica">Genética</a>
    <a href="#ecosistemas">Ecosistemas</a>
  </nav>
  <section id="celulas">
    <h2>¿Qué es una célula?</h2>
    <p>La célula es la unidad básica de la vida. Todos los organismos vivos están formados por una o más células.</p>
  </section>
  <section id="genetica">
    <h2>Genética Básica</h2>
    <p>La genética estudia cómo se transmiten las características de padres a hijos a través de los genes.</p>
  </section>
  <section id="ecosistemas">
    <h2>Ecosistemas</h2>
    <p>Un ecosistema es una comunidad de organismos que interactúan con su entorno físico.</p>
  </section>
  <footer>
    © 2024 Biología Básica. Todos los derechos reservados.
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
section {
  max-width: 800px;
  margin: auto;
  padding: 20px;
}
@media (max-width: 768px) {
  section {
    padding: 10px;
  }
}
