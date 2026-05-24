<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Jedly | Solicita tu Proyecto</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: white;
      text-align: center;
    }

    header {
      padding: 40px 20px;
    }

    header h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 18px;
      color: #ccc;
    }

    .container {
      max-width: 500px;
      margin: auto;
      background: rgba(0,0,0,0.6);
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0px 0px 20px #00ffcc;
    }

    input, textarea {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: none;
      border-radius: 8px;
    }

    button {
      background: #00c853;
      color: white;
      padding: 12px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      width: 100%;
      font-size: 16px;
    }

    button:hover {
      background: #009624;
    }

    .back {
      margin-top: 20px;
    }

    .back a {
      color: #00e5ff;
      text-decoration: none;
    }

    .back a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>

  <header>
    <h1>🚀 JEDLY</h1>
    <p>Desarrollador de Software | Soluciones Tecnológicas para Empresas</p>
  </header>

  <div class="container">
    <h2>💼 Solicita tu Proyecto</h2>

    <form action="https://formspree.io/f/maqkbjzw" method="POST">
      
      <input type="text" name="nombre" placeholder="Tu nombre" required>
      
      <input type="email" name="email" placeholder="Tu correo" required>

      <textarea name="mensaje" rows="5" placeholder="Describe tu proyecto..." required></textarea>
      
      <button type="submit">🚀 Enviar Solicitud</button>
    
    </form>

    <div class="back">
      <p><a href="https://github.com/JEDLY" target="_blank">⬅ Volver a mi perfil</a></p>
    </div>
  </div>

</body>
</html>
