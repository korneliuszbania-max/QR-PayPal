<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Płatność PayPal</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 40px;
      background: linear-gradient(135deg, #f0f4f9, #d9e6f2);
      color: #333;
    }
    .card {
      background: white;
      max-width: 500px;
      margin: auto;
      padding: 30px;
      border-radius: 16px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.1);
    }
    img {
      max-width: 180px;
      margin-bottom: 20px;
    }
    h1 {
      font-size: 26px;
      margin-bottom: 15px;
    }
    p {
      font-size: 18px;
      margin-bottom: 25px;
    }
    a.pay-btn {
      display: inline-block;
      padding: 15px 30px;
      background-color: #0070ba;
      color: white;
      text-decoration: none;
      font-size: 18px;
      font-weight: bold;
      border-radius: 10px;
      transition: 0.3s;
    }
    a.pay-btn:hover {
      background-color: #005c97;
    }
  </style>
</head>
<body>
  <div class="card">
    <!-- Wstaw tutaj nazwę swojego obrazka -->
    <img src="logo.png" alt="Moje logo">
    <h1>Dziękujemy za wsparcie!</h1>
    <p>Kliknij poniższy przycisk, aby dokonać płatności przez PayPal:</p>
    <!-- Podmień link na swój PayPal.Me -->
    <a class="pay-btn" href="https://www.paypal.com/paypalme/TWOJA_NAZWA/50" target="_blank">
      Zapłać 50 PLN
    </a>
  </div>
</body>
</html>
