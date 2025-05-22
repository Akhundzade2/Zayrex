<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Satış Saytı</title>
  <style>
    body { font-family: Arial; text-align: center; padding: 50px; }
    .product { border: 1px solid #ccc; padding: 20px; width: 300px; margin: auto; border-radius: 10px; }
    .product h2 { margin: 0 0 10px; }
    .price { font-size: 24px; color: green; margin-bottom: 20px; }
    #paymentForm { display: none; margin-top: 20px; }
    input { display: block; width: 100%; padding: 8px; margin: 10px 0; }
    button { padding: 10px 20px; font-size: 16px; }
  </style>
</head>
<body>

  <div class="product">
    <h2>Proqram A</h2>
    <div class="price">₼10</div>
    <button onclick="showPayment()">Al</button>

    <div id="paymentForm">
      <input type="text" placeholder="Kart nömrəsi" />
      <input type="text" placeholder="Son istifadə tarixi (AA/YY)" />
      <input type="text" placeholder="CVV" />
      <button onclick="submitPayment()">Təsdiqlə</button>
    </div>
  </div>

  <script>
    function showPayment() {
      document.getElementById("paymentForm").style.display = "block";
    }

    function submitPayment() {
      alert("Ödəniş qəbul edildi! (simulyasiya)");
    }
  </script>

</body>
</html>
