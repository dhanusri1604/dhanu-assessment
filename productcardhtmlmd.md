<!DOCTYPE html>
<html lang="en">
<head>
<title>Stationary Products</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    margin: 0;
    padding: 30px;
  }

  .page-heading {
    text-align: center;
    font-size: 34px;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 2px;
    color: #ff6f00;
    margin-bottom: 8px;
  }

  .page-subtitle {
    text-align: center;
    font-size: 15px;
    color: #777;
    margin-bottom: 30px;
  }

  .product-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }

  .product-card {
    background-color: #ffffff;
    width: 220px;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    overflow: hidden;
    text-align: center;
    padding-bottom: 15px;
  }

  .product-card img {
    width: 100%;
    height: 160px;
    object-fit: cover;
    display: block;
  }

  .product-name {
    font-size: 17px;
    font-weight: bold;
    margin: 12px 8px 5px 8px;
  }

  .product-description {
    font-size: 13px;
    color: #555;
    margin: 0 12px 8px 12px;
  }

  .product-price {
    font-size: 16px;
    font-weight: bold;
    color: #2e7d32;
    margin-bottom: 12px;
  }

  .buy-now-btn {
    background-color: #ff6f00;
    color: white;
    border: none;
    padding: 8px 20px;
    border-radius: 8px;
    font-size: 14px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }

  .buy-now-btn:hover {
    background-color: #e65100;
  }
</style>
</head>
<body>

  <div class="page-heading">Stationary</div>
  <div class="page-subtitle">Better products for your everyday writing needs</div>

  <div class="product-container">

    <!-- Item 1: Pen -->
    <div class="product-card">
      <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='220' height='160'><rect width='220' height='160' fill='%23FFD54F'/><text x='50%25' y='50%25' font-size='24' text-anchor='middle' dy='.3em' fill='%23333' font-family='Arial'>Pen</text></svg>" alt="Pen">
      <div class="product-name">Smooth Gel Pen</div>
      <p class="product-description">Blue ink, smudge-free writing, comfortable grip.</p>
      <div class="product-price">₹20</div>
      <button class="buy-now-btn">Buy Now</button>
    </div>

    <!-- Item 2: Pencil -->
    <div class="product-card">
      <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='220' height='160'><rect width='220' height='160' fill='%2381D4FA'/><text x='50%25' y='50%25' font-size='24' text-anchor='middle' dy='.3em' fill='%23333' font-family='Arial'>Pencil</text></svg>" alt="Pencil">
      <div class="product-name">HB Wooden Pencil</div>
      <p class="product-description">Dark, clean strokes with strong lead quality.</p>
      <div class="product-price">₹5</div>
      <button class="buy-now-btn">Buy Now</button>
    </div>

    <!-- Item 3: Eraser -->
    <div class="product-card">
      <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='220' height='160'><rect width='220' height='160' fill='%23A5D6A7'/><text x='50%25' y='50%25' font-size='24' text-anchor='middle' dy='.3em' fill='%23333' font-family='Arial'>Eraser</text></svg>" alt="Eraser">
      <div class="product-name">Soft White Eraser</div>
      <p class="product-description">Clean erasing without leaving smudges on paper.</p>
      <div class="product-price">₹8</div>
      <button class="buy-now-btn">Buy Now</button>
    </div>

  </div>

</body>
</html>