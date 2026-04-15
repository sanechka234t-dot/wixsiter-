<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>WixSiter — Донаты</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: linear-gradient(135deg, #0f172a, #020617);
  color: white;
}

header {
  text-align: center;
  padding: 30px;
  font-size: 28px;
  font-weight: bold;
  background: rgba(0,0,0,0.3);
}

.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding: 20px;
}

.card {
  background: #1e293b;
  padding: 20px;
  border-radius: 15px;
  width: 260px;
  text-align: center;
  transition: 0.3s;
  box-shadow: 0 0 20px rgba(0,0,0,0.5);
}

.card:hover {
  transform: scale(1.05);
}

.price {
  font-size: 22px;
  margin: 10px 0;
  color: #22c55e;
}

button {
  background: linear-gradient(45deg, #22c55e, #16a34a);
  border: none;
  padding: 12px;
  width: 100%;
  color: white;
  font-size: 16px;
  border-radius: 8px;
  cursor: pointer;
}

button:hover {
  opacity: 0.9;
}

.top {
  border: 2px solid gold;
}

footer {
  text-align: center;
  padding: 20px;
  opacity: 0.7;
}
</style>

</head>

<body>

<header>
💎 WixSiter — Донат Магазин
</header>

<div class="container">

  <div class="card">
    <h2>🔥 VIP</h2>
    <p>Доступ к базовым привилегиям</p>
    <div class="price">50 грн</div>
    <button onclick="buy('VIP')">Купить</button>
  </div>

  <div class="card">
    <h2>⚡ Премиум</h2>
    <p>Больше возможностей и бонусов</p>
    <div class="price">100 грн</div>
    <button onclick="buy('Премиум')">Купить</button>
  </div>

  <div class="card top">
    <h2>👑 Легенда</h2>
    <p>Максимальный статус + все плюшки</p>
    <div class="price">200 грн</div>
    <button onclick="buy('Легенда')">Купить</button>
  </div>

</div>

<footer>
📩 Telegram: @yourname  
<br>© 2026 WixSiter
</footer>

<script>
function buy(item) {
  window.location.href = "https://t.me/yourname?text=Хочу купить " + item;
}
</script>

</body>
</html>

# wixsiter-
