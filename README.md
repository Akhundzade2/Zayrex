<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Online Satış</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 20px;
    }
    .container {
      max-width: 400px;
      margin: auto;
      background: #fff;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product-img {
      width: 100%;
      border-radius: 10px;
    }
    h2 {
      margin-top: 20px;
      font-size: 24px;
    }
    .price {
      color: #27ae60;
      font-size: 22px;
      margin: 10px 0 20px;
    }
    button {
      background: #2980b9;
      color: white;
      border: none;
      padding: 12px 25px;
      font-size: 16px;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background: #1f6691;
    }
    #paymentForm {
      display: none;
      margin-top: 20px;
      text-align: left;
    }
    input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 15px;
    }
  </style>
</head>
<body>

  <div class="container">
    <img src="https://via.placeholder.com/400x200.png?text=Proqram+A" class="product-img" alt="Proqram A">
    <h2>Proqram A</h2>
    <div class="price">₼10</div>
    <button onclick="showPayment()">Satın al</button>

    <div id="paymentForm">
      <input type="text" placeholder="Kart nömrəsi" />
      <input type="text" placeholder="Tarix (AA/YY)" />
      <input type="text" placeholder="CVV" />
      <button onclick="submitPayment()">Təsdiqlə</button>
    </div>
  </div>

  <script>
    function showPayment() {
      document.getElementById("paymentForm").style.display = "block";
    }

    function submitPayment() {
      alert("Təşəkkürlər! Ödəniş simulyasiya olundu.");
    }
  </script>

</body>
</html><!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Online Satış</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 20px;
    }
    .container {
      max-width: 400px;
      margin: auto;
      background: #fff;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product-img {
      width: 100%;
      border-radius: 10px;
    }
    h2 {
      margin-top: 20px;
      font-size: 24px;
    }
    .price {
      color: #27ae60;
      font-size: 22px;
      margin: 10px 0 20px;
    }
    button {
      background: #2980b9;
      color: white;
      border: none;
      padding: 12px 25px;
      font-size: 16px;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background: #1f6691;
    }
    #paymentForm {
      display: none;
      margin-top: 20px;
      text-align: left;
    }
    input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 15px;
    }
  </style>
</head>
<body>

  <div class="container">
    <img src="https://via.placeholder.com/400x200.png?text=Proqram+A" class="product-img" alt="Proqram A">
    <h2>Proqram A</h2>
    <div class="price">₼10</div>
    <button onclick="showPayment()">Satın al</button>

    <div id="paymentForm">
      <input type="text" placeholder="Kart nömrəsi" />
      <input type="text" placeholder="Tarix (AA/YY)" />
      <input type="text" placeholder="CVV" />
      <button onclick="submitPayment()">Təsdiqlə</button>
    </div>
  </div>

  <script>
    function showPayment() {
      document.getElementById("paymentForm").style.display = "block";
    }

    function submitPayment() {
      alert("Təşəkkürlər! Ödəniş simulyasiya olundu.");
    }
  </script>

</body>
</html>
