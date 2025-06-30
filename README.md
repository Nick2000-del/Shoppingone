# Shoppingone
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shoppingone.com - Dettaglio Prodotto</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: #f8f8f8;
      color: #333;
    }
    header {
      background-color: #ffffff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    header h1 {
      margin: 0;
      font-size: 24px;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: 500;
    }
    nav a:hover {
      color: #b8895c;
    }
    .product {
      display: flex;
      flex-wrap: wrap;
      gap: 40px;
      padding: 40px;
      background-color: #fff;
      border-radius: 8px;
      margin: 40px auto;
      max-width: 1200px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .product img {
      flex: 1 1 400px;
      max-width: 500px;
      border-radius: 8px;
    }
    .product-details {
      flex: 1 1 400px;
    }
    .product-details h2 {
      margin-top: 0;
    }
    .price {
      color: #b8895c;
      font-size: 24px;
      margin: 15px 0;
    }
    .buy-section label {
      display: block;
      margin-top: 10px;
      margin-bottom: 5px;
      font-weight: 500;
    }
    .buy-section select,
    .buy-section input[type="number"] {
      padding: 8px;
      width: 100px;
      margin-bottom: 20px;
    }
    .buy-section button {
      background-color: #b8895c;
      color: #fff;
      border: none;
      padding: 12px 20px;
      cursor: pointer;
      border-radius: 5px;
      font-size: 16px;
    }
    .buy-section button:hover {
      background-color: #a0704e;
    }
    .related {
      margin: 40px auto;
      max-width: 1200px;
      padding: 20px;
    }
    .related h3 {
      margin-bottom: 20px;
    }
    .related-products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .related-products a {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-decoration: none;
      color: #333;
      width: 200px;
      text-align: center;
      overflow: hidden;
      transition: transform 0.3s;
    }
    .related-products a:hover {
      transform: translateY(-5px);
    }
    .related-products img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Shoppingone.com</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Abbigliamento</a>
      <a href="#">Scarpe</a>
      <a href="#">Profumi</a>
      <a href="#">Elettronica</a>
      <a href="#">Contatti</a>
    </nav>
  </header>

  <section class="product">
    <img src="https://source.unsplash.com/600x600?fashion" alt="Prodotto">
    <div class="product-details">
      <h2>Nome Prodotto</h2>
      <p class="price">€99,99</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin nec lectus et nunc pulvinar auctor.</p>
      <div class="buy-section">
        <label for="taglia">Taglia</label>
        <select id="taglia">
          <option>S</option>
          <option>M</option>
          <option>L</option>
          <option>XL</option>
        </select>
        <label for="quantita">Quantità</label>
        <input type="number" id="quantita" value="1" min="1">
        <br>
        <button>Aggiungi al carrello</button>
      </div>
    </div>
  </section>

  <section class="related">
    <h3>Prodotti correlati</h3>
    <div class="related-products">
      <a href="#">
        <img src="https://source.unsplash.com/400x300?shoes" alt="Scarpe">
        <p>Scarpe Trendy</p>
      </a>
      <a href="#">
        <img src="https://source.unsplash.com/400x300?perfume" alt="Profumo">
        <p>Profumo Elegante</p>
      </a>
      <a href="#">
        <img src="https://source.unsplash.com/400x300?electronics" alt="Gadget">
        <p>Nuovo Smartphone</p>
      </a>
    </div>
  </section>

  <footer>
    &copy; 2025 Shoppingone.com - Tutti i diritti riservati
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shoppingone.com - Conferma Ordine</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      background-color: #f8f8f8;
      margin: 0;
      color: #333;
    }
    header {
      background: #fff;
      padding: 20px 40px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 28px;
      color: #b8895c;
    }
    main {
      max-width: 700px;
      margin: 40px auto;
      background: white;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    h2 {
      color: #b8895c;
      margin-bottom: 20px;
    }
    .order-summary {
      text-align: left;
      margin: 20px 0;
    }
    .order-summary table {
      width: 100%;
      border-collapse: collapse;
    }
    .order-summary th, .order-summary td {
      padding: 12px;
      border-bottom: 1px solid #ddd;
    }
    .order-summary th {
      background-color: #f0f0f0;
      text-align: left;
    }
    p {
      font-size: 16px;
      margin-top: 30px;
    }
    footer {
      text-align: center;
      padding: 20px;
      color: #fff;
      background: #333;
      margin-top: 60px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Shoppingone.com</h1>
  </header>

  <main>
    <h2>Grazie per il tuo ordine!</h2>
    <p>Il tuo acquisto è stato completato con successo.</p>

    <section class="order-summary">
      <h3>Riepilogo ordine</h3>
      <table>
        <thead>
          <tr>
            <th>Prodotto</th>
            <th>Quantità</th>
            <th>Prezzo</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Nome Prodotto</td>
            <td>1</td>
            <td>€99,99</td>
          </tr>
          <tr>
            <td>Scarpe Trendy</td>
            <td>1</td>
            <td>€79,99</td>
          </tr>
        </tbody>
      </table>
      <p><strong>Totale: €179,98</strong></p>
    </section>

    <p>Ti invieremo una email di conferma con i dettagli della spedizione.<br />
    Per qualsiasi domanda, contattaci.</p>
  </main>

  <footer>
    &copy; 2025 Shoppingone.com - Tutti i diritti riservati
  </footer>
</body>
</html>
