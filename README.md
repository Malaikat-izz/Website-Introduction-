<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Malaikat Izz - Cyber TKJ</title>
  <style>
    body {
      background-color: #0f0f0f;
      color: #00ff99;
      font-family: 'Courier New', Courier, monospace;
      padding: 20px;
    }

    .container {
      max-width: 800px;
      margin: auto;
      text-align: center;
    }

    .logo {
      width: 120px;
      margin-bottom: 20px;
    }

    .glitch {
      font-size: 2.5rem;
      color: #00ff99;
      position: relative;
      display: inline-block;
    }

    .glitch::before,
    .glitch::after {
      content: attr(data-text);
      position: absolute;
      left: 0;
      width: 100%;
      overflow: hidden;
    }

    .glitch::before {
      animation: glitchTop 1s infinite linear alternate-reverse;
      color: #ff00c8;
      top: -2px;
    }

    .glitch::after {
      animation: glitchBottom 1s infinite linear alternate-reverse;
      color: #00ffff;
      top: 2px;
    }

    @keyframes glitchTop {
      0% { clip-path: inset(0 0 85% 0); }
      20% { clip-path: inset(10% 0 75% 0); }
      40% { clip-path: inset(20% 0 55% 0); }
      60% { clip-path: inset(30% 0 30% 0); }
      80% { clip-path: inset(40% 0 20% 0); }
      100% { clip-path: inset(50% 0 0 0); }
    }

    @keyframes glitchBottom {
      0% { clip-path: inset(85% 0 0 0); }
      20% { clip-path: inset(75% 0 10% 0); }
      40% { clip-path: inset(55% 0 20% 0); }
      60% { clip-path: inset(30% 0 30% 0); }
      80% { clip-path: inset(20% 0 40% 0); }
      100% { clip-path: inset(0 0 50% 0); }
    }

    p {
      line-height: 1.8;
      text-align: justify;
      margin-top: 20px;
    }

    .contact {
      margin-top: 30px;
    }

    a {
      color: #00ffff;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="https://g.top4top.io/p_3381neh7a0.png" alt="Logo" class="logo" />
    <h1 class="glitch" data-text="Malaikat Izz - Cyber TKJ">Malaikat Izz - Cyber TKJ</h1>
    
    <p>
      Malaikat Izz, yang dulunya dikenal sebagai Malaikat Galau, adalah sosok yang pernah menjadi bagian dari grup hacker misterius bernama xsvshacker. Ia mulai meretas sejak 2017 dengan niat awal iseng dan pembelajaran mandiri. Kemampuan yang terus diasah melalui platform seperti YouTube menjadikannya salah satu individu yang memahami celah keamanan digital secara otodidak.
    </p>

    <p>
      Nama "Malaikat Galau" sempat tercatat dalam beberapa aksi deface situs pada masa awal perjalanannya. Namun kini, dengan identitas baru "Malaikat Izz", ia bertransformasi menjadi seorang white hat hacker yang fokus pada edukasi dan pengujian keamanan sistem tanpa merusak. Ia adalah bagian dari generasi baru yang peduli dengan dunia siber namun lebih memilih berjalan dalam diam.
    </p>

    <div class="contact">
      <h3>Contact Us</h3>
      <p>
        Telegram: <a href="https://t.me/izz404">https://t.me/izz404</a><br>
        GitHub: <a href="https://github.com/Malaikatizz404">https://github.com/Malaikatizz404</a>
      </p>
    </div>
  </div>
</body>
</html>
