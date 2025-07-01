# Shoppingone
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Prodotto X - Il tuo prodotto ideale</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f8f9fa;
    }

    header {
      background-color: #007bff;
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2rem;
    }

    nav {
      background-color: #0056b3;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      padding: 15px 20px;
      text-decoration: none;
    }

    nav a:hover {
      background-color: #003f7f;
    }

    .hero {
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url("https://source.unsplash.com/1200x400/?product") center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 80px 20px;
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto;
    }

    .content {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .content h3 {
      margin-bottom: 20px;
      color: #007bff;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .feature {
      background-color: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }

    .feature:hover {
      transform: translateY(-5px);
    }

    .cta {
      text-align: center;
      margin-top: 40px;
    }

    .cta button {
      background-color: #007bff;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 1rem;
      border-radius: 5px;
      cursor: pointer;
    }

    .cta button:hover {
      background-color: #0056b3;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Prodotto X</h1>
    <p>Il prodotto che rivoluzionerà la tua vita</p>
  </header>

  <nav>
    <a href="#caratteristiche">Caratteristiche</a>
    <a href="#acquista">Acquista</a>
    <a href="#contatti">Contatti</a>
  </nav>

  <section class="hero">
    <h2>Scopri Prodotto X</h2>
    <p>Prestazioni eccezionali, design elegante e tecnologia innovativa — tutto in un unico prodotto.</p>
  </section>

  <section class="content" id="caratteristiche">
    <h3>Perché scegliere Prodotto X?</h3>
    <div class="features">
      <div class="feature">
        <h4>Alta qualità</h4>
        <p>Materiali premium e cura dei dettagli per garantire il massimo delle prestazioni.</p>
      </div>
      <div class="feature">
        <h4>Innovazione</h4>
        <p>Un prodotto studiato per rispondere alle esigenze moderne con le migliori tecnologie.</p>
      </div>
      <div class="feature">
        <h4>Facile da usare</h4>
        <p>Interfaccia intuitiva e immediata per una user experience eccellente.</p>
      </div>
    </div>

    <div class="cta" id="acquista">
      <button>Acquista ora</button>
    </div>
  </section>

  <footer id="contatti">
    <p>&copy; 2025 Prodotto X - Tutti i diritti riservati</p>
    <p>Email: info@prodottox.it</p>
  </footer>
</body>
</html>


