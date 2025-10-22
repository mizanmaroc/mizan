<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>متجر ميزان | Mizan Shop</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: "Cairo", sans-serif;
      background: #0b0f19;
      color: #fff;
      text-align: center;
    }

    header {
      background: linear-gradient(90deg, #1a2238, #111827);
      padding: 25px 0;
      box-shadow: 0 4px 12px rgba(0,0,0,0.5);
    }

    header h1 {
      color: #ffd700;
      font-size: 28px;
      margin: 0;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 40px auto;
      max-width: 1200px;
      gap: 20px;
    }

    .product {
      background: #141a2e;
      border-radius: 16px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.4);
      width: 260px;
      padding: 20px;
      transition: transform 0.35s ease;
    }

    .product:hover {
      transform: scale(1.05);
    }

    .product img {
      width: 100%;
      border-radius: 12px;
    }

    .product h2 {
      color: #ffdd44;
      font-size: 20px;
      margin: 10px 0 5px 0;
    }

    .product p {
      color: #ccc;
      font-size: 15px;
      margin: 5px 0 15px 0;
    }

    .price {
      font-size: 18px;
      color: #6fe07b;
      margin-bottom: 10px;
    }

    .btn {
      background: #2563eb;
      color: white;
      text-decoration: none;
      padding: 10px 20px;
      border-radius: 8px;
      transition: 0.3s;
      display: inline-block;
    }

    .btn:hover {
      background: #1d4ed8;
    }

    footer {
      margin-top: 40px;
      padding: 20px;
      background: #0f172a;
      color: #aaa;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>🛒 متجر ميزان - Mizan Shop</h1>
  </header>

  <div class="container">
    <div class="product">
      <img src="https://i.imgur.com/bM7L8Xr.png" alt="Product 1">
      <h2>سماعة بلوتوث</h2>
      <p>صوت نقي وبطارية تدوم 10 ساعات</p>
      <div
