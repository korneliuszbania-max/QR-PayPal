<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My QR Page</title>
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
    <h1>Welcome!</h1>
    <p>This page appears when you scan my QR code.</p>

    <img src="Unknown-1.jpg">

    <p>If you’d like to support me, just click the button below 👇</p>
    <a class="button" href="https://www.paypal.com/paypalme/yourname" target="_blank">
      Support me on PayPal
    </a>
  </div>
</body>
</html>
