<!DOCTYPE html><html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>شبیه دیجی‌کالا</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      background: #f5f5f5;
    }
    header {
      background: #d32f2f;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1rem;
      padding: 1rem;
    }
    .product {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .product h3 {
      font-size: 1rem;
      margin: 0.5rem 0;
    }
    .product p {
      color: green;
      font-weight: bold;
      margin-bottom: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>فروشگاه من</h1>
  </header>
  <main class="products">
    <div class="product">
      <img src="https://via.placeholder.com/200x200" alt="محصول ۱">
      <h3>گوشی موبایل سامسونگ</h3>
      <p>۱۲,۵۰۰,۰۰۰ تومان</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x200" alt="محصول ۲">
      <h3>هدفون بلوتوثی شیائومی</h3>
      <p>۱,۲۹۰,۰۰۰ تومان</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x200" alt="محصول ۳">
      <h3>لپ‌تاپ لنوو</h3>
      <p>۳۴,۰۰۰,۰۰۰ تومان</p>
    </div>
  </main>
</body>
</html>
