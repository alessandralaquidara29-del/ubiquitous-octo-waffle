<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Offerte Amazon</title>
  <style>
    body { margin:0; font-family: Arial; background:#f4f4f4; }
    header { background:#232f3e; color:white; padding:20px; text-align:center; }
    .hero { text-align:center; padding:80px 20px; background:#131921; color:white; }
    .btn {
      background:#ff9900; padding:15px 25px;
      text-decoration:none; color:black;
      font-weight:bold; border-radius:5px;
      display:inline-block; margin-top:15px;
    }
    .container { padding:30px; }
    .products { display:flex; flex-wrap:wrap; justify-content:center; }
    .product {
      background:white; margin:15px; padding:20px;
      border-radius:10px; width:250px; text-align:center;
    }
    .product img { width:100%; border-radius:10px; }
  </style>
</head>
<body>

<header>
  <h1>Offerte Imperdibili</h1>
</header>

<section class="hero">
  <h2>Scopri le migliori offerte su Amazon</h2>
  <p>Sconti aggiornati ogni giorno</p>
  <a href="https://www.amazon.it/?tag=TUO-CODICE" class="btn" target="_blank">
    Vai alle Offerte
  </a>
</section>

<div class="container">
  <h2 style="text-align:center;">🔥 Prodotti Consigliati</h2>

  <div class="products">

    <!-- PRODOTTO 1 -->
    <div class="product">
      <img src="https://amzn.to/4tkGn7b" alt="Prodotto">
      <h3>Cuffie Bluetooth</h3>
      <p>Audio di alta qualità e lunga durata</p>
      <a href="https://amzn.to/4tkGn7b"
         class="btn" target="_blank">
         Acquista su Amazon
      </a>
    </div>

    <!-- PRODOTTO 2 -->
    <div class="product">
      <img src="https://amzn.to/4tqDL7O" alt="Prodotto">
      <h3>Smartwatch</h3>
      <p>Shampoo e benessere</p>
      <a href="https://amzn.to/4tqDL7O"
         class="btn" target="_blank">
         Acquista su Amazon
      </a>
    </div>

    </a>
    </div>

  </div>
</div>

<footer style="background:#232f3e;color:white;text-align:center;padding:20px;">
  <p>Come affiliato Amazon, guadagno dagli acquisti idonei.</p>
</footer>

</body>
</html>
