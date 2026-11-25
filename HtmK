
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KlarexxSMP — Minecraft Server</title>
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: Arial, sans-serif;
  background: #071321;
  color: white;
  overflow-x: hidden;
}
body::before {
  content: "";
  position: fixed;
  inset: 0;
  background:
    radial-gradient(circle at 20% 20%, #087e8b33, transparent 35%),
    radial-gradient(circle at 80% 70%, #174c8b44, transparent 35%);
  z-index: -1;
}
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 22px 8%;
  background: #071321cc;
  border-bottom: 1px solid #20d9d055;
}
.logo {
  color: #35e5df;
  font-size: 25px;
  font-weight: bold;
}
nav a {
  color: white;
  text-decoration: none;
  margin-left: 20px;
  transition: .3s;
}
nav a:hover {
  color: #35e5df;
}
.hero {
  min-height: 85vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 30px 20px;
}
.hero h1 {
  font-size: clamp(42px, 9vw, 85px);
  color: #4ce9e1;
  text-shadow: 0 0 30px #13d9d9aa;
  animation: appear 1.2s ease;
}
.hero p {
  color: #a9c6d8;
  font-size: 19px;
  margin: 20px 0 30px;
}
.ip {
  padding: 17px 25px;
  border: 1px solid #35e5df;
  border-radius: 12px;
  background: #10283a;
  color: #6ff9f0;
  font-size: 19px;
  margin-bottom: 18px;
}
button {
  background: linear-gradient(90deg,#12aaa9,#36e5d7);
  color: #061521;
  border: none;
  padding: 15px 28px;
  border-radius: 10px;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  transition: .3s;
}
button:hover {
  transform: translateY(-4px);
  box-shadow: 0 0 25px #26e5df88;
}
section {
  padding: 65px 8%;
  text-align: center;
}
h2 {
  color: #4ce9e1;
  font-size: 32px;
  margin-bottom: 35px;
}
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(210px,1fr));
  gap: 20px;
}
.card {
  background: #10283a;
  border: 1px solid #1c6672;
  border-radius: 15px;
  padding: 30px 20px;
  transition: .3s;
}
.card:hover {
  transform: translateY(-8px);
  border-color: #4ce9e1;
  box-shadow: 0 0 25px #18d6d633;
}
.card h3 {
  color: #4ce9e1;
  margin-bottom: 12px;
}
.card p {
  color: #a9c6d8;
}
.telegram {
  margin-top: 20px;
}
.telegram a {
  color: #4ce9e1;
  text-decoration: none;
  font-size: 18px;
}
footer {
  padding: 25px;
  text-align: center;
  color: #7895a9;
  border-top: 1px solid #1c6672;
}
@keyframes appear {
  from {opacity:0; transform:translateY(30px);}
  to {opacity:1; transform:translateY(0);}
}
html {
  scroll-behavior: smooth;
}
</style>
</head>
<body>

<header>
  <div class="logo">KLAREXXSMP</div>
  <nav>
    <a href="#about">О сервере</a>
    <a href="#features">Возможности</a>
    <a href="#contacts">Контакты</a>
  </nav>
</header>

<div class="hero">
  <h1>KLAREXXSMP</h1>
  <p>Твоя история начинается здесь!</p>
  <div class="ip">klarexxsmp.mcsh.gg</div>
  <button onclick="copyIP()">КОПИРОВАТЬ IP</button>
  <p id="message"></p>
</div>

<section id="about">
  <h2>О НАШЕМ СЕРВЕРЕ</h2>
  <p>Добро пожаловать на KlarexxSMP!
  Здесь тебя ждут приключения, экономика,
  друзья и множество интересных механик.</p>
  <p style="color:#4ce9e1;margin-top:20px">
    Minecraft Java • Версия 1.21.11
  </p>
</section>

<section id="features">
  <h2>ВОЗМОЖНОСТИ</h2>
  <div class="cards">
    <div class="card">
      <h3>⚔️ Survival</h3>
      <p>Классическое выживание в Minecraft.</p>
    </div>
    <div class="card">
      <h3>💰 Экономика</h3>
      <p>Торгуй и развивай своё состояние.</p>
    </div>
    <div class="card">
      <h3>🏰 Приваты</h3>
      <p>Защищай свои территории.</p>
    </div>
    <div class="card">
      <h3>👥 Кланы</h3>
      <p>Создавай команду и играй вместе.</p>
    </div>
    <div class="card">
      <h3>🎁 Награды</h3>
      <p>Получай ежедневные бонусы.</p>
    </div>
    <div class="card">
      <h3>🏆 Ивенты</h3>
      <p>Участвуй в событиях сервера.</p>
    </div>
  </div>
</section>

<section id="contacts">
  <h2>НАШ TELEGRAM</h2>
  <p>Следи за новостями и конкурсами сервера!</p>
  <div class="telegram">
    <a href="https://t.me/klarexsmpezz1" target="_blank">
      ПЕРЕЙТИ В TELEGRAM →
    </a>
  </div>
</section>

<footer>
  © 2026 KlarexxSMP. Все права защищены.
</footer>

<script>
function copyIP() {
  navigator.clipboard.writeText("klarexxsmp.mcsh.gg")
    .then(() => {
      document.getElementById("message").textContent =
        "IP успешно скопирован!";
    })
    .catch(() => {
      document.getElementById("message").textContent =
        "Скопируй IP вручную: klarexxsmp.mcsh.gg";
    });
}
</script>

</body>
</html>

