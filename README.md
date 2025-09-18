<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My QR Page</title>
  <style>
    body { 
      font-family: Arial, sans-serif; 
      text-align: center; 
      padding: 20px; 
      background: #f5f5f5;
      margin: 0;
      transition: background 0.3s, color 0.3s;
    }
    .card {
      background: white;
      padding: 25px;
      border-radius: 16px;
      max-width: 600px;
      margin: auto;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: background 0.3s, color 0.3s;
    }
    img { 
      max-width: 100%; 
      height: auto;
      margin: 20px auto;
      display: block;
      border-radius: 12px; 
    }
    h1 {
      color: #333;
      font-size: 2em;
      margin-bottom: 10px;
      transition: color 0.3s;
    }
    p {
      color: #555;
      line-height: 1.6;
      font-size: 1.1em;
      margin: 15px 0;
      transition: color 0.3s;
    }
    a.button {
      display: inline-block;
      margin-top: 20px;
      padding: 14px 24px;
      background: #0070ba;
      color: white;
      text-decoration: none;
      font-size: 1.2em;
      font-weight: bold;
      border-radius: 10px;
      transition: background 0.3s;
    }
    a.button:hover {
      background: #005c95;
    }

    /* Dark mode */
    @media (prefers-color-scheme: dark) {
      body {
        background: #121212;
        color: #ddd;
      }
      .card {
        background: #1e1e1e;
        box-shadow: 0 4px 12px rgba(0,0,0,0.6);
      }
      h1 {
        color: #fff;
      }
      p {
        color: #ccc;
      }
    }

    /* Mobile adjustments */
    @media (max-width: 600px) {
      .card {
        padding: 20px;
      }
      h1 {
        font-size: 1.6em;
      }
      p {
        font-size: 1em;
      }
      a.button {
        font-size: 1em;
        width: 100%;
        padding: 14px 0;
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Welcome!</h1>
    <p>This page appears when you scan my QR code.</p>

    <img src="https://via.placeholder.com/400" alt="Sample image">

    <p>If you’d like to support me, just click the button below 👇</p>
    <a class="button" href="https://www.paypal.com/paypalme/yourname" target="_blank">
      Support me on PayPal
    </a>
  </div>
</body>
</html>
