<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Shop Đồ Nội Thất</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>🪑 Cửa Hàng Nội Thất</h1>

  <div class="product-list">
    <div class="product">
      <img src="https://via.placeholder.com/150" alt="Ghế Sofa">
      <h3>Ghế Sofa</h3>
      <p>Giá: 5.000.000đ</p>
      <button onclick="addToCart('Ghế Sofa', 5000000)">Thêm vào giỏ</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/150" alt="Bàn Gỗ">
      <h3>Bàn Gỗ</h3>
      <p>Giá: 3.000.000đ</p>
      <button onclick="addToCart('Bàn Gỗ', 3000000)">Thêm vào giỏ</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/150" alt="Tủ Quần Áo">
      <h3>Tủ Quần Áo</h3>
      <p>Giá: 4.500.000đ</p>
      <button onclick="addToCart('Tủ Quần Áo', 4500000)">Thêm vào giỏ</button>
    </div>
  </div>

  <div class="cart">
    <h2>🛒 Giỏ Hàng</h2>
    <ul id="cart-items"></ul>
    <p><strong>Tổng tiền:</strong> <span id="total">0</span> đ</p>
  </div>

  <script src="script.js"></script>
</body>
</html># Noi_that.htlm
