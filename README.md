<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>iPACQ Solutions - Safety Products</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    .section {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .section h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #e60000;
    }
    .product-row {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .product-box {
      background: #fff;
      display: flex;
      width: 100%;
      max-width: 540px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    }
    .product-img {
      width: 50%;
      height: auto;
      object-fit: cover;
    }
    .product-content {
      padding: 15px;
      width: 50%;
    }
    .product-content h3 {
      margin-top: 0;
    }
    .product-content ul {
      padding-left: 20px;
    }
    .read-more {
      margin-top: 10px;
      display: inline-block;
      background: #e60000;
      color: white;
      padding: 8px 16px;
      text-decoration: none;
      font-size: 14px;
    }
    @media screen and (max-width: 768px) {
      .product-box {
        flex-direction: column;
        max-width: 100%;
      }
      .product-img, .product-content {
        width: 100%;
      }
    }
  </style>
</head>
<body>  <section class="section">
    <h2>Hand Protection</h2>
    <div class="product-row">
      <div class="product-box">
        <img src="images/knitted_gloves.jpg" alt="Knitted Gloves" class="product-img">
        <div class="product-content">
          <h3>Knitted Gloves</h3>
          <ul>
            <li>Comfortable and breathable</li>
            <li>Available in cotton/polyester blends</li>
            <li>Used in general handling and packaging</li>
          </ul>
          <a class="read-more" href="#">Read More</a>
        </div>
      </div><div class="product-box">
    <img src="images/pu_coated_gloves.jpg" alt="PU Coated Gloves" class="product-img">
    <div class="product-content">
      <h3>PU Coated Gloves</h3>
      <ul>
        <li>Excellent grip and dexterity</li>
        <li>Lightweight and durable</li>
        <li>Used in assembly and electronics work</li>
      </ul>
      <a class="read-more" href="#">Read More</a>
    </div>
  </div>
</div>

  </section></body>
</html>
