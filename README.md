<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <title>Moja strona pod QR</title>
  <style>
    body { 
      font-family: Arial, sans-serif; 
      text-align: center; 
      padding: 40px; 
      background: #f5f5f5;
    }
    .card {
      background: white;
      padding: 30px;
      border-radius: 16px;
      max-width: 600px;
      margin: auto;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    img { 
      max-width: 250px; 
      margin: 20px auto;
      display: block;
      border-radius: 12px; 
    }
    h1 {
      color: #333;
    }
    p {
      color: #555;
      line-height: 1.5;
    }
    a.button {
      display: inline-block;
      margin-top: 20px;
      padding: 14px 24px;
      background: #0070ba;
      color: white;
      text-decoration: none;
      font-size: 18px;
      font-weight: bold;
      border-radius: 10px;
      transition: background 0.3s;
    }
    a.button:hover {
      background: #005c95;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Witaj na mojej stronie!</h1>
    <p>To jest strona, która wyświetli się po zeskanowaniu mojego kodu QR.</p>

    <img src="https://via.placeholder.com/250" alt="Obrazek testowy">

    <p>Możesz mnie wesprzeć klikając w przycisk poniżej 👇</p>
    <a class="button" href="https://www.paypal.com/paypalme/twojanazwa" target="_blank">
      Wesprzyj mnie na PayPal
    </a>
  </div>
</body>
</html>
