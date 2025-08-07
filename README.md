<!DOCTYPE html>
<html>
<head>
  <title>My Online Store</title>
  <style>
    .product {
      border: 1px solid #ccc;
      padding: 10px;
      width: 200px;
      display: inline-block;
      margin: 10px;
      text-align: center;
    }
    button {
      background-color: green;
      color: white;
      border: none;
      padding: 10px;
    }
  </style>
  <script>
    function addToCart(name) {
      alert(name + " ကိုတောင်းဆိုပြီးပြီးပြီ!");
    }
  </script>
</head>
<body>

  <h1>My Store</h1>

  <div class="product">
    <h2>T-Shirt</h2>
    <p>Price: 15,000 Ks</p>
    <button onclick="addToCart('T-Shirt')">Add to Cart</button>
  </div>

  <div class="product">
    <h2>Hat</h2>
    <p>Price: 8,000 Ks</p>
    <button onclick="addToCart('Hat')">Add to Cart</button>
  </div>

</body>
</html>
