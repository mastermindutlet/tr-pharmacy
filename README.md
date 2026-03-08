<!DOCTYPE html>
<html>
<head>
<title>TR Pharmacy</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
<h2>TR Pharmacy Demo</h2>

<!-- POS Sale Section -->
<input id="barcode" placeholder="Scan / Enter Barcode">
<input id="qty" placeholder="Qty">
<button onclick="addSale()">Add Sale</button>

<table>
<tr><th>Medicine</th><th>Price</th><th>Qty</th><th>Total</th></tr>
<tbody id="sale-list"></tbody>
</table>

<h3 id="total">Total Sale: 0</h3>

</div>
<script src="script.js"></script>
</body>
</html>
