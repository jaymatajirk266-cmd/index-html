# index-html<!DOCTYPE html>
<html>
<head>
  <title>BA Store</title>
  <style>
    body {
      font-family: Arial;
      text-align: center;
      background: #f5f5f5;
    }
    .product {
      background: white;
      padding: 20px;
      margin: 20px;
      border-radius: 10px;
    }
    button {
      background: black;
      color: white;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
    }
  </style>
</head>

<body>

<h1>🔥 BA Store</h1>

<div class="product">
  <img src="https://via.placeholder.com/200" width="200">
  <h2>Stylish T-Shirt</h2>
  <p>Best quality & comfortable</p>
  <h3>₹349</h3>
  <button onclick="order()">Order Now</button>
</div>

<script>
function order() {
  alert("Order placed! We will contact you.");
}
</script>

</body>
</html>
