```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Redes Sociais</title>

  <!-- Ícones -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      background-image: linear-gradient(#6b80f7, #4b3bfd);
      height: 100vh;
      color: #fff;
    }

    /* Cabeçalho */
    .header {
      background: linear-gradient(#6b80f7, #6b80f7);
      padding: 30px;
      color: #000000;
    }

    /* Linha divisória estilizada */
    .divider {
      width: 100%;
      height: 15px;
      margin: 1px auto;
      background: linear-gradient(rgba(0, 0, 0, 0.3), #03030300);
      border-radius: 0px;
    }

    /* Container de ícones */
    .social-links {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 100px; /* controla a distância entre ícones */
      margin-top: 40px;
    }

    /* Estilo dos links */
    .social-links a {
      text-decoration: none;
      color: #e4e4e4;
      font-size: 28px;
      transition: 0.3s;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    /* Cores no hover (personalizadas por rede) */
    .social-links a:hover { transform: scale(1.1); }
    .social-links a:nth-child(1):hover { color: #000; }     /* X */
    .social-links a:nth-child(2):hover { color: #ff1664; }  /* Instagram */
    .social-links a:nth-child(3):hover { color: #FF0000; }  /* YouTube */
  </style>
</head>

<body>
  <div class="header">
    <h1>Social Sites</h1>
  </div>

  <div class="divider"></div>

  <div class="social-links">
    <a href="https://www.twitter.com/seuusuario" target="_blank">
      <i class="fa-brands fa-x-twitter"></i>
    </a>
    <a href="https://www.instagram.com/seuusuario" target="_blank">
      <i class="fa-brands fa-instagram"></i> Instagram
    </a>
    <a href="https://www.youtube.com/seuusuario" target="_blank">
      <i class="fa-brands fa-youtube"></i> YouTube
    </a>
  </div>
</body>
</html>
```
