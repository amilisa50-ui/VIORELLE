<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VIORELLE · Belleza suave</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #f5ecff, #ffffff);
      color: #4a3f55;
    }
    header {
      background: linear-gradient(90deg, #cdb4ff, #e7d9ff);
      color: #4a3f55;
      padding: 25px 15px;
      text-align: center;
      border-bottom-left-radius: 30px;
      border-bottom-right-radius: 30px;
    }
    header h1 {
      margin: 0;
      font-size: 2.2rem;
    }
    header p {
      margin-top: 8px;
      font-size: 1rem;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 18px;
      margin-top: 15px;
      flex-wrap: wrap;
    }
    nav a {
      color: #6a4c93;
      text-decoration: none;
      font-weight: 600;
      background: white;
      padding: 6px 14px;
      border-radius: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.08);
    }
    section {
      padding: 45px 20px;
      max-width: 1000px;
      margin: auto;
    }
    section h2 {
      text-align: center;
      color: #6a4c93;
      margin-bottom: 20px;
    }
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
    }
    .card {
      background: white;
      border-radius: 20px;
      padding: 20px;
      box-shadow: 0 8px 20px rgba(106,76,147,0.15);
      text-align: center;
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: translateY(-6px);
    }
    .card img {
      width: 100%;
      border-radius: 16px;
    }
    .card h3 {
      margin-top: 15px;
      color: #6a4c93;
    }
    .card p {
      font-size: 0.95rem;
    }
    .card button {
      margin-top: 12px;
      padding: 10px 18px;
      border: none;
      border-radius: 20px;
      background: linear-gradient(90deg, #cdb4ff, #b8a1ff);
      color: white;
      font-weight: 600;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    }
    footer {
      background: #f0e6ff;
      color: #6a4c93;
      text-align: center;
      padding: 25px 15px;
      border-top-left-radius: 30px;
      border-top-right-radius: 30px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>💜 VIORELLE 💜</h1>
    <p>soft beauty • real glow ✨🫧</p>
    <nav>
      <a href="#inicio">🏠 Inicio</a>
      <a href="#productos">🧁 Productos</a>
      <a href="#nosotros">🌸 Nosotros</a>
      <a href="#contacto">📩 Contacto</a>
    </nav>
  </header>

  <section id="inicio">
    <h2>Bienvenida 🫶✨</h2>
    <p style="text-align:center;">Descubre productos de belleza creados con amor, ingredientes suaves y una vibra totalmente cute 💜🫧</p>
  </section>

  <section id="productos">
    <h2>Nuestros Productos 🧁💄</h2>
    <div class="productos">
      <div class="card">
        <img src="https://i.pinimg.com/736x/4e/ec/8c/4eec8c8536a7e3bd0f3d1b81fdec749d.jpg" alt="Gloss VIORELLE Star Kiss">
        <h3>Star Kiss 🍓✨</h3>
        <p><strong>Aroma:</strong> fresa suave 🍓<br>
        Gloss transparente con <strong>micro‑glitter sutil</strong> que aporta brillo natural sin exagerar. Hidratante, ligero y cómodo para uso diario.</p>
        <a href="https://wa.me/50300000000" target="_blank"><button>💬 Comprar por WhatsApp</button></a>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x200" alt="Crema facial">
        <h3>Crema Facial 🌸</h3>
        <p>Suave, ligera y perfecta para tu piel bonita.</p>
        <a href="https://wa.me/50300000000" target="_blank"><button>💬 Comprar por WhatsApp</button></a>
      </div>
    </div>
  </section>

  <section id="nosotros">
    <h2>Sobre Nosotros 🌷</h2>
    <p style="text-align:center;">Somos una marca joven, soñadora y creativa. Creemos en la belleza real, cute y consciente 💜✨</p>
  </section>

  <section id="contacto">
    <h2>Contacto 📱💌</h2>
    <p style="text-align:center;">
      💜 Instagram: <strong><a href="https://www.instagram.com/viorelle.beauty" target="_blank" style="color:#6a4c93; text-decoration:none;">@viorelle.glow</a></strong><br>
      💬 WhatsApp: <strong>+503 6070-2389   +503 7928-1652  +503 7703-0611</strong>
    </p>
  </section>

  <footer>
    <p>© 2025 VIORELLE | Hecho con 💜</p>
  </footer>

</body>
</html>
